<template>
  <div>
    <main class="main">
      <div class="card">
        <div class="card-header">
          v-checkbox 、 v-radio

        </div>
        <div class="card-body">

          <div class="d-flex">
            <div class="col">
              <div class="d-flex">
                <label class="v-label mr-3">radio01
                  <input type="radio"
                    name="sex"
                    checked>
                  <span class="checkmark"></span>
                </label>

                <label class="v-label">radio02
                  <input type="radio"
                    name="sex">
                  <span class="checkmark"></span>
                </label>
              </div>

              <pre v-highlightjs
                class="border border-primary mt-3">
            <code class="html">
  import radio&checkbox.css
                
  &lt;label class=&quot;v-label mr-3&quot;&gt;radio01
    &lt;input type=&quot;radio&quot; name=&quot;sex&quot; checked&gt;
    &lt;span class=&quot;checkmark&quot;&gt;&lt;&#x2F;span&gt;
  &lt;&#x2F;label&gt;

  &lt;label class=&quot;v-label&quot;&gt;radio02
    &lt;input type=&quot;radio&quot; name=&quot;sex&quot;&gt;
    &lt;span class=&quot;checkmark&quot;&gt;&lt;&#x2F;span&gt;
  &lt;&#x2F;label&gt;
            </code>
          </pre>
            </div>
            <div class="col">
              <div class="d-flex">
                <label class="v-label mr-3">check01
                  <input type="checkbox"
                    checked="checked">
                  <span class="checkmark"></span>
                </label>

                <label class="v-label mr-3">check02
                  <input type="checkbox">
                  <span class="checkmark"></span>
                </label>
              </div>
              <pre v-highlightjs
                class="border border-primary mt-3">
                      <code class="html">
  import radio&checkbox.css
  
  &lt;label class=&quot;v-label mr-3&quot;&gt;One
    &lt;input type=&quot;checkbox&quot; checked=&quot;checked&quot;&gt;
    &lt;span class=&quot;checkmark&quot;&gt;&lt;&#x2F;span&gt;
  &lt;&#x2F;label&gt;

  &lt;label class=&quot;v-label mr-3&quot;&gt;Two
    &lt;input type=&quot;checkbox&quot;&gt;
    &lt;span class=&quot;checkmark&quot;&gt;&lt;&#x2F;span&gt;
  &lt;&#x2F;label&gt;
                      </code>
                    </pre>
            </div>
          </div>
        </div>
      </div>
      <div class="card mt-3">
        <div class="card-header">
          v-select
        </div>
        <div class="card-body">
          <div class="v-select"
            style="width:200px;">
            <select class="form-control">
              <option value="0">Select car:</option>
              <option value="1">Audi</option>
              <option value="2">BMW</option>
              <option value="3">Citroen</option>
              <option value="4">Ford</option>
              <option value="5">Honda</option>
              <option value="6">Jaguar</option>
              <option value="7">Land Rover</option>
              <option value="8">Mercedes</option>
              <option value="9">Mini</option>
              <option value="10">Nissan</option>
              <option value="11">Toyota</option>
              <option value="12">Volvo</option>
            </select>
          </div>
          <pre v-highlightjs
            class="border border-primary mt-3">
  <code class="html">
  import select.css
  import select.js

  &lt;div class=&quot;v-select&quot; style=&quot;width:200px;&quot;&gt;
    &lt;select class=&quot;form-control&quot;&gt;
      &lt;option value=&quot;0&quot;&gt;Select car:&lt;&#x2F;option&gt;
      &lt;option value=&quot;1&quot;&gt;Audi&lt;&#x2F;option&gt;
      &lt;option value=&quot;2&quot;&gt;BMW&lt;&#x2F;option&gt;
      &lt;option value=&quot;3&quot;&gt;Citroen&lt;&#x2F;option&gt;
      &lt;option value=&quot;4&quot;&gt;Ford&lt;&#x2F;option&gt;
      &lt;option value=&quot;5&quot;&gt;Honda&lt;&#x2F;option&gt;
      &lt;option value=&quot;6&quot;&gt;Jaguar&lt;&#x2F;option&gt;
      &lt;option value=&quot;7&quot;&gt;Land Rover&lt;&#x2F;option&gt;
      &lt;option value=&quot;8&quot;&gt;Mercedes&lt;&#x2F;option&gt;
      &lt;option value=&quot;9&quot;&gt;Mini&lt;&#x2F;option&gt;
      &lt;option value=&quot;10&quot;&gt;Nissan&lt;&#x2F;option&gt;
      &lt;option value=&quot;11&quot;&gt;Toyota&lt;&#x2F;option&gt;
      &lt;option value=&quot;12&quot;&gt;Volvo&lt;&#x2F;option&gt;
    &lt;&#x2F;select&gt;
  &lt;&#x2F;div&gt;
  </code>
</pre>
        </div>
      </div>
      <div class="card mt-3">
        <div class="card-header">
          v-switch
        </div>
        <div class="card-body">
          <label class="switch">
            <input type="checkbox">
            <span class="slider"></span>
          </label>
          <pre v-highlightjs
            class="border border-primary mt-3">
              <code class="html">
  import switch.css
            
  &lt;label class=&quot;switch&quot;&gt;
    &lt;input type=&quot;checkbox&quot;&gt;
    &lt;span class=&quot;slider&quot;&gt;&lt;&#x2F;span&gt;
  &lt;&#x2F;label&gt;
              </code>
            </pre>
        </div>
      </div>

      <div class="card mt-3">
        <div class="card-header">
          star
        </div>
        <div class="card-body">
          <ul class="star">
            <li>
              <i class="fas fa-star"></i>
            </li>
            <li>
              <i class="fas fa-star"></i>
            </li>
            <li>
              <i class="fas fa-star"></i>
            </li>
            <li>
              <i class="fas fa-star"></i>
            </li>
            <li>
              <i class="fas fa-star"></i>
            </li>
          </ul>
          <pre v-highlightjs
            class="border border-primary mt-3">
              <code class="html">
  import fontawesome5.css
  import ./components/_star.scss
            
  &lt;ul class=&quot;star&quot;&gt;
    &lt;li&gt;
      &lt;i class=&quot;fas fa-star&quot;&gt;&lt;&#x2F;i&gt;
    &lt;&#x2F;li&gt;
    &lt;li&gt;
      &lt;i class=&quot;fas fa-star&quot;&gt;&lt;&#x2F;i&gt;
    &lt;&#x2F;li&gt;
    &lt;li&gt;
      &lt;i class=&quot;fas fa-star&quot;&gt;&lt;&#x2F;i&gt;
    &lt;&#x2F;li&gt;
    &lt;li&gt;
      &lt;i class=&quot;fas fa-star&quot;&gt;&lt;&#x2F;i&gt;
    &lt;&#x2F;li&gt;
    &lt;li&gt;
      &lt;i class=&quot;fas fa-star&quot;&gt;&lt;&#x2F;i&gt;
    &lt;&#x2F;li&gt;
  &lt;&#x2F;ul&gt;
              </code>
            </pre>
        </div>
      </div>
      <div class="card mt-3">
        <div class="card-header">
          timeline
        </div>
        <div class="card-body">
          <div class="col-6 offset-3">
            <nav class="timeline">
              <ul>
                <li class="active"
                  data-list="1"></li>
                <li data-list="2"></li>
                <li data-list="3"></li>
                <li data-list="4"></li>
              </ul>
            </nav>
          </div>
          <pre v-highlightjs
            class="border border-primary mt-3">
                <code class="html">
    import ./components/_timeline.scss
              
  &lt;nav class=&quot;timeline&quot;&gt;
    &lt;ul&gt;
      &lt;li class=&quot;active&quot; data-list=&quot;1&quot;&gt;&lt;&#x2F;li&gt;
      &lt;li data-list=&quot;2&quot;&gt;&lt;&#x2F;li&gt;
      &lt;li data-list=&quot;3&quot;&gt;&lt;&#x2F;li&gt;
      &lt;li data-list=&quot;4&quot;&gt;&lt;&#x2F;li&gt;
    &lt;&#x2F;ul&gt;
  &lt;&#x2F;nav&gt;
                </code>
              </pre>
        </div>
      </div>
    </main>

  </div>

</template>
  
<script>
export default {
  name: 'index'
}
</script>
