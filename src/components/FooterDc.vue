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
                <div>
                    <h3>
                        DC COMICS
                    </h3>
                    <ul>
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
                    <ul>
                        <li>
                            Shop DC
                        </li>
                        <li>
                            Shop DC Collectibles
                        </li>
                    </ul>
                </div>

                <div>
                    <h3>
                        DC
                    </h3>
                    <ul>
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
                    <ul>
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
            <div>

            </div>
        </div>
        <div>

        </div>
    </footer>
</template>

<style lang="scss">

@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

footer{
    background-image: url('../assets/images/img/footer-bg.jpg');
    display: flex;
    justify-content: center;
    color: $whiteText;


}

footer div.upper-footer{
        width: 1100px;
}

div.list-item{
display: flex;
}



</style>