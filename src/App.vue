<template>
  <div id="app">
    <ul id="dropdown1" class="dropdown-content">
      <li> <a>Pets</a> </li>
      <li><a>Friends</a></li>
    </ul>
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
        <div class="input-field col s5 offset-s3">
          <div class="col s2 m2 l2">
            <ul id="nav-mobile" >
              <li><a class="dropdown-button"  data-activates="dropdown1">Dropdown<i class="material-icons right">arrow_drop_down</i></a></li>
            </ul>
          </div>
          <div class="col s1 m1 l1"></div>
          <div class="col s1 m1 l1 ">
            <i class="material-icons">search</i>
          </div>
          <div class="col s8 m8 l8 ">
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
