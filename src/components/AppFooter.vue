<script>
import FooterTop from '../components/FooterSections/FooterTop.vue';
import FooterBottom from '../components/FooterSections/FooterBottom.vue';
export default {
    components: {
        FooterTop,
        FooterBottom
    }
} 
</script>

<template>
    <footer>
        <!-- Import Top Footer Section -->
        <FooterTop />
        <!--Import Bottom Footer Section-->
        <FooterBottom />
    </footer>
</template>


<style lang="scss" scoped>
</style>