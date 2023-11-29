<script>
export default {
    name: "AppJumbo",
    props: ["links"],
    mounted() {
        console.log("Componente AppJumbo caricato");
    }
}
</script>

<template>
    <section>
        <span><img class="jumbo" src="../assets/img/jumbotron.jpg" alt=""></span>
        <div>
            <span v-for="link in links"> {{ link.thumb }}</span>
        </div>

    </section>

    <section class="digital-comics">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
        <span class="scritte">DIGITAL COMICS</span>

        <img src="../assets/img/buy-comics-merchandise.png" alt="">
        <span class="scritte">DC MERCHANDISE</span>

        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
        <span class="scritte">SUBSCRIPTION</span>

        <img class="loc" src="../assets/img/buy-comics-shop-locator.png" alt="">
        <span class="scritte">COMIC SHOP LOCATOR</span>

        <img class="power" src="../assets/img/buy-dc-power-visa.svg" alt="">
        <span class="scritte">DC POWER VISA</span>

        <section class="back">
            <div class="container">
                <div class="menu-left">
                    <h3>DC COMICS</h3>
                    <div>Characters</div>
                    <div>Comics</div>
                    <div>Movies</div>
                    <div>TV</div>
                    <div>Games</div>
                    <div>Videos</div>
                    <div>News</div>

                    <div>
                        <h3>SHOP</h3>
                        <div>Shop DC</div>
                        <div>Shop DC collectibles</div>
                    </div>
                </div>

                <div class="menu-center">
                    <h3>DC</h3>
                    <div>Terms Of Use</div>
                    <div>Privacy policy(NEW)</div>
                    <div>Ad Choices</div>
                    <div>Advertising</div>
                    <div>Job</div>
                    <div>Subscripitons</div>
                    <div>Talen Workshop</div>
                    <div>CPSC Certicicates</div>
                    <div>Ratings</div>
                    <div>Shop Help</div>
                    <div>Contact Us</div>
                </div>

                <div>
                    <h3>SITES</h3>
                    <div>DC</div>
                    <div>MAD Magazine</div>
                    <div>DC Kids</div>
                    <div>DC Universe</div>
                    <div>DC Power Visa</div>
                </div>

                <div>
                    <img class="logo" src="../assets/img/dc-logo-bg.png" alt="">
                </div>

            </div>

        </section>

    </section>
</template>

<style scoped>
.jumbo {
    width: 100%;
    height: 25rem;
    padding: 0;
    object-fit: fill;
}
</style>

<style scoped>
.digital-comics {
    width: 100%;
    background-color: rgb(2, 130, 249);
}
</style>

<style scoped>
img {
    width: 3%;
    padding-top: 1%;
    padding-right: 1%;
    padding-left: 4%;
}
</style>

<style scoped>
.power {
    width: 4%;
}
</style>

<style scoped>
.scritte {
    position: relative;
    bottom: 0.9rem;
}
</style>

<style scoped>
.loc {
    width: 2%;
}
</style>

<style scoped>
.back {
    background-image: url(../assets/img/footer-bg.jpg);
    width: 100%;
}
</style>

<style scoped>
.container {
    display: flex;
    font-size: small;
}
</style>

<style scoped>
.menu-center {
    padding-right: 5%;
}
</style>

<style scoped>
.menu-left {
    padding-left: 10%;
    padding-right: 5%;
}
</style>

<style scoped>
.logo {
    width: 70%;
    position: relative;
    left: 10%;
}
</style>