<template>
  <div class="container">
    <div>
      <img src="https://zapnotes.com.br/logo.png">

      <h2 class="subtitle">
        Organize sua vida no WhatsApp!
      </h2>
      <div class="links">
        <a
          href="https://api.whatsapp.com/send?phone=556293926787&text=Come%C3%A7ar"
          target="_blank"
          class="button--green"
        >
          Começar
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
