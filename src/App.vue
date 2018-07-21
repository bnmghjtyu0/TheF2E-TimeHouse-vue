<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary fixed-top">
      <a class="navbar-brand"
        href="../index.html">
        <i class="mdi mdi-home"></i>
      </a>
      <button class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse"
        id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <a class="nav-link"
              href="../index.html">Home
              <span class="sr-only">(current)</span>
            </a>
          </li>
        </ul>
      </div>
    </nav>
    <section class="sidebar">
      <button class="btn switch"
        v-on:click="kk()">
        <i class="fas fa-angle-right"></i>
      </button>
      <ul class="floor-one">
        <li>
          <button class="btn dropdown-toggle"
            data-toggle="collapse"
            aria-expanded="false"
            data-target="#menu01"
            aria-controls="menu01">
            前端時光屋
          </button>
          <div class="collapse show"
            id="menu01">
            <ul class="floor-two">
              <li>
                <h6 class="dropdown-header d-flex no-gutters">
                  <div class="mr-auto">第一週: TODOLIST</div>
                  <div class="ml-auto">
                    <a href="https://hexschool.github.io/THE_F2E_Design/todolist/"
                      class="link"
                      target="_blank">設計檔</a>
                    <a href="./F2E/01.todolist.html"
                      class="link">實作</a>
                  </div>
                </h6>
                <span class="deadline">2018/06/02 ~ 2018/06/09</span>
              </li>
              <li>
                <h6 class="dropdown-header d-flex no-gutters">
                  <div class="mr-auto">第二週: FILTER</div>
                  <div class="ml-auto">
                    <a href="https://hexschool.github.io/THE_F2E_Design/week2-filter"
                      target="_blank"
                      class="link">設計檔</a>
                    <a href="./F2E/02.filter.html"
                      class="link">實作</a>
                  </div>
                </h6>
                <span class="deadline">2018/06/09 ~ 2018/06/16</span>
              </li>
              <li>
                <h6 class="dropdown-header d-flex no-gutters">
                  <div class="mr-auto">第三週: ORDER</div>
                  <div class="ml-auto">
                    <a href="https://hexschool.github.io/THE_F2E_Design/week3-admin%20order/"
                      target="_blank"
                      class="link">設計檔</a>
                    <a href="./F2E/03.orderBackend.html"
                      class="link">實作</a>
                  </div>
                </h6>
                <span class="deadline">2018/06/17 ~ 2018/06/24</span>
              </li>
              <li>
                <h6 class="dropdown-header d-flex no-gutters">
                  <div class="mr-auto">第四週:PRODUCT</div>
                  <div class="ml-auto">
                    <a href="https://hexschool.github.io/THE_F2E_Design/week4-product%20gallery/"
                      target="_blank"
                      class="link">設計檔</a>
                    <a href="./F2E/04.product.html"
                      class="link">實作</a>
                  </div>
                </h6>
                <span class="deadline">2018/06/25 ~ 2018/07/01</span>
              </li>
              <li>
                <h6 class="dropdown-header d-flex no-gutters">
                  <div class="mr-auto">第五週:COMIC</div>
                  <div class="ml-auto">
                    <a href="https://hexschool.github.io/THE_F2E_Design/week5-comic%20viewer/"
                      target="_blank"
                      class="link">設計檔</a>
                    <a href="./F2E/05.comic.html"
                      class="link">實作</a>
                  </div>
                </h6>
                <span class="deadline">2018/07/02 ~ 2018/07/08</span>
              </li>
              <li>
                <h6 class="dropdown-header d-flex no-gutters">
                  <div class="mr-auto">第六週:Validation</div>
                  <div class="ml-auto">
                    <a href="https://hexschool.github.io/THE_F2E_Design/week6-validation/#artboard0"
                      target="_blank"
                      class="link">設計檔</a>
                    <a href="./F2E/06.validation.html"
                      class="link">實作</a>
                  </div>
                </h6>
                <span class="deadline">2018/07/09 ~ 2018/07/15</span>
              </li>
              <li>
                <h6 class="dropdown-header d-flex no-gutters">
                  <div class="mr-auto">第七週:canvas 遊戲</div>
                  <div class="ml-auto">
                    <a href="https://hackmd.io/N5yEjm2vSx6D41qAbJGDmw"
                      target="_blank"
                      class="link">設計檔</a>
                    <a href="./F2E/07.canvas.html"
                      class="link">實作</a>
                  </div>
                </h6>
                <span class="deadline">2018/07/16 ~ 2018/07/22</span>
              </li>
            </ul>
          </div>
        </li>
      </ul>
    </section>

    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
  methods: {
    kk: function() {
      console.log(123)
    }
    // switch: function() {
    //   console.log('123')
    //   // let sidebar = document.querySelector('.sidebar')
    //   // sidebar.classList.toggle('show')
    //   // this.$emit('toggle')
    // }
  }
}
</script>

<style lang="scss">
@import './assets/css/main.scss';
</style>
