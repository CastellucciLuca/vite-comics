<script>
</script>

<template>
    <section id="bottom-footer">
        <div class="container-wrapped d-flex flex-between">
            <a href="#">SIGN-UP NOW!</a>
            <div class="social-btn d-flex align-center">
                <h3>FOLLOW US</h3>
                <ul>
                    <li>
                        <a href="#"><img src="../../assets/footer-facebook.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="../../assets/footer-twitter.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="../../assets/footer-youtube.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="../../assets/footer-pinterest.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="../../assets/footer-periscope.png" alt=""></a>
                    </li>
                </ul>
            </div>
        </div>
    </section>
</template>


<style lang="scss" scoped>
section#bottom-footer {
    background-color: #303030;
    padding: 2rem;
}
a {
    font-size: 1.8rem;
}
div.social-btn {
    h3 {
        color: white;
    }
    ul {
        display: flex;
        li {
            list-style-type: none;
            padding: 0 .5rem;
            a img {
                vertical-align: middle;
            }
        }
    }
}
</style>