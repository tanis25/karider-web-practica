<script setup>
// ✏️ CAMBIO VISIBLE: edita este texto, guarda (commit) en main
// y comprueba que aparece en el sitio publicado.
const mensaje = 'Versión 1 — despliegue de práctica'
</script>

<template>
  <header class="barra">
    <span class="logo">KARider</span>
    <span class="sub">Viajes compartidos UTTT · Equipo G3</span>
  </header>
  <main class="contenido">
    <section class="tarjeta">
      <h1>Frontend publicado en Azure Static Web Apps</h1>
      <p class="mensaje">{{ mensaje }}</p>
      <p>Cada cambio que llega a la rama <b>main</b> se publica automáticamente con GitHub Actions.</p>
    </section>
  </main>
</template>

<style scoped>
.barra { background: #1D2D44; color: #fff; padding: 16px 20px; display: flex; gap: 12px; align-items: baseline; flex-wrap: wrap; }
.logo { font-weight: 800; font-size: 1.4rem; }
.sub { opacity: .75; font-size: .9rem; }
.contenido { max-width: 720px; margin: 24px auto; padding: 0 16px; }
.tarjeta { background: #fff; border: 1px solid #dde3ea; border-radius: 12px; padding: 20px; }
h1 { font-size: 1.4rem; margin: 0 0 12px; color: #1D2D44; }
.mensaje { font-size: 1.3rem; color: #0284C7; font-weight: 700; }
</style>
