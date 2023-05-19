<script>
export default {
    
}
</script>

<template>
    <footer>
        <div id="mainFooter">
            <div id="linkFooter">
                <div>
                    <h3>DC COMICS</h3>
                    <a href="#">Characters</a>
                    <a href="#">Comics</a>
                    <a href="#">Movie</a>
                    <a href="#">TV</a>
                    <a href="#">Games</a>
                    <a href="#">Videos</a>
                    <a href="#">News</a>
                </div>
                <div>
                    <h3>SHOP</h3>
                    <a href="#">Shop DC</a>
                    <a href="#">Shop DC collectibles</a>
                </div>
                <div>
                    <h3>DC</h3>
                    <a href="#">Terms Of Use</a>
                    <a href="#">Privacy policy (New)</a>
                    <a href="#">Ad Choices</a>
                    <a href="#">Advertising</a>
                    <a href="#">Jobs</a>
                    <a href="#">Subscriptions</a>
                    <a href="#">Talent Workshops</a>
                    <a href="#">CPSC Certificates</a>
                    <a href="#">Ratings</a>
                    <a href="#">Shop Help</a>
                    <a href="#">Contact US</a>
                </div>
                <div>
                    <h3>SITES</h3>
                    <a href="#">DC</a>
                    <a href="#">MAD Magazine</a>
                    <a href="#">DC Kids</a>
                    <a href="#">DC Universe</a>
                    <a href="#">DC Power Visa</a>
                </div>
            </div>
            <img src="../assets/img/dc-logo-bg.png" alt="DC_logo">
        </div>
            
        <div id="signUp">
            <button>SIGN-UP NOW!</button>
            <div>
                <span>FOLLOW US</span>
                <img src="../assets/img/footer-facebook.png" alt="facebook">
                <img src="../assets/img/footer-twitter.png" alt="twitter">
                <img src="../assets/img/footer-youtube.png" alt="youtube">
                <img src="../assets/img/footer-pinterest.png" alt="pinteret">
                <img src="../assets/img/footer-periscope.png" alt="periscope">
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
    footer {
        background: url(../assets/img/footer-bg.jpg) no-repeat;
        background-size: cover;
        color: #fff;
        max-height: 482px;
        position: relative;
        z-index: -10;

    }

    #mainFooter{
        display: flex;

        img {
            position: absolute;
            z-index: -5;
            bottom: 0;
            right: 0;
        }
    }
    
    #linkFooter {
        max-height: calc(482px - 6em);
        display: flex;
        flex-wrap: wrap;
        flex-direction: column;

        div{
            display: flex;
            flex-direction: column;
        }
    
        a, a:hover, a:active{
            color: grey;
            text-decoration: none;
            font-size: smaller;
        }
    }
    
    #signUp {
        background-color: rgb(48, 48, 48);
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding-block: 2em;

        button {
            border: 3px solid #0282F9;
            color: #fff;
            padding: 1em;
        }

        div {
            display: flex;
            align-items: center;
            gap: 1em;
            color: #0282F9;
        }
    }
</style>