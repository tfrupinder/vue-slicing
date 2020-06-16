<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a href="#" class="btn navbar-brand">Logo Here</a>
      <div class="navbar-nav ml-auto">
        <li class="nav-item ml-auto mx-auto w-100px">
          <div class="dropdown">
            <a class="btn btn-none dropdown-toggle" data-toggle="collapse" data-target="#collapsibleNavbar">
              Eng
            </a>
            <div class="dropdown-menu" id="collapsibleNavbar">
              <a class="dropdown-item" href="#">Link 1</a>
              <a class="dropdown-item" href="#">Link 2</a>
              <a class="dropdown-item" href="#">Link 3</a>
            </div>
          </div>
        </li>
        <li class="nav-item mx-auto w-100px">
          <span class="navbar-toggler-icon"></span>
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
