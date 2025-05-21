<template>
  <div class="container">
    <h1 class="title">Aniversário do Wesley</h1>
    <img src="./dance.gif" alt="GIF animado" class="gif" />
    <div style="margin-left: 20px; margin-right: 20px" class="description">
      <p>
        Meu aniversário é no dia <strong>22 de maio</strong>, mas a comemoração
        será em:
      </p>
      <br />
      <p>📅 Data: 23 de maio de 2025 (sexta-feira)</p>

      <p>📍 Local: Rua Capitão Olavo, 505</p>

      <p>⏰ Horário: 19h00</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
};
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
