<script>
    export default{
    name: 'AppFooter',
    data(){
        return{

        }
    }
}

</script>

<template>
    <footer>
        <div class="upper-side">
            <div class="upper-footer">
                <div class="list-item">
                    <div class="margin-right">
                        <h3>
                            DC COMICS
                        </h3>
                        <ul class="list">
                            <li>
                                Characters
                            </li>
                            <li>
                                Comics
                            </li>
                            <li>
                                Movies
                            </li>
                            <li>
                                TV
                            </li>
                            <li>Games</li>
                            <li>
                                Videos
                            </li>
                            <li>
                                News
                            </li>
                        </ul>

                        <h3 class="margin-top">
                            SHOP
                        </h3>
                        <ul class="list">
                            <li>
                                Shop DC
                            </li>
                            <li>
                                Shop DC Collectibles
                            </li>
                        </ul>
                    </div>

                    <div class="margin-right">
                        <h3>
                            DC
                        </h3>
                        <ul class="list">
                            <li>
                                Term Of Use
                            </li>
                            <li>
                                Privacy policy (New)
                            </li>
                            <li>
                                Ad Choices
                            </li>
                            <li>
                                Advertising
                            </li>
                            <li>
                                Jobs
                            </li>
                            <li>
                                Subscriptions
                            </li>
                            <li>
                                Talent Workshops
                            </li>
                            <li>
                                CPSC Certificates
                            </li>
                            <li>
                                Ratings
                            </li>
                            <li>
                                Shop Help
                            </li>
                            <li>
                                Contact Us
                            </li>
                        </ul>
                    </div>

                    <div>
                        <h3>
                            SITES
                        </h3>
                        <ul class="list">
                            <li>
                                DC
                            </li>
                            <li>
                                MAD Magazine
                            </li>
                            <li>
                                DC Kids
                            </li>
                            <li>
                                DC Universe
                            </li>
                            <li>
                                DC Power Visa
                            </li>
                        </ul>
                    </div>
                </div>

        
                <div class="logo-item">
                    
                </div>
            </div>
        </div>

        <div class="lower-side">
            <div class="lower-footer">
                <div class="sign-up">
                    SIGN-UP NOW!
                </div>
                <div class="social-side flex">
                    <h2 class="follow">
                        FOLLOW US
                    </h2>
                    <div class="social-icon">
                        <a href="#">
                            <img src="../assets/images/img/footer-facebook.png" alt="Facebook logo">
                        </a>
                        <a href="#">
                            <img src="../assets/images/img/footer-twitter.png" alt="Facebook logo">
                        </a>
                        <a href="#">
                            <img src="../assets/images/img/footer-youtube.png" alt="Facebook logo">
                        </a>
                        <a href="#">
                            <img src="../assets/images/img/footer-pinterest.png" alt="Facebook logo">
                        </a>
                        <a href="#">
                            <img src="../assets/images/img/footer-periscope.png" alt="Facebook logo">
                        </a>
                    </div>
                </div>
            </div>
        </div>

    </footer>
</template>

<style lang="scss" scoped>

@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

footer{
    background-image: url('../assets/images/img/footer-bg.jpg');
    background-repeat: no-repeat;
    background-size: cover;
}

.upper-side{
    display: flex;
    justify-content: center;
    color: $whiteText;
}

div.upper-footer{
        width: 1100px;
        display: flex;
        justify-content: space-between;
        align-items: center;
}

div.list-item{
    display: flex;
    padding: 3rem 0;
}

div h3{
    padding-bottom: 1rem;
}

ul.list li{
    margin-bottom: .3rem;
    font-size: .9rem;
    color: $darkText;
}

div.logo-item{
    height: 100%;
    width: 563px;
    background-image: url('../assets/images/img/dc-logo-bg.png');
    background-repeat: no-repeat;
    background-position: center;
}

div.lower-side{
    display: flex;
    justify-content: center;
    background-color: $greyBG;
    padding: 2.6rem;
}

div .lower-footer{
    width: 1100px;
    @include centering(space-between, center);
    display: flex;
    color: $whiteText;
}

div .sign-up{
    padding: 1rem;
    border: 2px solid $lightblue;
}

h2.follow{
    color: $lightblue;
    align-items: center;
    display: flex;
}

.social-side{
    width: 40%;
    justify-content: space-between;
}

div .social-icon{
    width: 55%;
    justify-content: space-around;
    display: flex;
}


</style>