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
        <section id="jumbotron">
            <div class="container-wrapped">
                <h2> --> Content Here {{'<--'}} </h2>
            </div>
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
    background-color: black;
    color: white;
    padding: 2rem;
}
</style>