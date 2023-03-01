<template>
  <div class="about">
    <h1 class="text">This is an about page</h1>
    <el-button>test</el-button>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>

<style lang="scss" scoped>
.text {
  color: $primary-color;
}
</style>
