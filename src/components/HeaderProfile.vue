<template>
<nav class="navbar navbar-expand-lg fixed-top text-uppercase">
  <div class="container">
      <a class="navbar-brand font-weight-bold" href=""><img src="../assets/logo.png" alt="Logo"></a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav ms-auto">
          <a class="nav-link actived px-lg-4 rounded" href="#">Home</a>
          <a class="nav-link px-lg-4 rounded" href="#">Serviços</a>
          <a class="nav-link px-lg-4 rounded" href="#">Sobre mim</a>
          <a class="nav-link px-lg-4 rounded" href="#">Contatos</a>
      </div>
    </div>
  </div>
</nav>
  
</template>
<script>
  export default{
    name: 'HeaderProfile.vue'
  }
</script>