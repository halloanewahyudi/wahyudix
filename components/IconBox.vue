<template>
         <div class="icon-box flex flex-col lg:flex-row text-center lg:text-left">
        <div class="w-20 h-auto flex-shrink-0 mb-3 bg-slate-200 lg:mr-1 mx-auto lg:mx-0"><nuxt-img :src="icon" format="webp"></nuxt-img></div>
        <div class="w-auto">
          <h5 class="text-2xl text-serif text-info font-bold mb-3 leading-3">{{title}}</h5>
          <div class="text">{{description}}</div>
        </div>
      </div>
</template>
<script>
export default {
  name: 'IconBox',
        props: {
            icon: {
                type: String,
                default: 'icon'
            },
            title: {
                type: String,
                default: 'Title'
            },
            description: {
                type: String,
                default: 'Description'
            }
        }
    
}
</script>