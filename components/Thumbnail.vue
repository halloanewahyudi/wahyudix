<template>
    <div>
        <nuxt-img :src="image" format="webp" class="mx-auto mb-3 rounded-lg" />
        <h4 class="text-4xl font-bold text-info text-serif mb-3">{{title}}</h4>
        <p>{{description}}</p>
        <Button :link="link" :target="target"/>
    </div>
</template>
<script>
export default {
    props: {
        image: {
            type: String,
            required: true,
            default: '/images/project/ser/ser-cover.jpg'
        },
        title: {
            type: String,
            required: true,
            default:'Hello World'
        },
        description:{
            type: String,
            required: false,
            default: 'Quisque non condimentum dui. Vestibulum posuere at odio id venenatis'
        },
        link: {
            type: String,
            required: true,
            default: '/'
        },
        target:{
            type: String,
            required: false,
            default: '_self'
        }
    }
}
</script>