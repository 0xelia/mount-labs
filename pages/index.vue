<template>
    <div>
        <HeroHome />
        <section id="sec_2" class="h-screen flex justify-center items-center">
            <h1>Section 2</h1>
        </section>
    </div>
</template>

<script>
import HeroHome from '~~/components/heroHome.vue';

export default {
    components: {HeroHome}
}
</script>

<style lang="scss" scoped>
#sec_2{
    position: relative;
    // &::after{
    //     content: '';
    //     display: block;
    //     position: absolute;
    //     width: 100%;
    //     height: 170px;
    //     background: linear-gradient(0deg, rgb(255, 255, 255) 0%, rgba(255,255,255,0) 100%);;
    //     top: -170px;
    //     z-index: 9999999;
    // }
}
</style>