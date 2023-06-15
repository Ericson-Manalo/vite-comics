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

                    <h3>
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
                <img src="../assets/images/img/dc-logo-bg.png" alt="">
            </div>
        </div>

        <div class="lower-footer">

        </div>
    </footer>
</template>

<style lang="scss">

@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

footer{
    background-image: url('../assets/images/img/footer-bg.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    justify-content: center;
    color: $whiteText;
    height: 380px;
}

footer div.upper-footer{
        width: 1100px;
        display: flex;
        justify-content: space-between;
        align-items: center;
}

div.list-item{
    display: flex;
}

div h3{
    padding-bottom: 1rem;
}

ul.list li{
    margin-bottom: .3rem;
    font-size: .8rem;
}

div.logo-item img{

}



</style>