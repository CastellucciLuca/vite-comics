<script>
import BlueSpot from './AppMainBlueSpot.vue'
export default {
    components: {
        BlueSpot
    }
}
</script>

<template>
    <main>
            <section id="jumbotron" class="d-flex align-center">
                <h2> Content Goes Here </h2>
            </section>
            <!--BONUS SECTION-->
            <BlueSpot/>
    </main>
</template>


<style lang="scss" scoped>
main{
    width: 100%;
}
section#jumbotron {
    height: 205px;
    background-color: black;
    color: white;
    padding: 2rem;
}
</style>