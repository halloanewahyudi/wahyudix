<template>
  <div class="flex items-center">
    <div class="w-32 h-1 border-0 border-b-2 border-info mr-3"></div>
    <h4 class="text-3xl font-bold text-serif text-info ">{{ title }}</h4>
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
    },

}
</script>