<template>
  <div class="container my-md-3 pl-md-3">
    <div class="row">
      <div class="col-md-4 d-flex">
        <div class="card mb-4 box-shadow flex-fill">
          <img class="card-img-top" style="width: 100%; height:175px; display: block;" src="https://static.wixstatic.com/media/d65e0f_fb32c9e226f84a62b8b25e4f796fef98~mv2.jpg/v1/fill/w_413,h_250,al_c,q_80,usm_0.66_1.00_0.01/d65e0f_fb32c9e226f84a62b8b25e4f796fef98~mv2.webp">
          <div class="card-body">
            <h5>【20名旅遊美食部落客大募集】 出國跨境行動上網新體驗之旅</h5>
            <p class="card-text">FineMifi全新出國上網體驗，盛情邀請20位部落客參與體驗，只要部落客即將要出國，出國區域是FineMifi涵蓋區，提出申請接觸後，將有專人與您聯繫說明體驗合作機制，及確認是否資格符合，真心期盼您的加入，一起分享美好上網體驗給更多旅人。</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 d-flex">
        <div class="card mb-4 box-shadow flex-fill">
          <div class="card-img-top" style=" width: 100%; display: block;">
            <iframe width="100%" height="175" src="https://www.youtube.com/embed/KwkUqesjEM4" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
          </div>
          <div class="card-body">
            <h5>出國上網那樣划算？　SIM卡、租WiFi機、辦漫遊</h5>
            <p class="card-text">目前人手一支智慧型手機的年代，不管是查地圖、找美食、找景點，或者是拍照打卡傳訊息都很方便。所以這個上網出國的時候，到底用什麼比較划算呢？</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 d-flex">
        <div class="card mb-4 box-shadow flex-fill">
          <img class="card-img-top" style="width: 100%;height:175px; display: block;" src="https://static.wixstatic.com/media/d65e0f_8b26b0deee7f465d96d511793ddfdbb7~mv2.png/v1/fill/w_413,h_250,al_c,q_80,usm_0.66_1.00_0.01/d65e0f_8b26b0deee7f465d96d511793ddfdbb7~mv2.webp">
          <div class="card-body">
            <h5>【資深媒體人Bonnie Tai】 英國倫敦攝政街Regent Street</h5>
            <p class="card-text">對！我是菜英文。但還好有你帶著我逛景點、吃美食。這樣體貼的你，怎人讓人不愛妳...谷哥。還好有Fine全球行動上網夠給力，一個人的旅遊只差一根小米自拍棒就完美了。​倫敦主要的購物街道有三條：攝政街、牛津街、龐德街，攝政街是條寬敞的大馬路，兩旁全是規模很大的商店...</p>
          </div>
        </div>
      </div>

      <div class="col-md-4 d-flex">
        <div class="card mb-4 box-shadow flex-fill">
          <img class="card-img-top" style="width: 100%; height:175px; display: block;" src="https://static.wixstatic.com/media/d65e0f_3366ee023ebf4a77a52e049622d5bda0~mv2.png/v1/fill/w_413,h_250,al_c,q_80,usm_0.66_1.00_0.01/d65e0f_3366ee023ebf4a77a52e049622d5bda0~mv2.webp">
          <div class="card-body">
            <h5>【直播主劉盈盈】 匈牙利地表最美的美術館直擊</h5>
            <p class="card-text">一踏進紐約咖啡，完全讓我震懾住了！超美！金碧輝煌的感覺好像置身在皇宮城堡裡喔！這裡真的是咖啡廳嗎？實在太讓人驚訝了！每個角落都散發出歷史感以及優雅的氣息，來到這裡完全大開眼界！一定要立馬連線台灣分享...</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 d-flex">
        <div class="card mb-4 box-shadow flex-fill">
          <div class="card-img-top" style=" width: 100%; display: block;">
            <iframe width="100%"  height="175" src="https://www.youtube.com/embed/-qayMtUVIkU" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
          </div>
          <div class="card-body">
            <h5>出國應該選上網卡還是分享器?</h5>
            <p class="card-text">想出國卻不知道應該用上網卡還是分享器嗎?2人出遊及4人出遊又應該怎麼挑選咧?</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 d-flex">
        <div class="card mb-4 box-shadow flex-fill">
          <div class="card-img-top" style=" width: 100%; display: block;">
            <iframe width="100%"   height="175" src="https://www.youtube.com/embed/FYtWgmfQNZk" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
          </div>
          <div class="card-body">
            <h5>【朵朵Duoduo】去日本旅遊竟然可以免費上網？！推薦五種上網方式！</h5>
            <p class="card-text">這次的影片是來教大家選擇去日本時的上網方式</p>
          </div>
        </div>
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


