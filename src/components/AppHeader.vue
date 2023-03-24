<script></script>

<template>
  <header>
    <div class="header-logo">
      <img src="/vite.svg" alt="" />
      <span>MYpage</span>
    </div>
  </header>
</template>

<style scoped>
header {
  height: 70px;
  padding: 20px;
  position: fixed;
  width: 100%;
  top: 0;
  left: 0;
  background-color: rgba(0, 0, 0, 0.7);
  z-index: 99;
}

.header-logo {
  height: 100%;
  display: flex;
  align-items: center;
}
.header-logo span {
  color: #fff;
  font-size: 22px;
  margin-left: 10px;
}
</style>
