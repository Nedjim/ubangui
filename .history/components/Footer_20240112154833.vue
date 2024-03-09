<script setup lang="ts">

const address = "B.P. : 589 Saint-Louis, Sénégal";
const mail = "residence.ubangui@gmail.com";
const phone_number = "+221 77 643 66 79 / +221 77 568 49 89";

</script>

<template>
  <footer>
    <div class="content">
      Résidence Ubangui
    </div>

    <div>
      <p>{{ address }}</p>
      <p>{{ mail }}</p>
      <p>{{ phone_number }}</p>
    </div>
  </footer>
</template>

<style  scoped lang="scss">
footer {
  width: 100%;
  padding: 16px 0;
  background: #232e39;
  color: rgba(255,255,255,.5);

  .content {
    padding: 8px 24px;
  }
}
</style>