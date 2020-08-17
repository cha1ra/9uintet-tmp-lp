<template>
  <v-row>
    <v-col cols="12">
      <v-card class="pa-3">
        <v-row align="center" justify="center">
          <v-col cols="12">
            <div class="text-center mb-8">
              <span class="marker display-1">
                Information
              </span>
            </div>
            <p class="text-center mb-0">
              <span class="d-inline-block">
                <span class="title">株式会社ProgLearn</span>
                は
              </span>
              <span class="d-inline-block">
                2020年8月から
              </span>
              <span class="d-inline-block">
                <span class="title">quintet株式会社</span>
                になります
              </span>
            </p>
          </v-col>
          <v-col cols="11">
            <v-card class="px-3 py-12 elevation-0" color="grey lighten-5">
              <v-row no-gutters align="center" justify="center">
                <v-col cols="12" sm="4">
                  <div class="text-center pb-0 pb-sm-2">
                    <v-chip color="grey lighten-5" small>
                      旧会社名
                    </v-chip>
                  </div>
                  <div class="text-center">
                    <img
                      src="/logo.png"
                      style="width:100%; max-width: 200px"
                    >
                  </div>
                </v-col>
                <v-col cols="12" sm="1" class="text-center py-2">
                  <span class="d-none d-sm-inline">▶︎</span>
                  <span class="d-inline d-sm-none">▼</span>
                </v-col>
                <v-col cols="12" sm="4" class="text-center">
                  <div class="text-center pb-0 pb-sm-2">
                    <v-chip class="font-weight-black" color="cyan lighten-1" small dark>
                      新会社名
                    </v-chip>
                  </div>
                  <div style="color:#ffa000">
                    <span class="display-1 d-block d-sm-none font-weight-bold">quintet<span class="subtitle-1 font-weight-bold">(株)</span></span>
                    <span class="h6 text-sm-h5 text-md-h5 font-weight-bold d-none d-sm-inline">quintet株式会社</span>
                  </div>
                </v-col>
              </v-row>
            </v-card>
          </v-col>
          <v-col cols="11">
            <p class="text-center title font-weight-bold mt-8">
              ＼新サイト作成中／
            </p>
            <p class="text-left text-sm-center">
              <span class="d-inline-block">
                現在新コーポレートサイトを鋭意作成中です。
              </span>
              <span class="d-inline-block">
                <span class="d-inline-block">弊社事業内容・会社概要についてはお手数ですが</span>
                <span class="d-inline-block">株式会社ProgLearnコーポレートサイトをご参照ください。</span>
              </span>
            </p>
            <div class="text-center">
              <v-btn
                dark
                rounded
                color="amber darken-2"
                class="elevation-0 font-weight-bold mb-8"
                href="https://corp.proglearn.com"
              >
                旧サイトページ
              </v-btn>
            </div>
          </v-col>
          <v-col cols="11">
            <v-card
              class="elevation-0 pa-2 sentence"
            >
              <p class="d-inline d-md-block">
                プログラムには無限の可能性がある。プログラムを通じて、世の中をパッと明るくしたい。
              </p>
              <p class="d-inline d-md-block">
                そんな想いから私たちは株式会社ProgLearnを設立しました。お陰様で様々な業界の皆様とお取引を行っています。
              </p>
              <p class="white--text">
                .
              </p>
              <p class="d-inline d-md-block">
                そしてお取引を通じ、我々が果たすべき役割はプログラムコードの実装に留まっていては実現できないと考えるようになりました。
              </p>
              <p class="d-inline d-md-block">
                プログラミングはあくまでも手段です。サービスのアイディア実現という"目的"と組み合わせることで初めて力を発揮します。
              </p>
              <p class="d-inline d-md-block">
                プログラムという手段を提供しつつ、アイディアから開発まで一気通貫で行う。これが弊社の強みであり、体現すべき姿です。
              </p>
              <p class="d-block d-md-none white--text">
                .
              </p>
              <p>そこで我々の社会的位置づけを明確にすべく、会社名を株式会社ProgLearnからquintet株式会社へと変更いたしました。</p>
              <p class="white--text">
                .
              </p>
              <p class="d-inline d-md-block">
                inspiration, insight, innovation, influence, そして infinity。 5つの"in"を柱に満足度を生み出し続ける企業となるべく邁進いたします。
              </p>
              <p class="d-none d-md-block white--text">
                .
              </p>
              <p class="d-inline d-md-block">
                今後とも株式会社ProgLearn改め株式会社quintetを宜しくお願いいたします。
              </p>
              <p class="text-right">
                株式会社quintet 一同
              </p>
            </v-card>
          </v-col>
        </v-row>
      </v-card>
    </v-col>
  </v-row>
</template>
<script>
export default {
  data () {
    return {
      test: 'test'
    }
  }
}
</script>
<style scoped>
.sentence {
  background: linear-gradient(#ccc 1px, transparent 1px);
  background-size: auto 2.5em;
}
.sentence p {
  line-height: 2.5em;
  margin-bottom: 0;
  border-radius: 0px !important;
}
.marker {
  background: linear-gradient(transparent 60%, #FFA000 60%);
}
</style>
