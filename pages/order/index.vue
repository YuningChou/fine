<template>
  <div class="col-md-8 order-md-1">
    <h4 class="mb-3 text-primary">Step 1 . 請告訴我們您的旅遊上網需求</h4>
    <hr>
    <form class="needs-validation" novalidate="">
      <div class="row">
        <div class="col-md-6 mb-3">
          <label for="country">旅遊地點</label>
          <select class="custom-select d-block w-100" id="country" required="">
            <option value="">請選擇...</option>
            <option>日本</option>
          </select>
          <div class="invalid-feedback">
            Please select a valid country.
          </div>
        </div>
        <div class="col-md-6 mb-3">
          <label for="state">選擇套餐</label>
          <select class="custom-select d-block w-100" id="state" required="">
            <option value="">請選擇...</option>
            <option>東北亞日韓4G上網</option>
          </select>
          <div class="invalid-feedback">
            Please provide a valid state.
          </div>
        </div>
        <div class="col-md-6 mb-3">
          <label for="state">旅遊日期</label>
          <div class="row">
            <div class="col">
              <input type="date" class="form-control">
            </div>
            ~
            <div class="col">
              <input type="date" class="form-control">
            </div>
          </div>
        </div>
        <div class="col-md-6 mb-3">
          <label for="state">上網天數</label>
          <input type="text" class="form-control" placeholder="填寫上網所需天數 例如: 3">
        </div>
      </div>
      <h4 class="mb-3 text-primary"><i class="fas fa-wifi"></i> 以下是您選擇的商品,請確認</h4>
      <hr>
      <div class="row">
        <div class="col-md-12">
          <div class="card flex-md-row mb-4 box-shadow h-md-250">
            <div class="card-body d-flex flex-column align-items-start">
              <h3 class="mb-1">
                <a class="text-dark mr-3" href="#">東北亞日韓4G上網</a>
                <strong class="d-inline-block mb-2 text-danger">3日</strong>
              </h3>
              <h2 class="card-title pricing-card-title">$199 <small class="text-muted">/ day</small></h2>
              <ul class="list-unstyled mt-2 mb-2">
                <li><i class="fas fa-check text-success mr-2"></i>不限速</li>
                <li><i class="fas fa-check text-success mr-2"></i>可支持5台設備同步連線上網(內網與外網)</li>
                <li><i class="fas fa-check text-success mr-2"></i>電池容量5000mHA(長待型)</li>
                <li><i class="fas fa-check text-success mr-2"></i>支援外接4G SIM卡插槽向下兼容3G</li>
                <li><i class="fas fa-check text-success mr-2"></i>產品皆附中文說明書、USB充電線、專屬旅行箱級保護殼</li>
              </ul>
            </div>
            <img class="card-img-right flex-auto d-none d-lg-block px-5" src="~/static/wifi.svg" >
            <button type="button" class="btn btn-danger btn-sm rounded-0"  style="position:absolute;right:0;bottom:0"><i class="far fa-times-circle"></i> 不要了</button>
          </div>
        </div>
      </div>
      <div class="text-center">
        <nuxt-link class="btn btn-outline-primary btn-lg mx-2" to="/">再逛逛</nuxt-link>
        <nuxt-link class="btn btn-primary btn-lg mx-2" to="/order/step2">下一步</nuxt-link>
      </div>
    </form>
  </div>
</template>


<script>
export default {
  layout:'order',
}
</script>


