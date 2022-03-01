<template>
  <nav class="navbar navbar-expand-md navbar-dark bg-dark">
    <div class="container">
        <a href="" class="navbar-brand">LOGO</a>
      <button type="button" class="navbar-toggler" data-bs-target="#menu" data-bs-toggle="collapse">
          <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="menu">
        <ul class="navbar-nav ms-auto">
          <li>
            <router-link :to="{name: 'home'}" class="nav-link">Home</router-link>
          </li>
          <li>
            <router-link :to="{name: 'about'}" class="nav-link">About</router-link>
          </li>
          <li>
            <router-link :to="{name: 'service'}" class="nav-link">Services</router-link>
          </li>
          <li>
            <a href="" class="nav-link">Gallery</a>
          </li>
          <li>
            <a href="" class="nav-link">Contact</a>
          </li>
          <li>
            <a href="" class="nav-link">Login</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <router-view/>
  <section class="py-5 bg-dark text-white">
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <h1>This is footer one</h1>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque dui tortor, placerat ut massa nec, pellentesque semper justo. Sed ultricies varius mi, in luctus lorem finibus id. Cras elementum libero vel sapien porta, ut varius turpis tempus. Integer consequat dui sit amet lorem fermentum facilisis. Etiam iaculis turpis libero, nec cursus eros placerat et. Mauris vestibulum tortor ac nisi interdum tempus. Phasellus vel dictum urna</p>
          <p>Aliquam tempus magna eget ipsum fermentum porttitor. Vivamus eu justo a est suscipit semper et a orci. Quisque nisi dui, tincidunt eu orci sed, blandit tempus mi. In id augue feugiat quam dignissim malesuada. </p>
        </div>
        <div class="col-md-4">
          <h1>This is footer two</h1>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque dui tortor, placerat ut massa nec, pellentesque semper justo. Sed ultricies varius mi, in luctus lorem finibus id. Cras elementum libero vel sapien porta, ut varius turpis tempus. Integer consequat dui sit amet lorem fermentum facilisis. Etiam iaculis turpis libero, nec cursus eros placerat et. Mauris vestibulum tortor ac nisi interdum tempus. Phasellus vel dictum urna</p>
          <p>Aliquam tempus magna eget ipsum fermentum porttitor. Vivamus eu justo a est suscipit semper et a orci. Quisque nisi dui, tincidunt eu orci sed, blandit tempus mi. In id augue feugiat quam dignissim malesuada. </p>
        </div>
        <div class="col-md-4">
          <h1>This is footer three</h1>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque dui tortor, placerat ut massa nec, pellentesque semper justo. Sed ultricies varius mi, in luctus lorem finibus id. Cras elementum libero vel sapien porta, ut varius turpis tempus. Integer consequat dui sit amet lorem fermentum facilisis. Etiam iaculis turpis libero, nec cursus eros placerat et. Mauris vestibulum tortor ac nisi interdum tempus. Phasellus vel dictum urna</p>
          <p>Aliquam tempus magna eget ipsum fermentum porttitor. Vivamus eu justo a est suscipit semper et a orci. Quisque nisi dui, tincidunt eu orci sed, blandit tempus mi. In id augue feugiat quam dignissim malesuada. </p>
        </div>
      </div>
    </div>
  </section>
</template>
<script>

</script>
<style>

</style>
