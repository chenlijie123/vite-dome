<template>
  <div class="about">
    <h1>This is an about page</h1>
    <div class="notes">
      <span class="nt-text">22222223</span>
    </div>
  </div>
</template>

 
<style lang="scss" scoped>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
.notes {
  width: 100px;
  height: 100px;
  .nt-text{
    color:red;
  }
}
</style>
