<template>
  <v-card class="flex-container">
    <v-layout column justify-center align-center>
      <v-card class="text">
        <v-layout justify-center>
          <v-avatar size="80%">
            <a
              href="https://twitter.com/junchann0202"
              target="_blank"
              rel="noopener noreferrer"
            >
              <img
                src="http://hitsusya.com/wp-content/uploads/2020/09/Twitter_Social_Icon_Rounded_Square_Color-2.png"
            /></a>
          </v-avatar>
        </v-layout>

        <v-card-text>
          <h1>twitterやってます</h1>

          <p class="txt-contents">
            2020年の4月と遅まきながら始めました。<br />適当なつぶやきとイベントについてもアナウンスしてます。
          </p>
          <p>
            For more information ,please follow
            <a
              href="https://twitter.com/junchann0202"
              target="_blank"
              rel="noopener noreferrer"
              >my twitter</a
            >.
          </p>
        </v-card-text>
      </v-card>
      <v-card class="timeline">
        <v-flex xs12>
          <Timeline
            :id="user_id"
            sourceType="profile"
            :options="{ tweetLimit: '3' }"
          />
        </v-flex>
      </v-card>
    </v-layout>
  </v-card>
</template>
<script>
import { Timeline } from "vue-tweet-embed";
export default {
  components: {
    Timeline
  },
  data: function() {
    return {
      user_id: "junchann0202"
    };
  }
};
</script>
<style>
img {
  margin: 20px;
}
h1 {
  margin: 20px;
  text-align: center;
}
p {
  margin: 20px;
  text-align: center;
}
.flex-container {
  justify-content: start;
}
</style>
