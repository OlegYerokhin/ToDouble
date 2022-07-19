<template>
  <q-page>
    <div class="wrapper column">
      <div class="wrapper__content">
        <h1>Разработка интернет-магазина с нуля за неделю</h1>
        <p class="wrapper__text">Дизайн интернет магазина, элементов микро UX, корзин, личного кабинета - от фирменного стиля 
          до пользовательского интерфейса в сжатые сроки 
          с командой Virtual Designers 
        </p>
        <q-btn 
          label="Заказать"
          flat
          class="wrapper__order-btn flex q-px-xl q-py-sm bg-positive text-white text-bold cursor-pointer no-hover"
          size="15px"
        />
      </div>

    </div>
  </q-page>
</template>

<style lang="scss" scoped>
  .wrapper {
    background: url(../assets/development-bg.png);
    background-size: cover;
    // height: 766px;
    padding: 175px 377px;
    &__content {
      width: 60%;
    }
    &__text {
      line-height: 22px;
      width: 432px;
      padding-bottom: 55px;
    }
    &__order-btn {
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