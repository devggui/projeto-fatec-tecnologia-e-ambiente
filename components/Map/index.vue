<template>
  <div class="container">  
    <div class="map-wrapper">
      <iframe
        src="https://maps.google.com/maps?q=locais%20para%20reciclagem%20de%20lixo%20eletronico%20em%20bauru&t=&z=13&ie=UTF8&iwloc=&output=embed"
        class="responsive-iframe"
        style="border:0;"
        allowfullscreen=""
        loading="lazy"
      />
    </div>
  </div>
</template>

<script>

</script>

<style scoped>
.map-wrapper {
  height: 100vh;
  width: 100%;
}
.responsive-iframe {
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  width: 100%;
  height: 100%;
}

</style>