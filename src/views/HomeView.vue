<template>
  <div class="home">
    <div class="carousel slide" id="slider" data-bs-ride="carousel" data-bs-interval="1800">
      <ol class="carousel-indicators">
        <li data-bs-target="#slider" data-bs-slide-to="0" class="active"></li>
        <li data-bs-target="#slider" data-bs-slide-to="1"></li>
        <li data-bs-target="#slider" data-bs-slide-to="2"></li>

      </ol>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="/img/1.jpg" alt="" class="w-100 h-400"/>
        </div>
        <div class="carousel-item">
          <img src="/img/2.jpg" alt="" class="w-100 h-400"/>
        </div>
        <div class="carousel-item">
          <img src="/img/3.jpg" alt="" class="w-100 h-400"/>
        </div>
      </div>
    </div>
    <section class="py-5">
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <div class="card">
              <img src="/img/shirt1.jpg" alt="" class="card-img h-300"/>
              <div class="card-body">
                <h3>Fashionable T-shirt</h3>
                <p>lorem epsum djsjfsnjnsjk</p>
                <hr/>
                <a href="" class="btn btn-success">Details</a>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card">
              <img src="/img/shirt2.jpg" alt="" class="card-img h-300"/>
              <div class="card-body">
                <h3>Fashionable T-shirt</h3>
                <p>lorem epsum djsjfsnjnsjk</p>
                <hr/>
                <a href="" class="btn btn-success">Details</a>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card">
              <img src="/img/shirt3.jpg" alt="" class="card-img h-300"/>
              <div class="card-body">
                <h3>Fashionable T-shirt</h3>
                <p>lorem epsum djsjfsnjnsjk</p>
                <hr/>
                <a href="" class="btn btn-success">Details</a>
              </div>
            </div>
          </div>
        </div>
      </div>

    </section>
  </div>
</template>

<script>


export default {
  name: 'HomeView',

}
</script>
<style></style>
