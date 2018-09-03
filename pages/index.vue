<template>
  <div>
    <div class="d-md-flex flex-md-equal w-100 my-md-3 pl-md-3">
      <div class="bg-dark mr-md-3 pt-3 px-3 pt-md-5 px-md-5 text-center text-white overflow-hidden">
        <div class="my-3 py-3">
          <h2 class="display-5">全球行動上網分享器</h2>
          <p class="lead">全台首創4G Virtual SIM卡技術</p>
        </div>
        <div class="bg-light box-shadow mx-auto p-3" style="width: 80%; height: 300px; border-radius: 21px 21px 0 0;">
          <img src="../static/wifi.svg" width="75%">
        </div>
      </div>
      <div class="bg-light mr-md-3 pt-3 px-3 pt-md-5 px-md-5 text-center overflow-hidden">
        <div class="my-3 p-3">
          <h2 class="display-5">出國跨境行動上網預付卡</h2>
          <p class="lead">虛擬跨網分享應用「虛擬 SIM 卡」</p>
        </div>
        <div class="box-shadow mx-auto" style="width: 80%; height: 300px; border-radius: 21px 21px 0 0;">
          <img src="../static/sim.jpg" width="100%">
        </div>
      </div>
    </div>
    <div class="position-relative overflow-hidden p-3 m-md-3 text-center text-light banner">
      <div class="col-md-7 p-lg-5 mx-auto my-5">
        <h2 class="font-weight-normal">SIM卡與Wi-Fi分享器有什麼不同?</h2>
        <p class=" font-weight-normal">
          SIM卡僅供一台手機使用，如熱點分享會有耗電、斷線、網速下降..等問題，<br>
          且手機更換SIM卡，會使原先的號碼無法使用，而流失重要訊息等不便問題。<br>
          但Wi-Fi分享器可同時連接多台行動裝置，所以朋友間可彼此分擔價格，以更便宜的價格使用網路。
        </p>
      </div>
    </div>
    <div class="bg-dark pt-5">
      <div class="container marketing">
        <div class="row">
          <div class="col-lg-4 col-md-4">
            <img class="rounded-circle" src="../static/4g.svg" alt="Generic placeholder image" width="140" height="140">
            <p class="mt-3 text-light">全台首創4G Virtual SIM卡技術</p>
          </div><!-- /.col-lg-4 -->
          <div class="col-lg-4 col-md-4">
            <img class="rounded-circle" src="../static/users.svg" alt="Generic placeholder image" width="140" height="140">
            <p class="mt-3 text-light">可支持5台設備同步連線上網</p>
          </div><!-- /.col-lg-4 -->
          <div class="col-lg-4 col-md-4">
            <img class="rounded-circle" src="../static/save.svg" alt="Generic placeholder image" width="140" height="140">
            <p class="mt-3 text-light">流量使用選擇多，用多用少都輕鬆</p>
          </div><!-- /.col-lg-4 -->
        </div>
      </div>
    </div>
    <div class="d-md-flex flex-md-equal w-100 my-md-3 pl-md-3">
      <div class="bg-info mr-md-3 py-3 px-3 pt-md-5 px-md-5 text-center text-white overflow-hidden">
        <div class="mb-3 pb-2">
          <h2 class="display-5">口碑推薦</h2>
          <p class="lead">FineMifi全新出國上網體驗，盛情邀請20位部落客參與體驗，只要部落客即將要出國，出國區域是FineMifi涵蓋區，提出申請接觸後，將有專人與您聯繫說明體驗合作機制，及確認是否資格符合，真心期盼您的加入，一起分享美好上網體驗給更多旅人。</p>
        </div>
        <div class="mx-auto" style="width: 80%; height: 300px; border-radius: 21px 21px 0 0;">
          <div class="row">
            <div class="col-lg-6 col-md-12">
              <div class="d-flex my-3">
                <img class="rounded-circle mr-3" src="../static/users/user1.jpg" alt="Generic placeholder image" width="100" height="100">
                <p class="align-self-center text-left">John Doe<br>Fine / 資深媒體人</p>
              </div>
            </div>
            <div class="col-lg-6 col-md-12">
              <div class="d-flex my-3">
                <img class="rounded-circle mr-3" src="../static/users/user3.jpg" alt="Generic placeholder image" width="100" height="100">
                <p class="align-self-center text-left">Mary Chen<br>Fine / 旅遊部落客</p>
              </div>
            </div>
            <div class="col-lg-6 col-md-12">
              <div class="d-flex my-3">
                <img class="rounded-circle mr-3" src="../static/users/user15.jpg" alt="Generic placeholder image" width="100" height="100">
                <p class="align-self-center text-left">Wendy Jackson<br>Fine / 旅遊部落客</p>
              </div>
            </div>
            <div class="col-lg-6 col-md-12">
              <div class="d-flex my-3">
                <img class="rounded-circle mr-3" src="../static/users/user10.jpg" alt="Generic placeholder image" width="100" height="100">
                <p class="align-self-center text-left">Mike<br>Youtuber</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="bg-light mr-md-3 pt-3 px-3 pt-md-5 px-md-5 text-center overflow-hidden">
        <div class="mb-3 ">
          <h2 class="display-5">其他用戶怎麼說</h2>
        </div>
        <div class="mx-auto" style="width: 80%; height: 300px; border-radius: 21px 21px 0 0;">
          <div v-swiper:mySwiper="swiperOption">
            <div class="swiper-wrapper">
              <div class="swiper-slide">
                <div class="media text-muted pt-3">
                  <img class="rounded-circle mr-3" src="../static/users/user2.jpg" alt="Generic placeholder image" width="50" height="50">
                  <p class="media-body pb-3 mb-0  lh-125 border-gray text-left">
                    <strong class="d-block text-gray-dark">@Billy</strong>
                    出國上網最重視的除「價格」外，「上網品質、高速流量多寡」等都是旅途在乎的重點。
                  </p>
                </div>
              </div>
              <div class="swiper-slide">
                <div class="media text-muted pt-3">
                  <img class="rounded-circle mr-3" src="../static/users/user4.jpg" alt="Generic placeholder image" width="50" height="50">
                  <p class="media-body pb-3 mb-0  lh-125 border-gray text-left">
                    <strong class="d-block text-gray-dark">@Carol</strong>
                    使用上很流暢~
                  </p>
                </div>
              </div>
              <div class="swiper-slide">
                <div class="media text-muted pt-3">
                  <img class="rounded-circle mr-3" src="../static/users/user6.jpg" alt="Generic placeholder image" width="50" height="50">
                  <p class="media-body pb-3 mb-0  lh-125 border-gray text-left">
                    <strong class="d-block text-gray-dark">@Jennifer</strong>
                    很不錯!! 推推
                  </p>
                </div>
              </div>
              <div class="swiper-slide">
                <div class="media text-muted pt-3">
                  <img class="rounded-circle mr-3" src="../static/users/user8.jpg" alt="Generic placeholder image" width="50" height="50">
                  <p class="media-body pb-3 mb-0  lh-125 border-gray text-left">
                    <strong class="d-block text-gray-dark">@Robert</strong>
                    CP值很高! 真心推薦!!
                  </p>
                </div>
              </div>
              <div class="swiper-slide">
                <div class="media text-muted pt-3">
                  <img class="rounded-circle mr-3" src="../static/users/user10.jpg" alt="Generic placeholder image" width="50" height="50">
                  <p class="media-body pb-3 mb-0  lh-125 border-gray text-left">
                    <strong class="d-block text-gray-dark">@Mike</strong>
                    客服很即時~
                  </p>
                </div>
              </div>
              <div class="swiper-slide">
                <div class="media text-muted pt-3">
                  <img class="rounded-circle mr-3" src="../static/users/user12.jpg" alt="Generic placeholder image" width="50" height="50">
                  <p class="media-body pb-3 mb-0  lh-125 border-gray text-left">
                    <strong class="d-block text-gray-dark">@Bob</strong>
                    將好吃、好玩、好康、好用的好康通通送給Fine友，讓出國上網也可以很悠閒自在又環保。
                  </p>
                </div>
              </div>
              <div class="swiper-slide">
                <div class="media text-muted pt-3">
                  <img class="rounded-circle mr-3" src="../static/users/user14.jpg" alt="Generic placeholder image" width="50" height="50">
                  <p class="media-body pb-3 mb-0  lh-125 border-gray text-left">
                    <strong class="d-block text-gray-dark">@Dora</strong>
                    操作相當簡單,出國必備
                  </p>
                </div>
              </div>
              <div class="swiper-slide">
                <div class="media text-muted pt-3">
                  <img class="rounded-circle mr-3" src="../static/users/user16.jpg" alt="Generic placeholder image" width="50" height="50">
                  <p class="media-body pb-3 mb-0  lh-125 border-gray text-left">
                    <strong class="d-block text-gray-dark">@Tammy</strong>
                    還好有Fine全球行動上網夠給力，一個人的旅遊只差一根小米自拍棒就完美了。
                  </p>
                </div>
              </div>
              <div class="swiper-slide">
                <div class="media text-muted pt-3">
                  <img class="rounded-circle mr-3" src="../static/users/user17.jpg" alt="Generic placeholder image" width="50" height="50">
                  <p class="media-body pb-3 mb-0  lh-125 border-gray text-left">
                    <strong class="d-block text-gray-dark">@Linda</strong>
                    體驗很不錯 給個讚
                  </p>
                </div>
              </div>
              <div class="swiper-slide">
                <div class="media text-muted pt-3">
                  <img class="rounded-circle mr-3" src="../static/users/user19.jpg" alt="Generic placeholder image" width="50" height="50">
                  <p class="media-body pb-3 mb-0  lh-125 border-gray text-left">
                    <strong class="d-block text-gray-dark">@Charles</strong>
                    把在國內上網的習慣帶到出國，即使沿途風景明媚，旅客往往在手機拍照後，立即打卡上傳照片到社群網站
                  </p>
                </div>
              </div>
              <div class="swiper-slide">
                <div class="media text-muted pt-3">
                  <img class="rounded-circle mr-3" src="../static/users/user20.jpg" alt="Generic placeholder image" width="50" height="50">
                  <p class="media-body pb-3 mb-0  lh-125 border-gray text-left">
                    <strong class="d-block text-gray-dark">@Sam</strong>
                    充分體驗旅行的美好與記錄
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="py-5">
      <div class="container-fluid text-center">
        <h3 class="text-center mb-3"><i class="fab fa-hotjar text-danger"></i> 熱門套餐 <i class="fab fa-hotjar text-danger"></i></h3>
        <div class="row">
            <div class="col-md-3">
              <div class="card mb-4 box-shadow">
                <img class="card-img-top" style="height: 150px; width: 100%; display: block;" src="../static/wifi.svg" >
                <div class="card-body">
                  <h4>東北亞日韓4G上網</h4>
                  <ul class="list-unstyled mt-2 mb-2">
                    <li class="bg-danger text-white">不限速</li>
                    <li>分享多台上網趣</li>
                    <li>超大電池容量續航力強</li>
                    <li>支援外接4G SIM卡</li>
                  </ul>
                  <h2 class="card-title pricing-card-title">$199 <small class="text-muted">/ day</small></h2>
                  <button type="button" class="btn btn-lg btn-block btn-outline-primary">立即預約</button>
                </div>
              </div>
            </div>
            <div class="col-md-3">
              <div class="card mb-4 box-shadow">
                <img class="card-img-top" style="height: 150px; width: 100%; display: block;" src="../static/wifi2.svg" >
                <div class="card-body">
                  <h4>東南亞星馬泰菲4G上網</h4>
                  <ul class="list-unstyled mt-2 mb-2">
                    <li class="bg-danger text-white">每日1GB後降速，隔天恢復</li>
                    <li>分享多台上網趣</li>
                    <li>超大電池容量續航力強</li>
                    <li>支援外接4G SIM卡</li>
                  </ul>
                  <h2 class="card-title pricing-card-title">$199 <small class="text-muted">/ day</small></h2>
                  <button type="button" class="btn btn-lg btn-block btn-outline-primary">立即預約</button>
                </div>
              </div>
            </div>
            <div class="col-md-3">
              <div class="card mb-4 box-shadow">
                <img class="card-img-top" style="height: 150px; width: 100%; display: block;" src="../static/wifi3.svg" >
                <div class="card-body">
                  <h4>大洋紐澳4G上網</h4>
                  <ul class="list-unstyled mt-2 mb-2">
                    <li class="bg-danger text-white">每日1GB後降速，隔天恢復</li>
                    <li>分享多台上網趣</li>
                    <li>超大電池容量續航力強</li>
                    <li>支援外接4G SIM卡</li>
                  </ul>
                  <h2 class="card-title pricing-card-title">$199 <small class="text-muted">/ day</small></h2>
                  <button type="button" class="btn btn-lg btn-block btn-outline-primary">立即預約</button>
                </div>
              </div>
            </div>
            <div class="col-md-3">
              <div class="card mb-4 box-shadow">
                <img class="card-img-top" style="height: 150px; width: 100%; display: block;" src="../static/wifi4.svg" >
                <div class="card-body">
                  <h4>中國-可翻牆-4G上網</h4>
                  <ul class="list-unstyled mt-2 mb-2">
                    <li class="bg-danger text-white">每日1GB後降速，隔天恢復</li>
                    <li>分享多台上網趣</li>
                    <li>超大電池容量續航力強</li>
                    <li>支援外接4G SIM卡</li>
                  </ul>
                  <h2 class="card-title pricing-card-title">$299 <small class="text-muted">/ day</small></h2>
                  <button type="button" class="btn btn-lg btn-block btn-outline-primary">立即預約</button>
                </div>
              </div>
            </div>
          </div>
          <button class="btn btn-primary btn-lg">到Fine商城看看其他優惠套餐</button>
      </div>
    </div>
    <div class="d-md-flex flex-md-equal w-100 my-md-3 pl-md-3">
      <div class="mr-md-3 pt-3 px-3 pt-md-5 px-md-5 text-center text-white overflow-hidden" style="background:#4267b2">
        <div class="my-3 py-3">
          <h2 class="display-5">粉絲頁按讚 - Fine全球行動上網</h2>
          <p class="lead">活動優惠不錯過</p>
        </div>
        <div class="bg-light box-shadow mx-auto p-3" style="width: 80%; height: 300px; border-radius: 21px 21px 0 0;">
          <img src="../static/facebook.png" width="55%">
        </div>
      </div>
      <div class="mr-md-3 pt-3 px-3 pt-md-5 px-md-5 text-center text-white overflow-hidden" style="background:#00b900">
        <div class="my-3 p-3">
          <h2 class="display-5">加入Line好友@finewifi</h2>
          <p class="lead">掃描下方QR CODE 線上客服 即時回答</p>
        </div>
        <div class="bg-light box-shadow mx-auto p-3" style="width: 80%; height: 300px; border-radius: 21px 21px 0 0;">
          <img src="../static/lineqr.png" width="60%">
        </div>
      </div>
    </div>
    <div class="bg-light py-5">
      <div class="container">
        <h3 class="text-center mb-3">合作夥伴</h3>
        <carousel :perPage="4" :paginationPadding="5">
          <slide class="px-1"><img src="../static/startravel.png" width="100%"></slide>
          <slide class="px-1"><img src="../static/tsuse.png" width="100%"></slide>
          <slide class="px-1"><img src="../static/mafi.png" width="100%"></slide>
          <slide class="px-1"><img src="../static/hipo.png" width="100%"></slide>
          <slide class="px-1"><img src="../static/wanzuo.png" width="100%"></slide>
        </carousel>
      </div>
    </div>

  </div>
</template>

<script>
import Vue from 'vue'
if (process.browser) {
  const VueAwesomeSwiper = require('vue-awesome-swiper/dist/ssr')
  Vue.use(VueAwesomeSwiper)
}
import { Carousel, Slide } from "vue-carousel";
export default {
  layout:'default',
  data () {
      return {
        swiperOption: {
          autoplay:true,
          loop:true,
          height: 460,
          direction: 'vertical',
          slidesPerView: '5',
        }
      }
    },
  components: {
    Carousel,
    Slide
  }
};
</script>


