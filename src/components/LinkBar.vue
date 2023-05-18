<script>
export default {
    
}
</script>

<template>
    <div id="linkBar">
        <div>
            <img src="../assets/img/buy-comics-digital-comics.png" alt="dicital-comics">
            DIGITAL COMICS
        </div>
        <div>
            <img src="../assets/img/buy-comics-merchandise.png" alt="merchandise">
            DC MERCHANDISE
        </div>
        <div>
            <img src="../assets/img/buy-comics-subscriptions.png" alt="subscriptions">
            SUBSCRIPTION
        </div>
        <div>
            <img src="../assets/img/buy-comics-shop-locator.png" alt="shop-lacator">
            COMIC SHOP LOCATOR
        </div>
        <div>
            <img src="../assets/img/buy-dc-power-visa.svg" alt="power-visa">
            DC POWER VISA
        </div>
    </div>
</template>

<style lang="scss" scoped>
    
    
    #linkBar{
        background-color: #0282F9;
        color: #fff;
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding-inline: 2em;

        div {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: .5em;
        }

        img {
            width: 25%;
            height: auto;
        }
    }
</style>