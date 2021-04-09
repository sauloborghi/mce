<template>
<div class="card position-relative">
  <div class="mb-3">
  <label for="exampleFormControlInput1" class="form-label">Nome</label>
  <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="José Silva">
  <br>
  <label for="exampleFormControlInput1" class="form-label">Email</label>
  <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="jose_silva@gmail.com">
  <br>
  <label for="exampleFormControlInput1" class="form-label">Assunto</label>
  <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="Problema no cadastro">
  <br>
  <label for="exampleFormControlInput1" class="form-label">Telefone</label>
  <input type="number" class="form-control" id="exampleFormControlInput1" placeholder="(99)9999-9999">
  <center>
  <button type="submit" class="btn btn-success mb-3">Enviar</button>
  </center>
</div>
</template>

<style scoped>
  .card {
    margin-top: 10px;
    margin-left: 10px;
    margin-right: 10px;
    margin-bottom: 10px;
  }
  .mb-3 {
    margin-top: 10px;
    margin-left: 20px;
    margin-right: 20px;
    margin-bottom: 10px;
  }
  </style>
  
<script>
export default {
  name: 'Form',
}
</script>