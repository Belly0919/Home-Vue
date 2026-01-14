<template>
  <div class="ip-card">
    <img src="https://ipinfo.cv/api/ip/card.png?template=default" alt="IP信息卡" />
  </div>
</template>

<style scoped>
.ip-glass {
  margin: 80px auto 20px; 
  padding: 22px 28px;
  border-radius: 22px;
  backdrop-filter: blur(18px) saturate(140%);
  -webkit-backdrop-filter: blur(18px) saturate(140%);
  background: rgba(255,255,255,0.65);
  box-shadow: 0 18px 45px rgba(0,0,0,.12);
  display: inline-flex;
  justify-content: center;
}

.ip-glass img {
  width: 460px; 
  max-width: 88vw;
  border-radius: 16px;
}
</style>
