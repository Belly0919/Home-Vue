<template>
  <div class="background"></div>

  <Home />

  <!-- IP 信息卡 -->
  <div class="ip-card">
    <img src="https://ipinfo.cv/api/ip/card.png?template=default" alt="IP信息卡" />
  </div>

  <footer>
    <span>© 2025 Made in <a href="/" target="_blank">{{ userName }}</a></span>
    <a v-if="icpNumber" href="https://beian.miit.gov.cn/" target="_blank">{{ icpNumber }}</a>
    <a v-if="policenumber"
       :href="`https://beian.mps.gov.cn/#/query/webSearch?police=${policenumber}`"
       target="_blank"
       class="police_link">
      <span class="police_img"></span> {{ policenumber }}
    </a>
  </footer>
</template>
