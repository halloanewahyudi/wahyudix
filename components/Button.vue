<template>
   <div class="max-w-max flex justify-between items-center">
  <div class="-mr-4">
   <nuxt-img src="/images/ta_small.png" format="webp"></nuxt-img>
  </div>
  <div class="text"> <a :href="link" :target="target"> {{button_text}} </a> </div>
  <div>
      <nuxt-img src="/images/arrow.svg" format="webp"></nuxt-img>
  </div>
 </div>
</template>
<script>
export default {
    props: {
        button_text: {
            type: String,
            default: 'Selanjutnya'
        },
        link: {
            type: String,
            default: '/'
        },
        target:{
            type: String,
        }

    }
}
</script>