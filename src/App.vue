<template>
  <div id="app">
    <router-view />
    <div class="footer">
      <p class="footer-text">Copyright &copy 2021 Designed & Developed by Arunkumar</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>

.footer {
  height: 4%;
  border-top: 1px solid #E9E9E9;
  text-align: center;
  color: #304156;
}

.footer-text {
  padding-bottom: 10px;
  font-weight: bold;
}
</style>
