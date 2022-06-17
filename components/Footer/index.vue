<template>
  <div class="container">
    <div class="content">
      <img class="logo" src="../../assets/logo.png">
      <div class="content-text">
        <h3>devguiet@gmail.com</h3>
        <h3>(14) 99861-9263</h3>
      </div>
      <div class="info">
        <ul>
          <a href="https://pt-br.facebook.com"><Facebook :size="40" fillColor="#fff"/></a>
          <a href="https://web.whatsapp.com"><Whatsapp :size="40" fillColor="#fff"/></a>
          <a href="https://www.instagram.com"><Instagram :size="40" fillColor="#fff"/></a>        
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
import Facebook from 'vue-material-design-icons/Facebook.vue'
import Whatsapp from 'vue-material-design-icons/Whatsapp.vue'
import Instagram from 'vue-material-design-icons/Instagram.vue'

export default {
  components: {    
    Facebook,
    Whatsapp,
    Instagram
  }
}
</script>

<style lang="scss" scoped>
.container {
  background: #56bdaa;  
}

.content {
  background: #56bdaa;
  width: 100%;
  height: 300px;
  bottom: 0;
  left: 0;
  text-align: center;
  align-items: center;
  justify-content: center;

  > .content-text {
    color: #fff;
    margin-bottom: 20px;    
  }
}

h3 {
  margin-bottom: 7px;
}

.logo {
  height: 10rem;
  cursor: pointer;
}

.info {  
  color: #fff;
  display: flex;
  flex-direction: row; 
  justify-content: center;
}
</style>