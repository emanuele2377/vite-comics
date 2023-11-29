<script>
export default {
    name:
        "AppHeader"

}

</script>

<template>
    <header>

        <img src="../assets/img/dc-logo.png" alt="">
        <span>Characters</span>
        <span>Comics</span>
        <span>Movies</span>
        <span>TV</span>
        <span>Games</span>
        <span>Collectibles</span>
        <span>Videos</span>
        <span>Fans</span>
        <span>News</span>
        <span>Shop</span>

    </header>
</template>

<style scoped>
header {
    background-color: white;
    display: flex;
}
</style>

<style scoped>
span {
    margin: 0 1rem;
    color: black;
    position: relative;
    top: 2rem;
}
</style>

<style scoped>
img {
    width: 5%;
    padding-right: 15%;
    padding-left: 5%;
    padding-top: 3%;
    position: relative;
    bottom: 1.2rem;
}
</style>