<template>
  <div class="container">
    <section>
      <div class="content">
        <div class="content-texts">
          <strong>Você sabe o que é Lixo eletrônico ou e-lixo?</strong>
          <b>São produtos elétricos e eletrônicos danificados, quebrados ou sem utilidade por algum motivo que devem ser descartados.</b>           
        </div>
        <img src="../../assets/banner.webp">
      </div>
    </section>
    <section>
      <div class="content">
        <img src="../../assets/descarte.jpg">
        <div class="content-texts">
          <strong>Onde e como descartar?</strong>
          <b>Uma forma simples de ajudar a diminuir esses problemas é não despejar o lixo eletrônico em qualquer lugar. O reaproveitamento de materiais pela reciclagem é capaz de dar um novo destino para os materiais.</b>           
        </div>          
      </div>
    </section>
    <section>
      <div class="content">          
        <div class="content-texts">
          <strong>Descarte aqui!!!</strong>                  
          <b>Clique na lixeira para descobrir os pontos de descartes mais próximos a você.</b>           
        </div>
        <nuxt-link to="/location">
          <div class="img-hover"></div>                  
        </nuxt-link>           
      </div>      
    </section>      
  </div>
</template>

<script>

</script>

<style lang="scss" scoped>
.container {
  background: #fff; 
}

section {
  padding: 112px 0 48px;
}

.content {
  display: flex;
  margin: 0 0 0 128px;
  padding: 0 16px;

  > img {
    width: 50%;
    height: 50%;
    padding: 0 16px;
    border-radius: 50px;
  }  
}

.content-texts {
  display: flex;
  flex-direction: column;
  justify-content: center;

  > strong {
    font-size: 48px;
    margin: 0 0 32px;
    color: #244c22;
  }

  > b {
    font-size: 24px;
    margin: 0 0 16px;
    color: #6C758F;
  }
}

.img-hover {  
  background: url("../../assets/lixeira-fechada.png") no-repeat;
  background-size: auto 100%;
  width: 200px;
  height: 300px;
  margin-left: 160px;

  &:hover {
    background: url("../../assets/lixeira-aberta.png") no-repeat;
    background-size: auto 100%;
    width: 200px;
    height: 300px;
    transition: 0.2s;
  }
}

</style>