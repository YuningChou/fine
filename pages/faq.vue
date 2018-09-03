<template>
    <div class="container my-md-3 pl-md-3">
      <div class="d-flex justify-content-between">
        <h2 class="mb-0 d-block text-primary"><i class="fas fa-question-circle"></i> FAQ</h2>
        <h3 class="mb-0 mt-1 font-italic font-weight-bold text-success d-block">客服專線 : 02-82211828 <i class="fas fa-phone"></i></h3>
      </div>
      <hr>
      <ul class="nav nav-pills nav-justified" id="myTab" role="tablist">
        <li class="nav-item">
          <a class="nav-link active h5" id="faq1-tab" data-toggle="tab" href="#faq1" role="tab" aria-controls="faq1" aria-selected="true">常見問題</a>
        </li>
        <li class="nav-item">
          <a class="nav-link h5" id="faq2-tab" data-toggle="tab" href="#faq2" role="tab" aria-controls="faq2" aria-selected="false">設備問題</a>
        </li>
        <li class="nav-item">
          <a class="nav-link h5" id="faq3-tab" data-toggle="tab" href="#faq3" role="tab" aria-controls="faq3" aria-selected="false">歸還問題</a>
        </li>
      </ul>
      <div class="tab-content pb-5" id="myTabContent">
        <div class="tab-pane fade show active" id="faq1" role="tabpanel" aria-labelledby="faq1-tab">
          <div id="accordion1">
            <div class="card">
              <div class="card-header px-0" id="heading1">
                <h5 class="mx-3 py-1 mb-0  h6 collapsed" data-toggle="collapse" data-target="#acollapse1" aria-expanded="true" aria-controls="acollapse1">
                  <i class="fab fa-quora text-primary"></i> 如果取消訂單的話，會產生其他費用嗎?
                </h5>
              </div>
              <div id="acollapse1" class="collapse show" aria-labelledby="heading1" data-parent="#accordion1">
                <div class="card-body">
                  租賃設備者取消租借情況﹕
                  <ol>
                    <li>物流出貨『前』(出國前4個工作天)﹕退回全額租金不會收取任何費用。請進線客服確認(02-8221-1828)。</li>
                    <li>物流出貨『後』(基本為出國前1天，仍以實際寄出時間為主)﹕酌收租金50 %及來回運費，其餘退回。請進線客服確認(02-8221-1828)。</li>
                    <li>變更國別﹕請於出國前3個工作天, 進線客服確認(02-8221-1828)。</li>
                    <li>變更旅遊期間﹕請於出國前3個工作天, 進線客服確認(8221-1828)。</li>
                    <li>非個人因素(如.班機遲延、遇天災…等)﹕請檢附相關證明(如航空公司開立的班機延誤/取消證明)，經本公司審核許可者，得免計取消費用。</li>
                    <li>因個人因素無法取貨﹕租金費用照常計算，無法退費。</li>
                    <li>因我方因素無法到貨(如.天災所致物流無配送等…特殊情況所致無法到貨)﹕租借的租金全額退費。(不可要求額外賠償其他損失)。</li>
                  </ol>
                  自購設備者取消租借情況﹕
                  <ol>
                    <li>變更國別﹕請於出國前3個工作天,進線客服確認(02-8221-1828)，如已於旅程中請以Line與客服聯繫確認。</li>
                    <li>變更旅遊期間﹕請於出國前3個工作天, 進線客服確認(02-8221-1828)，如已於旅程中請以Line與客服聯繫確認。</li>
                    <li>非個人因素(如.班機遲延、遇天災…等)﹕請檢附相關證明(如航空公司開立的班機延誤/取消證明)，經本公司審核許可者，得免計取消費用。</li>
                    <li>因我方因素無法到貨(如.天災所致物流無配送等…特殊情況所致無法到貨)﹕租借的租金全額退費。(不可要求額外賠償其他損失)。</li>
                  </ol>
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading2">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#acollapse2" aria-expanded="true" aria-controls="acollapse2">
                  <i class="fab fa-quora text-primary"></i> 我已經完成線上預約，請問我要怎麼知道我有沒有預約成功呢?
                </h5>
              </div>
              <div id="acollapse2" class="collapse" aria-labelledby="heading2" data-parent="#accordion1">
                <div class="card-body">
                  如果您已預約成功的話，本公司系統將會自動寄出預約確認信到您的電子信箱內。<br>【提醒】Yahoo、Hotmail、pchome等免費信箱可能會在信箱垃圾桶內。
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading3">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#acollapse3" aria-expanded="true" aria-controls="acollapse3">
                  <i class="fab fa-quora text-primary"></i> 我要如何查詢宅配什麼時候會到?
                </h5>
              </div>
              <div id="acollapse3" class="collapse" aria-labelledby="heading3" data-parent="#accordion1">
                <div class="card-body">
                  設備預計於出國日前一天中午以前會送達，若有問題請撥客服專線(02)8221-1828，提供您的大名及訂單編號，將由專員為您查詢宅配運送進度。
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading4">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#acollapse4" aria-expanded="true" aria-controls="acollapse4">
                  <i class="fab fa-quora text-primary"></i> 我選擇超商取機，我什麼時候才能去拿? 會通知我嗎？
                </h5>
              </div>
              <div id="acollapse4" class="collapse" aria-labelledby="heading4" data-parent="#accordion1">
                <div class="card-body">
                  取件方式若選擇超商取機，則會在出國日前一天收到取機提醒的簡訊，當日中午過後就可至指定超商領取包裹，記得攜帶收件人的身分證件喔！若未收到簡訊者請撥客服專線(02) 8221-1828將由專員為您查詢宅配運送進度。
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading5">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#acollapse5" aria-expanded="true" aria-controls="acollapse5">
                  <i class="fab fa-quora text-primary"></i> 請問信用卡資料是否會被存取?
                </h5>
              </div>
              <div id="acollapse5" class="collapse" aria-labelledby="heading5" data-parent="#accordion1">
                <div class="card-body">
                  Fine並不會存取顧客的信用卡資料(卡號、卡名、有效期限、安全密碼，因此每次申請時都必須重新輸入信用卡資料。
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading6">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#acollapse6" aria-expanded="true" aria-controls="acollapse6">
                  <i class="fab fa-quora text-primary"></i> 請問個人資料如何處理?
                </h5>
              </div>
              <div id="acollapse6" class="collapse" aria-labelledby="heading6" data-parent="#accordion1">
                <div class="card-body">
                  依據個資保護法等相關法令，我們已採取符合法規要求的防護措施，以保護您個人資料的安全。若要了解更多資料，請確認您的隱私政策。
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading7">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#acollapse7" aria-expanded="true" aria-controls="acollapse7">
                  <i class="fab fa-quora text-primary"></i> 為什麼使用超過30天以上必須要電話洽詢呢?
                </h5>
              </div>
              <div id="acollapse7" class="collapse" aria-labelledby="heading7" data-parent="#accordion1">
                <div class="card-body">
                  因旅行超過30天以上須要先幫您確認庫存狀況，所以請先來電客服專線(02) 8221-1828洽詢。
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading8">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#acollapse8" aria-expanded="true" aria-controls="acollapse8">
                  <i class="fab fa-quora text-primary"></i> 請問我的旅行目的地是否收得到訊號?
                </h5>
              </div>
              <div id="acollapse8" class="collapse" aria-labelledby="heading8" data-parent="#accordion1">
                <div class="card-body">
                  旅行目的地訊號的相關問題，訂購前可先與客服專線洽詢。(而實際的使用狀況、設備速度及連線品質將視當地電信商營運狀況為主。)
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading9">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#acollapse9" aria-expanded="true" aria-controls="acollapse9">
                  <i class="fab fa-quora text-primary"></i> 我在外島，是否可使用宅配或超商呢？
                </h5>
              </div>
              <div id="acollapse9" class="collapse" aria-labelledby="heading9" data-parent="#accordion1">
                <div class="card-body">
                  因行動上網分享器內含鋰電池，無法以空運寄到外島，目前僅提供本島宅配地址，造成不便敬請見諒，謝謝！
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading10">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#acollapse10" aria-expanded="true" aria-controls="acollapse10">
                  <i class="fab fa-quora text-primary"></i> 租用設備及頻寬付款方式有哪些？
                </h5>
              </div>
              <div id="acollapse10" class="collapse" aria-labelledby="heading10" data-parent="#accordion1">
                <div class="card-body">
                  目前提供：信用卡(一次付清)、網路ATM 、 實體ATM、超商代碼繳費等多種付款方式提供選擇呦。
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading11">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#acollapse11" aria-expanded="true" aria-controls="acollapse11">
                  <i class="fab fa-quora text-primary"></i> 我確認出國期間後，最晚需要在幾天前線上預約呢？
                </h5>
              </div>
              <div id="acollapse11" class="collapse" aria-labelledby="heading11" data-parent="#accordion1">
                <div class="card-body">
                  因Fine設備皆委外給物流公司管理及配送，故最晚需在您出國日五天前做好訂購及付款的動作呦。
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading12">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#acollapse12" aria-expanded="true" aria-controls="acollapse12">
                  <i class="fab fa-quora text-primary"></i> 設備使用過程故障損壞維修需要付費嗎？
                </h5>
              </div>
              <div id="acollapse12" class="collapse" aria-labelledby="heading12" data-parent="#accordion1">
                <div class="card-body">
                  設備已購買：超過保固期或保固期間產生的故障，可聯繫原廠Fine判定維修狀況後，所需檢修費用將由廠商報價後通知消費者，購買之消費者決定是否繼續維修。<br>單純設備租賃：租賃期間設備故障或損壞，經原廠Fine判定人為關係造成後，再向租賃消費者進行費用索償。
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading13">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#acollapse13" aria-expanded="true" aria-controls="acollapse13">
                  <i class="fab fa-quora text-primary"></i>如果在國外遇到問題可以向誰求助呢？
                </h5>
              </div>
              <div id="acollapse13" class="collapse" aria-labelledby="heading13" data-parent="#accordion1">
                <div class="card-body">
                  請聯繫Fine線上客服：
                  <ul>
                    <li>官方Line@懋雲科技</li>
                    <li>官方FB客服:@FineMifi</li>
                    <li>客服信箱:service@hurraycloud.com</li>
                    <li>客服專線:02- 8221-1828(國外請撥(+)886-2- 8221-1828)</li>
                  </ul>
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading14">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#acollapse14" aria-expanded="true" aria-controls="acollapse14">
                  <i class="fab fa-quora text-primary"></i> 押金什麼時候會退給我？
                </h5>
              </div>
              <div id="acollapse14" class="collapse" aria-labelledby="heading14" data-parent="#accordion1">
                <div class="card-body">
                  租賃設備需要押金2500元，若是當月為1-15日歸還設備者，押金將於次月5日退還；若當月為16-31日歸還設備者，押金將於次月25日退還。
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading15">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="acollapse" data-target="#collapse15" aria-expanded="true" aria-controls="acollapse15">
                  <i class="fab fa-quora text-primary"></i> 如果我在國外想增加旅遊使用天數該怎麼進行延長加租呢?
                </h5>
              </div>
              <div id="acollapse15" class="collapse" aria-labelledby="heading15" data-parent="#accordion1">
                <div class="card-body">
                  若是持有買F1分享器者可直接透過官網輸入設備序號後填寫訂單進行加租的服務，而租借設備/網路一般用戶者則請先與客服人員聯繫確認是否可以延長使用時間。
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="tab-pane fade" id="faq2" role="tabpanel" aria-labelledby="faq2-tab">
          <div id="accordion2">
            <div class="card">
              <div class="card-header px-0" id="heading1">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#bcollapse1" aria-expanded="true" aria-controls="bcollapse1">
                  <i class="fab fa-quora text-primary"></i> 我的手機不是4G的，也可以租賃分享器嗎？
                </h5>
              </div>
              <div id="bcollapse1" class="collapse show" aria-labelledby="heading1" data-parent="#accordion2">
                <div class="card-body">
                  本司設備是使用WiFi做連結所以只要是可連結WiFi之3C產品則都可以使用呦。
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading2">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#bcollapse2" aria-expanded="true" aria-controls="bcollapse2">
                  <i class="fab fa-quora text-primary"></i> 請問會有附使用說明書嗎?
                </h5>
              </div>
              <div id="bcollapse2" class="collapse" aria-labelledby="heading2" data-parent="#accordion2">
                <div class="card-body">
                  有喔，每台設備套裡皆會附上使用說明及狀況排除說明等資訊，若在國外有任何問題，也可以聯繫客服。
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading3">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#bcollapse3" aria-expanded="true" aria-controls="bcollapse3">
                  <i class="fab fa-quora text-primary"></i> 為何剛開機的時候機器螢幕有顯示，後來螢幕就沒有顯示了？
                </h5>
              </div>
              <div id="bcollapse3" class="collapse" aria-labelledby="heading3" data-parent="#accordion2">
                <div class="card-body">
                  剛開機時螢幕會顯示開機內容，後來螢幕沒有顯示是因為機器啟動省電設置，可以節省電力不必要的消耗。只要再按一次電源鍵，螢幕就會恢復正常顯示。
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading4">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#bcollapse4" aria-expanded="true" aria-controls="bcollapse4">
                  <i class="fab fa-quora text-primary"></i> 如果自己有SIM卡可以裝在F1分享器裡使用嗎?
                </h5>
              </div>
              <div id="bcollapse4" class="collapse" aria-labelledby="heading4" data-parent="#accordion2">
                <div class="card-body">
                  若是自行準備各國SIM卡的使用者，F1分享器也提供Nano SIM卡插槽，可使用自己的SIM卡上網。<br>
                  ■備註：務必確認在使用Fine的國際數據服務時，必須移除插在SIM卡座上的SIM卡，否則會以實體插入的SIM卡進行電信網路連線。
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading5">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#bcollapse5" aria-expanded="true" aria-controls="bcollapse5">
                  <i class="fab fa-quora text-primary"></i> 100MB大約能提供多少數據用量呢?
                </h5>
              </div>
              <div id="bcollapse5" class="collapse" aria-labelledby="heading5" data-parent="#accordion2">
                <div class="card-body">
                  以下為各約100MB的數據用量：
                  <ol>
                    <li>純文字E-mail（300字)　約200筆</li>
                    <li>圖片E-mail（500KB)　約200筆</li>
                    <li>Skype 語音通話　約50分鐘</li>
                    <li>Skype 視訊　約20分鐘</li>
                    <li>WEB瀏覽　約400頁</li>
                  </ol>
                    [例如]Google首頁･･･約0.02MB<br>
                    Yahoo首頁･･･約0.2MB<br>
                    ※依據網頁瀏覽的容量不同資料量亦不同。
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading6">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#bcollapse6" aria-expanded="true" aria-controls="bcollapse6">
                  <i class="fab fa-quora text-primary"></i> 一台設備可以分享給多少人使用呢?設備大小約多少?
                </h5>
              </div>
              <div id="bcollapse6" class="collapse" aria-labelledby="heading6" data-parent="#accordion2">
                <div class="card-body">
                  F1分享器最多可同時分享五台行動裝置，設備尺寸約：123 mm x 65.6 mm x 17 mm (約iPhone5大小，方便攜帶)。
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading7">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#bcollapse7" aria-expanded="true" aria-controls="bcollapse7">
                 <i class="fab fa-quora text-primary"></i> F1分享器除了當行動上網分享器外還有什麼其他功能嗎?
                </h5>
              </div>
              <div id="bcollapse7" class="collapse" aria-labelledby="heading7" data-parent="#accordion2">
                <div class="card-body">
                  F1分享器還有許多附加功能提供高品質服務：
                  <ol>
                    <li>5000mAh行動電源(手機續航超過18小時)</li>
                    <li>客製化行動APP</li>
                  </ol>
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading8">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#bcollapse8" aria-expanded="true" aria-controls="bcollapse8">
                  <i class="fab fa-quora text-primary"></i> F1租借分享器一旦遺失或損壞相關設備配件該如何賠償?
                </h5>
              </div>
              <div id="bcollapse8" class="collapse" aria-labelledby="heading8" data-parent="#accordion2">
                <div class="card-body">
                  請善盡保管人責任，若租借設備遺失、遭竊或損壞之賠償價目如下(以下皆為新台幣)：
                  <ul>
                    <li>1.行動分享器空機3990元 </li>
                    <li>2.SIM卡遺失或拆開2500元 </li>
                    <li>3.旅行包300元 </li>
                    <li>4.充電器500元 </li>
                    <li>5.Micro USB線100元。</li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="tab-pane fade" id="faq3" role="tabpanel" aria-labelledby="faq3-tab">
          <div id="accordion3">
            <div class="card">
              <div class="card-header px-0" id="heading1">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#ccollapse1" aria-expanded="true" aria-controls="ccollapse1">
                  <i class="fab fa-quora text-primary"></i> 如果在預計歸還日未歸還機器，費用該如何計算?
                </h5>
              </div>
              <div id="ccollapse1" class="collapse show" aria-labelledby="heading1" data-parent="#accordion3">
                <div class="card-body">
                  超商回郵需在回國日隔天將設備放入包裹內所含的回郵包裝，送至全省7-11門市據點，以郵戳蓋印日期為準，若郵戳日期晚於合約結束日，將以逾期計算，逾期罰金將從逾期日開始繼續計算至歸還為止，逾期費用為設備租金一天$該次每日訂價租金 (不適用折扣價)扣至收到設備當日止，以天為單位，扣到押金扣完為止。如有不可歸責於申請人之事由，導致逾期歸還者(如班機遲延、遇天災等)，申請人應檢附相關證明向本公司說明，經本公司審核許可者，得免計逾期罰金。
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-header px-0" id="heading2">
                <h5 class="mx-3 py-1 mb-0   h6 collapsed" data-toggle="collapse" data-target="#ccollapse2" aria-expanded="true" aria-controls="ccollapse2">
                  <i class="fab fa-quora text-primary"></i> 歸還時間與方式？
                </h5>
              </div>
              <div id="ccollapse2" class="collapse" aria-labelledby="heading2" data-parent="#accordion3">
                <div class="card-body">
                   歸還設備方式為：回國日隔天將設備放入包裹內所含的回郵包裝，送至全省7-11門市據點，最晚請於回國日隔天下午5點前送件。
                   <ul>
                    <li>貼心小提醒： 若回國日算起3日內未歸還設備，本公司將收取逾期款項; 若將包裹變更為當日配送，亦將酌收增加運送費用。</li>
                    <li>超商回郵歸還地址：新北市新店區寶宏路11號 國陽物流 收</li>
                   </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  layout:'default',

};
</script>


