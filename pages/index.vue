<template>
<div>
  <HomeCover />
  <HomeSection2 id="sec2" class="lg:pb-20" />
  <nuxt-img src="/images/tempe.png" format="webp" sizes="lg:300px md:100px" class="absolute -mt-32"></nuxt-img>
   <HomeSection3 class="lg:-mt-32 py-10 mb-4 lg:mb-0" />
</div>
</template>

<script>
export default {
  name: 'IndexPage',
  layout:'default'
}
</script>
