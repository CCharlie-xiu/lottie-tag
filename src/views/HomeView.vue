<template>
  <div class="home">
      <div class="ani-box">
        <cente-lottie :width="300" :height="300"></cente-lottie>
    </div>
  </div>
</template>

<script>
import { defineComponent } from "vue";
import centeLottie from '@/components/centeLottie'
  export default  defineComponent({
    components: {
      centeLottie
    }
  })
</script>


<style scoped lang='less'>

</style>