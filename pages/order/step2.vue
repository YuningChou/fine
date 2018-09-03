<template>
  <div class="col-md-8 order-md-1">
    <h4 class="mb-3 text-primary">Step 2 . 付款與取貨</h4>
    <hr>
    <form class="needs-validation" novalidate="">
      <div class="row">
        <div class="col-md-7 mb-5">
          <h5 class="mb-3"><i class="far fa-money-bill-alt"></i> 付款方式</h5>
          <div class="btn-group-toggle" data-toggle="buttons">
            <label class="btn btn-outline-primary btn-lg mr-2 active">
              <input type="radio" name="paymentMethod" id="credit" autocomplete="off" checked> 信用卡
            </label>
            <label class="btn btn-outline-primary btn-lg mr-2">
              <input type="radio" name="paymentMethod" id="webatm" autocomplete="off"> WEBATM
            </label>
            <label class="btn btn-outline-primary btn-lg mr-2">
              <input type="radio" name="paymentMethod" id="atm" autocomplete="off"> ATM
            </label>
            <label class="btn btn-outline-primary btn-lg mr-2">
              <input type="radio" name="paymentMethod" id="convenience" autocomplete="off"> 超商繳費
            </label>
            <label class="btn btn-outline-primary btn-lg mr-2">
              <input type="radio" name="paymentMethod" id="cash" autocomplete="off"> 現金繳費
            </label>
          </div>
        </div>

        <div class="col-md-5 mb-5">
          <h5 class="mb-3"><i class="fas fa-shipping-fast"></i> 取貨方式</h5>
          <div class="btn-group-toggle" data-toggle="buttons">
            <label class="btn btn-outline-primary btn-lg mr-2 active">
              <input type="radio" name="shipMethod" id="finemifi" autocomplete="off" checked> FineMifi公司取貨
            </label>
            <label class="btn btn-outline-primary btn-lg mr-2">
              <input type="radio" name="shipMethod" id="ship" autocomplete="off"> 宅配到府
            </label>
          </div>
        </div>

        <div class="col-md-12 mb-5">
          <h5 class="mb-3"><i class="fas fa-user"></i> 取貨人資料</h5>
          <div class="row">
              <div class="col-md-6 mb-3">
                <label for="firstName">姓名</label>
                <input type="text" class="form-control" id="firstName" placeholder="" value="" required="">
                <div class="invalid-feedback">
                  Valid first name is required.
                </div>
              </div>
              <div class="col-md-6 mb-3">
                <label for="lastName">連絡電話</label>
                <input type="text" class="form-control" id="lastName" placeholder="" value="" required="">
                <div class="invalid-feedback">
                  Valid last name is required.
                </div>
              </div>
              <div class="col-md-6 mb-3">
                <label for="lastName">電子信箱</label>
                <input type="email" class="form-control" id="lastName" placeholder="" value="" required="">
                <div class="invalid-feedback">
                  Valid last name is required.
                </div>
              </div>
              <div class="col-md-6 mb-3">
                <label for="lastName">收件地址</label>
                <input type="text" class="form-control" id="lastName" placeholder="" value="" required="">
                <div class="invalid-feedback">
                  Valid last name is required.
                </div>
              </div>
              <div class="col-md-12 mb-3">
                <label for="lastName">備註</label>
                <textarea type="text" class="form-control" id="lastName" placeholder="" value=""></textarea>
              </div>
            </div>
        </div>
      </div>
      <div class="text-center">
        <nuxt-link class="btn btn-outline-primary btn-lg mx-2" to="/order">回上一步</nuxt-link>
        <nuxt-link class="btn btn-primary btn-lg mx-2" to="/order/checkout">下一步</nuxt-link>
      </div>
    </form>
  </div>
</template>


<script>
export default {
  layout:'order',
}
</script>


