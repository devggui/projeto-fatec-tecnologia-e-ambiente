<template>
  <div class="container">
    <header>
      <img class="logo" src="../../assets/logo.png">
      <div class="nav-bar">
        <nav>      
          <ul class="nav-links">
            <li><nuxt-link to="/">Home</nuxt-link></li>
            <li><nuxt-link to="/aboutus">Sobre nós</nuxt-link></li>                                    
            <li><nuxt-link to="/contact">Contato</nuxt-link></li>
          </ul>
        </nav>
      </div>
    </header>
  </div>
</template>

<script>

</script>

<style lang="scss" scoped>
.container {
  background: #56bdaa;
}

header {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  min-width: 100px; 
  height: 120px;
  margin: 0 226px 0 226px;
  padding: 16px 0px;
}

.logo {
  height: 15rem;
  cursor: pointer;
}

.nav-bar {
  display: flex;
  align-items: center; 
}

.nav-links {
  list-style: none;
}

.nav-links li {
  display: inline-block;
  padding: 0 20px;  
}

.nav-links li a {
  transition: all 0.3s ease 0s;
  color: #244c22;
  font-weight: 800;
  font-size: 20px;
}

span {
  display: flex;
  flex-direction: row;
  padding: 0 0 0 10px;
}


</style>