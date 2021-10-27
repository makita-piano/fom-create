<template>
  <div class="grid-center">
    <header class="col-12">
      <h1>Fragments of Memories Create</h1>
        <div class="top-img">
        <p class="top-img-txt">
          <span class="word top-img-txt-big">記</span><span class="word top-img-txt-big">憶</span>
          <span class="word top-img-txt-small">の</span>
          <span class="word top-img-txt-big">か</span><span class="word top-img-txt-big">け</span><span class="word top-img-txt-big">ら</span><br class="display-none-pc">
          <span class="word top-img-txt-small">を</span>
          <span class="word top-img-txt-small">か</span><span class="word top-img-txt-small">た</span><span class="word top-img-txt-small">ち</span><span class="word top-img-txt-small">に</span>
        </p>
        <hr class="top-img-hr display-none-mobile">
      </div>
    </header>

    <div class="grid-center col-12 main-div">
      <div>
        <h2>FoMクリエイトとは</h2>
        <div class="about-div">
          <p>「Fragments of Memories Create」の略。関東を中心に、クラシックの演奏会や発表会、あるいは講演などを収録・編集いたします。ピアノ演奏や作編曲をはじめ、自身も音楽への造詣が深い岩本健吾が「大切な記憶をかたちにしたい」という一心で主宰する事業です。</p>
        </div>
      </div>
      <!--<div id="example" style="padding-top: 1rem">
        <h2>制作例</h2>
        <fade-in>
          <section>
            <div class="grid col-12">
              <div class="grid col-4_sm-12" style="margin-bottom: 2rem;cursor: pointer" @click="openModal">
                <div class="grid col-12" style="position: relative">
                  <img src="~assets/sample.png" width="100%" style="padding: 0 1rem" alt="piano">
                </div>
                <span style="padding-left: 1rem;text-decoration: underline">鴨田音楽教室様</span>
              </div>
              <div class="grid col-4_sm-12" style="margin-bottom: 2rem;cursor: pointer" @click="openModal">
                <img src="~assets/sample.png" width="100%" style="padding: 0 1rem" alt="piano">
                <span style="padding-left: 1rem">あああ様</span>
              </div>
              <div class="grid col-4_sm-12" style="margin-bottom: 2rem;cursor: pointer" @click="openModal">
                <img src="~assets/sample.png" width="100%" style="padding: 0 1rem" alt="piano">
                <span style="padding-left: 1rem">あああ様</span>
              </div>
              <div class="grid col-4_sm-12" style="margin-bottom: 2rem;cursor: pointer" @click="openModal">
                <img src="~assets/sample.png" width="100%" style="padding: 0 1rem" alt="piano">
                <span style="padding-left: 1rem">あああ様</span>
              </div>
            </div>
          </section>
        </fade-in>
      </div>-->
      <div>
        <h2>ご依頼のながれ</h2>
        <fade-in>
          <section>
            <div class="grid">
              <div class="grid-center col-12">
                <div class="col-8_sm-12 flow-div">
                  <div class="flow-div-div">
                    <div class="flow-div-div-div-header">
                      <p class="flow-p">01&nbsp;-&nbsp;<span class="flow-span">お問い合わせ</span></p>
                    </div>
                    <div class="flow-div-div-div-contents">
                      <p><span style="text-decoration: underline">iwamoto@fom-create.com</span><br>こちらのメールアドレスへお気軽にお問い合わせください。</p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-6_sm-12 flow-div">
                <div class="flow-div-div">
                  <div class="flow-div-div-div-header">
                    <p class="flow-p">02&nbsp;-&nbsp;<span class="flow-span">内容確認</span></p>
                  </div>
                  <div class="flow-div-div-div-contents">
                    ご希望の日時・場所・内容・納品形態（データのみ、DVD, Blu-Ray）・納期など、お伺いいたします。
                  </div>
                </div>
              </div>
              <div class="col-6_sm-12 flow-div">
                <div class="flow-div-div">
                  <div class="flow-div-div-div-header">
                    <p class="flow-p">03&nbsp;-&nbsp;<span class="flow-span">お見積り</span></p>
                  </div>
                  <div class="flow-div-div-div-contents">
                    「料金プラン」にそって、お見積りいたします。
                  </div>
                </div>
              </div>
              <div class="col-6_sm-12 flow-div">
                <div class="flow-div-div">
                  <div class="flow-div-div-div-header">
                    <p class="flow-p">04&nbsp;-&nbsp;<span class="flow-span">契約</span></p>
                  </div>
                  <div class="flow-div-div-div-contents">
                    お見積り内容に問題がなければ契約完了となります。
                  </div>
                </div>
              </div>
              <div class="col-6_sm-12 flow-div">
                <div class="flow-div-div">
                  <div class="flow-div-div-div-header">
                    <p class="flow-p">05&nbsp;-&nbsp;<span class="flow-span">収録</span></p>
                  </div>
                  <div class="flow-div-div-div-contents">
                    イベント当日、収録にうかがいます。
                  </div>
                </div>
              </div>
              <div class="col-6_sm-12 flow-div">
                <div class="flow-div-div">
                  <div class="flow-div-div-div-header">
                    <p class="flow-p">06&nbsp;-&nbsp;<span class="flow-span">納品</span></p>
                  </div>
                  <div class="flow-div-div-div-contents">
                    収録後は、適宜やり取りをしながら編集を進め、期日までに納品します。
                  </div>
                </div>
              </div>
              <div class="col-6_sm-12 flow-div">
                <div class="flow-div-div">
                  <div class="flow-div-div-div-header">
                    <p class="flow-p">07&nbsp;-&nbsp;<span class="flow-span">お支払い</span></p>
                  </div>
                  <div class="flow-div-div-div-contents">
                    納品完了後、代金を所定の口座にお振込みいただきます。
                  </div>
                </div>
              </div>
            </div>
          </section>
        </fade-in>
      </div>
      <div class="grid-center col-12">
        <h2 class="col-12">料金プラン</h2>
        <fade-in>
          <section>
            <div class="grid col-12" style="padding: 0 .5rem;max-width: 768px;font-size: 1.2rem">
              <div class="col-12">
                FoMクリエイトでは、
              </div>
              <div class="col-12">
                <p class="price" style="color: #36C190">収録<span style="color: #333">・</span>編集<span style="color: #333">・</span>制作</p>
              </div>
              <div class="col-12">
                という3つの部分ごとに料金を計算しております。
              </div>
              <div class="grid col-12" style="padding: 1rem">
                <div class="grid col-12" style="box-shadow: 0 2px 5px #ccc;border-radius: 5px;">
                  <div class="col-12" style="border-radius: 5px 5px 0 0;background: #CEE8E4;text-align: center">
                    <p style="margin-left: 1rem;font-size: 2rem;line-height: 3rem;"><span style="font-size: 2rem">収録</span></p>
                  </div>
                  <div class="grid col-12" style="padding: 1rem">
                    <div class="col-12">
                      以下の3点より、収録費を算出します。
                    </div>
                    <div class="col-12" style="margin: .5rem 0">
                      ・拘束時間<br>
                      ・交通経費<br>
                      ・機材プラン<br>
                    </div>
                  </div>
                </div>
              </div>
              <div class="grid col-12" style="padding: 1rem">
                <div class="grid col-12" style="box-shadow: 0 2px 5px #ccc;border-radius: 5px;">
                  <div class="col-12" style="border-radius: 5px 5px 0 0;background: #CEE8E4;text-align: center">
                    <p style="margin-left: 1rem;font-size: 2rem;line-height: 3rem;"><span style="font-size: 2rem">編集</span></p>
                  </div>
                  <div class="col-12" style="padding: 1rem">
                    編集を施す部分の総時間（≒演奏時間）に対して、編集費としての料金を計算します。
                  </div>
                </div>
              </div>
              <div class="grid col-12" style="padding: 1rem">
                <div class="grid col-12" style="box-shadow: 0 2px 5px #ccc;border-radius: 5px;">
                  <div class="col-12" style="border-radius: 5px 5px 0 0;background: #CEE8E4;text-align: center">
                    <p style="margin-left: 1rem;font-size: 2rem;line-height: 3rem;"><span style="font-size: 2rem">制作</span></p>
                  </div>
                  <div class="col-12" style="padding: 1rem">
                    納品の形態（データ・DVD・Blu-Ray）により、それぞれの制作費を計算します。
                  </div>
                </div>
              </div>
              <!--<div class="col-12">
                詳しくは<a href="#example">制作例</a>をクリックください。
              </div>-->
            </div>
          </section>
        </fade-in>
      </div>
      <div class="grid-center col-12" style="margin-bottom: 3rem">
        <h2 class="col-12">プロフィール</h2>
        <fade-in>
          <section>
            <div class="grid-center col-12" style="max-width: 768px">
              <div class="grid col-12">
                <div class="grid col-12" style="margin: auto;text-align: center">
                  <div class="col-12">
                    <img src="~assets/profile.jpeg" width="100%" style="width:8rem;border-radius: 50%;height: 8rem" alt="iwamoto">
                  </div>
                  <div class="col-12">岩本　健吾</div>
                </div>
              </div>
              <div style="margin-bottom: 1rem">
                <a href="https://www.facebook.com/kengo.iwamoto.71" target="_blank">
                  <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 28 28" class="svg replaced-svg"><g transform="translate(0 0)"><path d="M-2505-5135a13.906,13.906,0,0,1-9.9-4.1,13.908,13.908,0,0,1-4.1-9.9,13.91,13.91,0,0,1,4.1-9.9,13.907,13.907,0,0,1,9.9-4.1,13.909,13.909,0,0,1,9.9,4.1,13.908,13.908,0,0,1,4.1,9.9,13.906,13.906,0,0,1-4.1,9.9A13.908,13.908,0,0,1-2505-5135Zm-2.073-14.026v8.433h3.178v-8.433h2.6l.5-3.146h-3.106v-.969a1.037,1.037,0,0,1,1-1.115h2.174v-3.212h-2.557v.012a3.859,3.859,0,0,0-3.034,1.195,3.961,3.961,0,0,0-.754,2.485h-.006v1.6h-2.109v3.146Z" transform="translate(2519 5163)" fill="#444"></path></g></svg>
                </a>
              </div>
              <div class="grid col-12" style="padding: 0 .5rem;font-size: 1.2rem">
                東京音楽大学大学院音楽研究科器楽専攻鍵盤楽器研究領域（伴奏）修了。島村楽器ミュージックサロン南行徳ピアノ講師。
                ピアニスト・作編曲家として演奏や教育活動をする傍ら、一般社団法人全日本ピアノ指導者協会（ピティナ）にて2015年より5年間半、ゼロから動画収録・編集の業務に携わる。自身の音楽スキルを存分に活かすことが可能な動画制作への好奇心が溢れ、2020年12月17日に「FoMクリエイト」を起業。国内外で活躍する著名なアーティストの収録も数多くおこなっている。</div>
            </div>
          </section>
        </fade-in>
      </div>
      <!--<transition name="modal" appear v-if="modal">
        <div class="modal modal-overlay" @click="closeModal">
          <div class="modal-window" style="max-height: 90vh">
            <div class="modal-header" style="position: relative">
              鴨田音楽教室様
              <button @click="closeModal" style="position: absolute;right: .7rem;top: .7rem;background: none;border: none;color: #555">×</button>
            </div>
            <div class="modal-content" style="overflow-y: auto;max-height: 80vh;">
              <div class="grid col-12">
                <div class="col-12 youtube-iframe">
                  <div style="position: relative; padding-bottom: 56.25%;">
                    <iframe
                      style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
                      src="https://www.youtube.com/embed/YzUpM0uvlnc"
                      frameborder="0"
                      allow="autoplay;
                      encrypted-media"
                      allowfullscreen>
                    </iframe>
                  </div>
                </div>
                <div class="col-12">
                  <table style="padding: 0 2rem;border-collapse: collapse;width: 100%">
                    <tbody>
                      <tr>
                        <th style="border: 1px solid #000;padding: 1rem;border-collapse: collapse;width: auto">
                          収録代(拘束6時間)
                        </th>
                        <td style="border: 1px solid #000;padding: 1rem;border-collapse: collapse;width: auto;text-align: right">
                          ￥12,000
                        </td>
                      </tr>
                      <tr>
                        <th style="border: 1px solid #000;padding: 1rem;border-collapse: collapse;width: auto">
                          機材プラン(カメラx2 , ステレオx2)
                        </th>
                        <td style="border: 1px solid #000;padding: 1rem;border-collapse: collapse;width: auto;text-align: right">
                          ￥0
                        </td>
                      </tr>
                      <tr>
                        <th style="border: 1px solid #000;padding: 1rem;border-collapse: collapse;width: auto">
                          総編集費用(￥6,000/30分 x 180分)
                        </th>
                        <td style="border: 1px solid #000;padding: 1rem;border-collapse: collapse;width: auto;text-align: right">
                          ￥36,000
                        </td>
                      </tr>
                      <tr>
                        <th style="border: 1px solid #000;padding: 1rem;border-collapse: collapse;width: auto">
                          DVD制作(19セット)
                        </th>
                        <td style="border: 1px solid #000;padding: 1rem;border-collapse: collapse;width: auto;text-align: right">
                          ￥16,720
                        </td>
                      </tr>
                      <tr>
                        <th style="border: 1px solid #000;padding: 1rem;border-collapse: collapse;width: auto">
                          ほか(交通費など)
                        </th>
                        <td style="border: 1px solid #000;padding: 1rem;border-collapse: collapse;width: auto;text-align: right">
                          ￥2,545
                        </td>
                      </tr>
                      <tr>
                        <th style="border: 1px solid #000;padding: 1rem;border-collapse: collapse;width: auto;background-color: #eee">
                          合計料金(税込)
                        </th>
                        <td style="border: 1px solid #000;padding: 1rem;border-collapse: collapse;width: auto;text-align: right;background-color: #eee">
                          ￥67,265
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </div>
              </div>
            </div>
          </div>
        </div>
      </transition>-->
    </div>
  </div>
</template>

<script>
  import FadeIn from '../components/FadeIn'
  import swal from 'sweetalert'

  export default {
    head() {
      return {
        meta: [
          { hid: 'og:url', property: 'og:url', content: 'https://fom-create.com' },
        ],
        link: [
          { rel: 'canonical', href: 'https://fom-create.com' }
        ]
      }
    },
    data() {
      return {
        modal: false
      }
    },
    methods: {
      openModal() {
        this.modal = true
      },
      closeModal() {
        this.modal = false
      },
    },
    components: {
      FadeIn
    }
  }
</script>

<style scoped>
ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

* , *::before , *::after {
  box-sizing: border-box;
  margin: 0;
}

h1 {
  font-family: 'Sofia', cursive;
  font-size: 1rem;
  font-weight: normal;
  padding: 1rem 0;
  text-align: center;
  margin: 0;
}

#content h2 {
  background: #6bb6ff;
  border-bottom: .3rem solid #2281C6;
  color: white;
  margin: 3rem 0 1rem 0;
  padding: .9rem 0 0 .5rem;
}

hr {
  border: none;
}

img {
  border: 0;
  max-width: 100%;
  vertical-align: top;
}

.top-img {
  align-items: center;
  background: url(/_MG_2128.JPG) center top / cover no-repeat;
  display: flex;
  flex-wrap: wrap;
  height: 70vh;
  justify-content: flex-end;
  overflow: hidden;
  position: relative;
  width: 100%;
  z-index: 2;
}
.top-img-txt-big {
  font-size: 3rem;
}
.top-img-txt-small {
  font-size: 2rem;
}
.top-img-hr {
  border-bottom: .2rem solid white;
  bottom: 2.5rem;
  height: 1rem;
  position: absolute;
  right: 40rem;
  width: 19vw;
}

#content .main-div {
  max-width: 768px;
  padding: 0 .5rem;
  background: white;
}

.about-div {
  padding: 0 .5rem;
  font-size: 1.2rem;
  line-height: 2;
}

#content .flow-div {
  padding: 1rem;
}

.flow-div-div {
  box-shadow: 0 .3rem .6rem #ccc;
  border-radius: .5rem;
}

.flow-div-div-div-header {
  border-radius: 5px 5px 0 0;
  background: #CEE8E4;
  text-align: center;
  height: 3rem;
}

.flow-div-div-div-contents {
  padding: 1rem;
  height: 7rem;
}


.flow-p {
  margin-left: 1rem;
  font-size: 2rem;
  line-height: 3rem;
}

.flow-span {
  font-size: 1.2rem;
  vertical-align: 8%;
}

.ul-flow {
  align-items: flex-start;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin: 0 auto;
  width: 900px;
}

.ul-flow > li {
  position: relative;
  width: 250px;
}

.div-flow::before {
  background-color: #FFF;
  bottom: 0;
  content: '';
  height: 3px;
  left: 0;
  position: absolute;
  transition: .5s ease;
  width: 100%;
}

.div-flow {
  margin-bottom: 20px;
  padding-bottom: 20px;
  position: relative;
}

.span-flow {
  display: block;
  letter-spacing: .2rem;
  margin: 0 auto;
  text-align: center;
}

.em-flow {
  display: block;
  font-size: 3rem;
  font-weight: 800;
  line-height: 1.5;
  margin: 0 auto 5px;
  opacity: 1;
  text-align: center;
  transform: translate(0,0);
  transition-delay: .4s;
}

.modal-overlay {
  align-items: center;
  background: rgba(0, 0, 0, .5);
  display: flex;
  height: 100%;
  justify-content: center;
  left: 0;
  padding: 5vh 0;
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 30;
}

.modal-window {
  background: #FFF;
  border-radius: 4px;
  overflow: hidden;
  width: 90%;
  margin: auto;
}

.modal-content {
  padding: .5rem 1rem;
}

.modal-header {
  background: #CEE8E4;
  padding: 10px;
  text-align: left;
}

.modal-enter-active , .modal-leave-active {
  transition: opacity .4s;
}

.modal-enter-active .modal-window {
  transition: opacity .4s, transform .4s;
}

.modal-leave-active .modal-window {
  transition: opacity .4s, transform .4s;
}

.modal-leave-active {
  transition: opacity .6s ease .4s;
}

.modal-enter , .modal-leave-to {
  opacity: 0;
}

.modal-enter .modal-window {
  opacity: 0;
  transform: translateY(-20px);
}

.modal-leave-to .modal-window {
  opacity: 0;
  transform: translateY(-20px);
}

.youtube-iframe {
  margin-bottom: .5rem;
}

.top-img-txt {
  color: white;
  font-family: Shippori Mincho, serif;
  font-weight: 400;
  line-height: 1.5;
  text-align: center;
}

.price {
  font-size: 2rem;
}

@media (max-width: 768px) {
  .top-img-txt {
    margin: auto auto 3rem;
  }

  [class='li-flow']:not(:last-child) {
    margin-bottom: 80px;
  }

  .li-flow {
    margin: 0 auto;
    width: 80%;
  }

  .div-flow {
    margin-bottom: 15px;
    padding-bottom: 15px;
  }

  .span-flow {
    margin: 0 auto;
  }

  .ul-flow {
    display: block;
    margin: 0 auto;
    width: 100%;
  }

  [class='li-flow']:not(:last-child)::after {
    bottom: -2.3em;
    content: '∨';
    font-size: 22px;
    font-weight: bold;
    height: 1em;
    left: 0;
    line-height: 1;
    margin: auto;
    position: absolute;
    right: 0;
    top: auto;
    width: 1em;
  }
}

@media (min-width: 769px) {
  .price {
    font-size: 3rem;
  }
  .top-img-txt {
    padding-right: 2rem;
  }

  .top-img-txt-big {
    font-size: 4rem;
  }

  .top-img-txt-small {
    font-size: 2.5rem;
  }

  .modal-window {
    max-width: 768px;
    width: 100%;
  }

  .modal-content {
    padding: 1rem 3rem;
  }

  h1 {
    letter-spacing: .5rem;
  }

  .youtube-iframe {
    padding: 0 15%;
  }

  [class='li-flow']:not(:last-child) > div::after {
    content: '>';
    font-weight: bold;
    height: 1em;
    line-height: 1;
    margin: auto;
    position: absolute;
    right: -40px;
    top: 100%;
  }
  #content .main-div {
    margin: 3rem 0;
    border-radius: .5rem;
  }
  .top-img {
    align-items: flex-end;
  }
  .about-div {
    font-size: 1.2rem;
  }
  h1 {
    font-size: 1.5rem;

  }
}
.word {
  animation: word 10s infinite ease-in-out;
}
.word:nth-child(1) {
  animation-delay: .1s;
}
.word:nth-child(2) {
  animation-delay: .2s;
}
.word:nth-child(3) {
  animation-delay: .3s;
}
.word:nth-child(4) {
  animation-delay: .4s;
}
.word:nth-child(5) {
  animation-delay: .5s;
}
.word:nth-child(6) {
  animation-delay: .6s;
}
.word:nth-child(7) {
  animation-delay: .7s;
}
.word:nth-child(8) {
  animation-delay: .8s;
}
.word:nth-child(9) {
  animation-delay: .9s;
}
.word:nth-child(10) {
  animation-delay: 1.0s;
}
.word:nth-child(11) {
  animation-delay: 1.1s;
}
.word:nth-child(12) {
  animation-delay: 1.2s;
}
@keyframes word {
  0%, 5%, 30%, 100% { filter: blur(0px); opacity: 1; }        
  15%, 20% { filter: blur(1em); opacity: 0; }        
}
</style>
