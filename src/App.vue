<template>
  <div id="app">
    <nav class='blue'>
      <div class="row">
        <div class="col s1 m1 l1">
          <div class="nav-wrapper">
            <a class="brand-logo">Prueba</a>
          </div>
        </div>
        <div class="col s3 m3 l3">
          <ul id="nav-mobile" >
            <li><a>Sass</a></li>
            <li><a>Components</a></li>
            <li><a>JavaScript</a></li>
          </ul>
        </div>
        <div class="input-field col s4 offset-s4">
          <div class="col s1 m1 l1 ">
            <i class="material-icons">search</i>
          </div>
          <div class="col s11 m11 l11 ">
            <input id="search" type="search" required>
          </div>
        </div> 
      </div>
    </nav>
    <hello></hello>
  </div>
</template>

<script>
import Hello from './components/Hello.vue'

export default {
  name: 'app',
  components: {
    Hello
  }
}
</script>
