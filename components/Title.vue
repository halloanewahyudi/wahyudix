<template>
  <div class="flex justify-center items-center mb-20">
    <kinesis-container>
      <kinesis-element strength="29" class="-mr-20">
        <nuxt-img src="/images/ta.png" ></nuxt-img>
      </kinesis-element>
    </kinesis-container>

    <h1 class="text-6xl text-info font-bold z-10">{{ title }}</h1>
  </div>
</template>
<script>
export default {
  props: {
    title: {
      type: String,
      required: true,
      defuylt: "Hello World",
    },
  },
};
</script>