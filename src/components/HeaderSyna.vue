<template>
  <div id="header">
    <div class="container">
      <div class="row justify-content-between">
        <div class="col-lg-2 m-1">
          <img class="logo-syna" src="../assets/logo2.png" alt />
        </div>
        <div class="col-lg-6 m-1">
            <input class="form-control" type="text" placeholder="Belanja apa hari ini ... ">
        </div>
        <div class="col-lg-1">
             <i class="fa fa-shopping-cart" aria-hidden="true"></i>
        </div>
        <div class="col-lg-2">
            | <button class="btn btn-outline-warning m-1">Daftar</button>
              <button class="btn btn-success">Masuk</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.css'


export default {
  name: "HeaderSyna",
};
</script>

<style>
template{
    margin: 0px;
    padding: 0px;
}

#header .logo-syna {
  width: 200px;
  height: auto;
}
</style>