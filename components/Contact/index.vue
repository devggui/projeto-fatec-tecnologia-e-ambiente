<template>
  <div class="container">
    <section>
      <div class="content">
        <div class="content-form">
          <strong>Contato</strong>
            <label for="nome">Nome:</label>
            <input type="texto" id="nome" name="nome_usuario">
            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email_usuario">
            <label for="texto">Texto:</label>
            <textarea id="texto" name="texto_usuario"></textarea>        
            <button type="submit">Enviar</button>                  
        </div>
        <img src="../../assets/contato3.svg">
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
  margin: 0 0 0 300px;
  padding: 0 16px;

  > img {
    width: 40%;
    height: 50%;
    padding: 0 16px;
    border-radius: 50px;
    margin-left: 300px;    
  }  
}

.content-form {
  display: flex;
  flex-direction: column;
  justify-content: center;

  > strong {
    font-size: 48px;
    font-weight: 800;
    margin: 10px 0 10px 0;
    color: #244c22;
    text-align: center;
  }

  > label {
      display: inline-block;
      width: 90px;
      text-align: center;
      font-size: 24px;
      font-weight: 800;
      margin: 20px 0 10px 0;
      color: #244c22;
    }

  > input, textarea {
      font: 1em sans-serif;
      width: 300px;
      box-sizing: border-box;  
      border: 1px solid #999;
      border-radius: 3px;
      padding: 10px;
    }

    > button {
      width: 100%;
      padding: 20px;
      border-radius: 3px;
      background: #244c22;
      font-size: 24px;
      color: #fff;
      font-weight: 800;
      margin: 20px 0 20px 0;
    }
}

input:focus, textarea:focus {  
  border-color: #000;
}

textarea {
  vertical-align: top;
  height: 15em;
}
</style>