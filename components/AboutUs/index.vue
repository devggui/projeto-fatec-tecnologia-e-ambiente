<template>
  <div class="container">
    <section>
      <div class="content">
        <div class="content-texts">
          <strong>Sobre nós</strong>
          <b>Somos estudantes do curso de banco de dados na faculdade de técnologia de Bauru - FATEC.</b>
          <strong>Objetivo</strong>
          <b>Nosso objetivo com esse site é indicar aos usuarios que acessarem a importancia da reciclagem do lixo eletrônico, e indica-los onde podem ser descartados</b>
        </div>
        <img src="../../assets/fatec.webp">
      </div>
    </section>
  </div>
</template>

<script>

</script>

<style scoped lang="scss">
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

</style>