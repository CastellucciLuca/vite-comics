<script>
</script>

<template>
    <section id="bottom-footer">
        <div class="container-wrapped d-flex flex-between">
            <button>SIGN-UP NOW!</button>
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
@use '../../styles/partials/variables.scss' as *;
section#bottom-footer {
    background-color: $footer-bg;
    padding: 2rem;
}
button {
    color: white;
    font-size: 1.2rem;
    background-color: #303030;
    border: 2px solid #0681f3;
    padding: 0.8rem;
    &:hover {
        color: white;
        background-color: $dc-color;
    }
}

div.social-btn {
    h3 {
        color: $dc-color;
        text-transform: uppercase;
        font-size: 1.5rem;
        margin-right: 1rem;
        font-weight: bold;
        margin-top: 0.8rem;
    }
    ul {
        display: flex;
        margin-top: 0.4rem;
        li {
            list-style-type: none;
            padding: 0 .7rem;
            a img {
                transform: scale(1.2);
                vertical-align: middle;
                &:hover {
                    transition: all .2s ease-in-out;
                    transform: scale(1);
                }
            }
        }
    }
}
</style>