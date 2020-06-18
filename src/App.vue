<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a href="#" class="btn navbar-brand">Logo Here</a>
      <div class="navbar-nav ml-auto">
        <li class="nav-item ml-auto mx-auto w-100px">
          <div class="dropdown mr-2 mt-2">
            <a class="btn btn-none dropdown-toggle" data-toggle="dropdown">
              Eng
            </a>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="#">Link 1</a>
              <a class="dropdown-item" href="#">Link 2</a>
              <a class="dropdown-item" href="#">Link 3</a>
            </div>
          </div>
        </li>
        <li class="nav-item mr-5 w-100px">
          <div>
           <span class="navbar-toggler-icon icon-bar" ></span>  
          </div>
        </li>
      </div>
    </nav>

    <div>
      <router-view />
    </div>
  </div>
</template>

<script>
export default {
  name: "app",
};
</script>
<style scoped>
.icon-bar{
    font-size: 2em;
    color: #11C176 !important;
}
</style>