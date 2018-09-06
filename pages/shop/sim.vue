<template>
  <div>
    <div class="bg-light container">
      <div class="row">
        <div class="col">
          <nuxt-link class="py-2 d-block text-center h4 mb-0" to="/shop/wifi">WiFi</nuxt-link>
        </div>
        <div class="col">
          <nuxt-link class="py-2 d-block text-center h4 mb-0 border-bottom border-primary" to="/shop/sim"> SIM</nuxt-link>
        </div>
      </div>
    </div>
    <div class="container py-3 form-banner">
      <form>
        <div class="form-group">
          <label for="exampleFormControlSelect1">旅遊區域</label>
          <select class="form-control" id="exampleFormControlSelect1">
            <option>日本</option>
            <option>韓國</option>
            <option>中國</option>
            <option>歐洲</option>
            <option>美洲</option>
          </select>
        </div>
        <button type="submit" class="btn btn-primary btn-block mt-3">送出</button>
      </form>
    </div>
    <h3 class="text-center m-3"><i class="fab fa-hotjar text-danger"></i> 熱門商品 <i class="fab fa-hotjar text-danger"></i></h3>
    <div class="container">
      <div class="row">
        <div class="col-6 px-2">
          <div class="card mb-4 box-shadow">
            <img class="card-img-top" style="height: 150px; width: 100%; display: block;" src="https://picsum.photos/150/150?image=0" >
            <div class="card-body">
              <p class="card-text">Fine</p>
            </div>
          </div>
        </div>
        <div class="col-6 px-2">
          <div class="card mb-4 box-shadow">
            <img class="card-img-top" style="height: 150px; width: 100%; display: block;"  src="https://picsum.photos/150/150?image=2" >
            <div class="card-body">
              <p class="card-text">Fine</p>
            </div>
          </div>
        </div>
        <div class="col-6 px-2">
          <div class="card mb-4 box-shadow">
            <img class="card-img-top" style="height: 150px; width: 100%; display: block;"  src="https://picsum.photos/150/150?image=3" >
            <div class="card-body">
              <p class="card-text">Fine</p>
            </div>
          </div>
        </div>

        <div class="col-6 px-2">
          <div class="card mb-4 box-shadow">
            <img class="card-img-top" style="height: 150px; width: 100%; display: block;"  src="https://picsum.photos/150/150?image=7" >
            <div class="card-body">
              <p class="card-text">Fine</p>
            </div>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  layout:'shop',
}
</script>

<style>
  .form-banner{
    background:url('https://picsum.photos/600/450?image=302');
    background-size:cover;
  }
</style>


