<script setup lang="ts">

const address = "B.P. : 589 Saint-Louis, Sénégal";
const mail = "residence.ubangui@gmail.com";
const phone_number = "+221 77 643 66 79 / +221 77 568 49 89";

</script>

<template>
  <footer>
      <h3>Résidence Ubangui</h3>
    

    <div class="contact">
      <p>{{ address }}</p>
      <p>{{ mail }}</p>
      <p>{{ phone_number }}</p>
    </div>
  </footer>
</template>

<style  scoped lang="scss">
footer {
  padding: 8px 24px;
  width: 100%;
  padding: 16px 0;
  background: #232e39;
  color: rgba(255,255,255,.5);


  .contact {
    color: white;
  }
}
</style>