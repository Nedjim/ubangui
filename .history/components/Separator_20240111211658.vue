<template>
    <div>
        <div class="separator"></div>
    </div>
</template>

<style scoped lang="scss">
.separator {
  overflow: hidden;
  height: 20px;
}

.separator:after {
  content: '';
  display: block;
  width: 90%;
  height: 30px;
  margin: -30px auto 0;
  border-radius: 120px / 10px;
  box-shadow: 0px 0px 8px rgba(0,0,0,.6);
}
</style>