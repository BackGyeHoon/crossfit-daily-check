<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <v-card>
        <v-card-title class="headline">
          CROSSFIT DAILY CHECK에 오신 것을 환영 합니다 !
        </v-card-title>
        <v-card-text>
          <p>해당 사이트는 크로스핏을 시작한 크린이가 필요해서 만든 사이트 입니다.</p>
          <p>1. 오늘의 와드 기록</p>
          <p>2. 와드 소요 시간</p>
          <p>3. 이전 기록 비교</p>
          <p>개발자가 만든 사이트이다보니, UI적으로는 최악입니다. 그래도 최대한 불편하지 않도록 구현하겠습니다 !</p>
          <div class="text-xs-right">
            <em><small>&mdash; 제작자 : BackGyehoon</small></em>
          </div>
          <hr class="my-3">
          <a
            href="https://github.com/BackGyeHoon/crossfit-daily-check"
            target="_blank"
            rel="noopener noreferrer"
          >
            제작자 깃헙: BackGyeHoon
          </a>
          <br>
          <a
            href="http://naver.me/FRD9ZlHQ"
            target="_blank"
            rel="noopener noreferrer"
          >
            Crossfit Baegot
          </a>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn
            color="primary"
            nuxt
            to="/inspire"
          >
            Continue
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>
