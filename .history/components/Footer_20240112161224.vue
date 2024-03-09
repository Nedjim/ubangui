<script setup lang="ts">
const address = "B.P. : 589 Saint-Louis, Sénégal";
const mail = "residence.ubangui@gmail.com";
const phone_number = "+221 77 643 66 79 / +221 77 568 49 89";
</script>

<template>
  <div>
    <footer>
      <h4>Résidence Ubangui</h4>

      <div class="contact">
        <p>
          <font-awesome-icon class="icon" icon="fa-solid fa-map" />
          {{ address }}
        </p>
        <p>
          <font-awesome-icon class="icon" icon="fa-solid fa-envelope" />

          {{ mail }}
        </p>
        <p>
          <font-awesome-icon class="icon" icon="fa-solid fa-phone" />
          {{ phone_number }}
        </p>
      </div>
    </footer>
  </div>
</template>

<style scoped lang="scss">
footer {
  width: 100%;
  padding: 16px 40px;
  margin-top: 40px;
  background: #232e39;
  color: rgba(255, 255, 255, 0.5);

  .contact {
    color: white;
    font-size: 14px;

    .icon {
      margin-right: 8px;
    }
  }
}
</style>
