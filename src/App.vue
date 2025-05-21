<template>
  <div class="container">
    <h1 class="title">Aniversário do Wesley</h1>
    <img src="./dance.gif" alt="GIF animado" class="gif" />
    <p style="margin-left: 20px; margin-right: 20px;" class="description">Meu aniversário e dia <strong>22/05</strong> mas vamos comer um bolinho dia <strong>23/05</strong>.<br><br><p>⏰ 19:00 📌 Rua capitão olavo 505</p></p>
    
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  text-align: center;
}

.title {
  font-size: 2rem;
  margin-bottom: 20px;
  color: #000000;
}

.gif {
  max-width: 300px;
  margin-bottom: 20px;
}

.description {
  font-size: 1.2rem;
  color: #000000;
}
</style>
