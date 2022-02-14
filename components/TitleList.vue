<template>
   <div>
  <div class="text-1xl font-bold text-info">{{title}}  <span class="w-2 h-2 inline-block rounded-full bg-orange"></span></div>
  <div class="mb-3">{{description}}</div>
</div>
</template>
<script>
export default {
    props: {
        title: {
            type: String,
            required: true,
            default: "Hello World",
        },
        description:{
            type: String,
            required: false,
            default: 'Quisque non condimentum dui. Vestibulum posuere at odio id venenatis'
        },
    },
}
</script>