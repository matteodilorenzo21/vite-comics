<script>

</script>

<template>
    <section>
        <div class="container h-100 space-around">

            <figure>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="digital comics">
                <figcaption><a href="#">DIGITAL COMICS</a></figcaption>
            </figure>

            <figure>
                <img src="../assets/img/buy-comics-merchandise.png" alt="merchandise">
                <figcaption><a href="#">DC MERCHANDISE</a></figcaption>
            </figure>

            <figure>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="subscriptions">
                <figcaption><a href="#">SUBSCRIPTIONS</a></figcaption>
            </figure>
            
            <figure>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="shop locator">
                <figcaption><a href="#">SHOP LOCATOR</a></figcaption>
            </figure>

            <figure>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="buy power visa">
                <figcaption><a href="#">DC POWER VISA</a></figcaption>
            </figure>

        </div>
    </section>
</template>

<style lang="scss" scoped>
    section {
        height: 120px;
        background-color: #0282F9;
    }

    .space-around {
    display: flex;
    justify-content: space-around;
    align-items: center;
    }

    .h-100 {
    height: 100%;
    }

    figure {
        display: flex;
    }

    figcaption {
        padding: 20px 0;
        margin-left: 5px;

        a {
            text-decoration: none;
            color: #fff;

            &:hover {
                color: #000;
            }
        }
    }

    img {
        height: 60px;
        width: 50px;
    }

</style>