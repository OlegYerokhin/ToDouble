<template>
  <q-header 
    class="wrapper bg-primary"
  >
    <div class="q-pa-md flex justify-around items-center">
      <img src="../assets/logo.png" alt="logo">
      <nav
        class="wrapper__navigation"
      >
        <a href="/" class="q-mx-md text-white text-bold">Услуги</a>
        <a href="/" class="q-mx-md text-white text-bold">Портфолио</a>
        <a href="/" class="q-mx-md text-white text-bold">Этапы</a>
        <a href="/" class="q-mx-md text-white text-bold">Дизайнеры</a>
        <q-btn 
          label="Заказать"
          flat
          class="wrapper__order q-px-lg q-mx-md bg-positive text-bold cursor-pointer no-hover"
          size="15px"
        />
      </nav>
    </div>
  </q-header>

</template>

<script>
export default {
  
}
</script>

<style lang="scss" scoped>
  .wrapper {
    
      &__order {
        border-radius: 5px;
        border: 2px solid $positive;
        &:hover {
          border: 2px solid $white;
        }
        &:active {
          background-color: $white !important;
          color: $primary !important;
          border: 2px solid $primary;
        }
      }
    
  }
</style>