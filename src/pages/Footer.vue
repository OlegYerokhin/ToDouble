<template>
  <q-footer class="footer bg-primary">
    <div class="container flex justify-center">
      <div class="column col-4 ">
        <q-img class="company-logo row q-mb-xl" width="280px" src="../assets/logo.png" alt="logo" />
        <ul class="flex">
          <li>
            <a class="social-network cursor-pointer" href="/"><img src="../assets/instagram.png" alt="instagram"></a>
          </li>
          <li>
            <a class="social-network cursor-pointer" href="/"><img src="../assets/facebook.png" alt="facebook"></a>
          </li>
          <li>
            <a class="social-network cursor-pointer" href="/"><img src="../assets/telegram.png" alt="telegram"></a>
          </li>
          <li>
            <a class="social-network cursor-pointer" href="/"><img src="../assets/viber.png" alt="viber"></a>
          </li>
          <li>
            <a class="social-network cursor-pointer" href="/"><img src="../assets/whatsapp.png" alt="whatsapp"></a>
          </li>
        </ul>
      </div>
      <div class="contact column col-4">
        <ul>
          <li class="contact-item flex q-mb-md">
            <img src="../assets/viber.png" alt="viber" class="contact__contact-icon q-mx-sm">
            <p>Валерия:</p>
            <a class="q-ml-xs text-white" href="tel:+380505859409">+380505859409</a>
          </li>
          <li class="flex q-mb-md">
            <img src="../assets/viber.png" alt="viber" class="contact__contact-icon q-mx-sm">
            <p>Анна:</p>
            <a class="q-ml-xs text-white" href="tel:+380505859409">+380505859409</a>
          </li>
          <li class="flex">
            <img src="../assets/viber.png" alt="viber" class="contact__contact-icon q-mx-sm">
            <p>Валерия:</p>
            <a class="q-ml-xs text-white" href="tel:+380505859409">+380505859409</a>
          </li>
        </ul>
      </div>
      <div class="column col-4">
        <a class="text-white" href="mailto:hr@dv-s.com">hr@dv-s.com</a>
      </div>
    </div>
    <div class="rights flex justify-center">
      <p>Developers 2018-2022 © All rights reserved</p>
    </div>
  </q-footer>

</template>

<script>
export default {
  
}
</script>

<style lang="scss" scoped>

.container {
  margin-top: 100px;
}

.social-network {
  margin-right: 38px;
}

.contact {
  margin: 0 120px;
  
  &__contact-icon {
    width: 22px;
    height: 22px;
  }
}

.rights {
  margin: 120px 0 70px;
}
</style>