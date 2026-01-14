<template>
  <div class="ip-card">
    <img src="https://ipinfo.cv/api/ip/card.png?template=compact" alt="IP信息卡" />
  </div>
</template>

<style scoped>
.ip-card {
  margin: 25px auto 10px;
  display: flex;
  justify-content: center;
}

.ip-card img {
  max-width: 380px;
  width: 100%;
  border-radius: 14px;
  box-shadow: 0 10px 30px rgba(0,0,0,.25);
}
</style>
