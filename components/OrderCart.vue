<template>
  <div class="col-md-4 order-md-2 mb-4 d-none d-md-block">
    <h4 class="d-flex justify-content-between align-items-center mb-3">
      <span class="text-muted"><i class="fas fa-shopping-cart"></i> 您的購物車</span>
      <span class="badge badge-secondary badge-pill">1</span>
    </h4>
    <ul class="list-group mb-3">
      <li class="list-group-item d-flex justify-content-between lh-condensed">
        <div>
          <h6 class="my-0">東北亞日韓4G上網 <span class="ml-3 text-danger">$199 <small class="text-muted">/ day</small></span></h6>
          <small class="text-danger">3日</small>
        </div>
        <span class="text-muted">${{199*3}}</span>
      </li>
      <li class="list-group-item d-flex justify-content-between bg-light">
        <div class="text-success">
          <h6 class="my-0">優惠券</h6>
          <small>優惠券碼: OOXXOOX</small>
        </div>
        <span class="text-success">-$5</span>
      </li>
      <li class="list-group-item d-flex justify-content-between">
        <span>Total (TWD))</span>
        <strong>${{199*3-5}}</strong>
      </li>
    </ul>

    <form class="card p-2 mb-3">
      <div class="input-group">
        <input type="text" class="form-control" placeholder="請輸入優惠代碼">
        <div class="input-group-append">
          <button type="submit" class="btn btn-success">輸入</button>
        </div>
      </div>
    </form>
    <div class="form-check">
      <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
      <label class="form-check-label" for="defaultCheck1">
        我已經閱讀購物條款
      </label>
    </div>
    <button class="btn btn-primary btn-lg btn-block mt-3" type="submit">沒問題 ! 結帳</button>
    <button class="btn btn-outline-danger mt-5 d-block mx-auto">下次不想填這麼多資料? 想知道獲得優惠方式?<br>
      <span class="font-weight-bold h4"><i class="far fa-hand-point-right"></i> 快成為會員吧! <i class="far fa-hand-point-left"></i></span>
    </button>
  </div>
</template>
