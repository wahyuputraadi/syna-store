<template>
  <div id="header">
    <div class="container">
      <div class="row justify-content-between">
        <div class="col-lg-3">
          <img src="../img/LogoSynaStore.png" alt />
        </div>
        <div class="col-lg-5">
            <input class="form-control" type="text" placeholder="Belanja apa hari ini ...  "> 
        </div>
        <div class="col-lg-1 p-1">
             <img class="favorit" src="../img/favorit.png" alt="">
        </div>
          <div class="col-lg-1">
             <img class="keranjang" src="../img/keranjang.png" alt="">
        </div>
        <div class="col-lg-1">
            <button class="btn btn-outline-warning">Daftar</button>
        </div>
        <div class="col-lg-1">
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


</style>