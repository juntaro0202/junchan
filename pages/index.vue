<template>
  <v-layout column justify-center align-center>
    <v-flex xs12 sm8 md6>
      <div class="text-center">
        <v-container fluid>
          <v-row>
            <v-col cols="6" sm="3">
              <v-img
                src="http://hitsusya.com/wp-content/uploads/2020/09/logo.png"
                gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)"
              ></v-img>
            </v-col>
          </v-row>
        </v-container>
      </div>
      <v-card>
        <v-card-title class="headline"
          >Welcome to じゅんちゃん official site</v-card-title
        >
        <v-card-text>
          <p>本サイトはじゅんちゃんの活動についてまとめているサイトです。</p>
          <p>
            今アクティブに活動しているのはyoutubeです。
            <a
              href="https://www.youtube.com/channel/UCa6oNOr1S251sHs8rile4Rw?view_as=subscriber"
              target="_blank"
              rel="noopener noreferrer"
              >チャンネル登録お願いします</a
            >。
          </p>
          <p>
            twitterも最近勧められてはじめています。
            <a
              href="https://twitter.com/junchann0202"
              target="_blank"
              rel="noopener noreferrer"
              title="chat"
              >フォローするにはこちら</a
            >。
          </p>
          <p>
            月に2~4回ほど読書会イベントも開催してます。
            <a
              href="https://www.read4action.com/"
              target="_blank"
              rel="noopener noreferrer"
              title="contribute"
              >詳細はこちら</a
            >。
          </p>
          <p>
            Thank you for developing with Vuetify and I look forward to bringing
            more exciting features in the future.
          </p>
          <div class="text-xs-right">
            <em>
              <small>&mdash; Junya Kitahata</small>
            </em>
          </div>
          <hr class="my-3" />
          お問い合わせやお仕事の依頼につきましては下記からお願いします。
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" nuxt to="/contact">Contact</v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>
