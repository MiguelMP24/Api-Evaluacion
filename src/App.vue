<script>
import navbar from '@/components/navbar.vue';
import foot from '@/components/foot.vue';
import personajes from '@/components/personajes.vue';



export default {
    name: 'App',
    components: {
        navbar,
        personajes,
        foot
    },
}
</script>

<template>
    <div>
    <navbar/>
 
    <personajes/>

    <foot/>
</div>
</template>

<style>
</style>
