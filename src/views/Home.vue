<template>
  <div class="home">
    <Navbar />

    <main class="container vh-100 d-flex flex-column justify-content-center">
      <h1>COLOCAR AQUI EL CONTENIDO</h1>
      <!-- primary para los botones -->
      <button class="btn btn-primary">Contactanos</button>
    </main>

    <!-- SECCIONES DEL SITIO -->
    <section class="vh-100 d-flex align-items-center bg-secondary">
      <div class="container">
        <h1>COLOCAR AQUI EL CONTENIDO</h1>
        <button class="btn btn-dark w-100">Contactanos</button>
      </div>
    </section>

    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Navbar,
    Footer
  }
}
</script>