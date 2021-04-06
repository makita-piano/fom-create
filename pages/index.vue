<template>
  <div class="grid-center">
    <header class="col-12">
      <h1>Fragments of Memories Create</h1>
        <div class="top-img">
        <p class="top-img-txt">
          <span class="top-img-txt-big">記憶</span>
          <span class="top-img-txt-small">の</span>
          <span class="top-img-txt-big">かけら</span><br class="display-none-pc">
          <span class="top-img-txt-small">を</span><span class="top-img-txt-small">かたちに</span>
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
      <div>
      <div id="example" style="padding-top: 1rem">
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
      </div>
        <h2>ご依頼のながれ</h2>
        <div class="grid">
          <div class="grid-center col-12">
            <div class="col-8_sm-12 flow-div">
              <div class="flow-div-div">
                <div class="flow-div-div-div-header">
                  <p class="flow-p">01&nbsp-&nbsp<span class="flow-span">お問い合わせ</span></p>
                </div>
                <div class="flow-div-div-div-contents">
                  <p><span style="text-decoration: underline" @click="witeToClipboard()" id="email">iwamoto@fom-create.com</span><br>こちらのメールアドレスへお気軽にお問い合わせください。</p>
                </div>
              </div>
            </div>
          </div>
          <div class="col-6_sm-12 flow-div">
            <div class="flow-div-div">
              <div class="flow-div-div-div-header">
                <p class="flow-p">02&nbsp-&nbsp<span class="flow-span">内容確認</span></p>
              </div>
              <div class="flow-div-div-div-contents">
                ご希望の日時・場所・内容・納品形態（データのみ、DVD, Blu-Ray）・納期など、お伺いいたします。
              </div>
            </div>
          </div>
          <div class="col-6_sm-12 flow-div">
            <div class="flow-div-div">
              <div class="flow-div-div-div-header">
                <p class="flow-p">03&nbsp-&nbsp<span class="flow-span">お見積り</span></p>
              </div>
              <div class="flow-div-div-div-contents">
                「料金プラン」にそって、お見積りいたします。
              </div>
            </div>
          </div>
          <div class="col-6_sm-12 flow-div">
            <div class="flow-div-div">
              <div class="flow-div-div-div-header">
                <p class="flow-p">04&nbsp-&nbsp<span class="flow-span">契約</span></p>
              </div>
              <div class="flow-div-div-div-contents">
                お見積り内容に問題がなければ契約完了となります。
              </div>
            </div>
          </div>
          <div class="col-6_sm-12 flow-div">
            <div class="flow-div-div">
              <div class="flow-div-div-div-header">
                <p class="flow-p">05&nbsp-&nbsp<span class="flow-span">収録</span></p>
              </div>
              <div class="flow-div-div-div-contents">
                イベント当日、収録にうかがいます。
              </div>
            </div>
          </div>
          <div class="col-6_sm-12 flow-div">
            <div class="flow-div-div">
              <div class="flow-div-div-div-header">
                <p class="flow-p">06&nbsp-&nbsp<span class="flow-span">納品</span></p>
              </div>
              <div class="flow-div-div-div-contents">
                収録後は、適宜やり取りをしながら編集を進め、期日までに納品します。
              </div>
            </div>
          </div>
          <div class="col-6_sm-12 flow-div">
            <div class="flow-div-div">
              <div class="flow-div-div-div-header">
                <p class="flow-p">07&nbsp-&nbsp<span class="flow-span">お支払い</span></p>
              </div>
              <div class="flow-div-div-div-contents">
                納品完了後、代金を所定の口座にお振込みいただきます。
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="grid-center col-12" >
        <h2 class="col-12">料金プラン</h2>
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
          <div class="col-12">
            詳しくは<a href="#example">制作例</a>をクリックください。
          </div>
        </div>
      </div>
      <div class="grid-center col-12" style="margin-bottom: 3rem">
        <h2 class="col-12">プロフィール</h2>
        <fade-in>
          <section>
            <div class="grid-center col-12" style="max-width: 768px">
              <div class="grid col-12">
                <div class="grid col-12" style="margin: auto;text-align: center">
                  <div class="col-12">
                    <img src="~assets/iwamoto.png" width="100%" style="width:8rem;border-radius: 50%;height: 8rem" alt="iwamoto">
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
      <transition name="modal" appear v-if="modal">
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
      </transition>
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
      witeToClipboard() {
        const copyText = this.$el.querySelector('#email').textContent
        if(navigator.clipboard){
          navigator.clipboard
            .writeText(copyText)
            .then(() => {
              swal({
                title: "",
                text: "メールアドレスをコピーしました！",
                icon: "success",
            　});
            })
            .catch(e => {
              console.error(e)
            })
        }
      }
    },
    components: {
      FadeIn
    }
  }
</script>
