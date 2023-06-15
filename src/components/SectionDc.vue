<script>

export default{
    name: 'AppSection',
    data(){
        return{

        }
    }
}
</script>

<template>
    <section>
        <div class="main-section">
            <div class="item-container flex">
                <img src="../assets/images/img/buy-comics-digital-comics.png" alt="Digital Comics">
                <p>
                    DIGITAL COMICS 
                </p>
            </div>
            <div class="item-container flex">
                <img src="../assets/images/img/buy-comics-merchandise.png" alt="DC Merchandise">
                <p>
                    DIGITAL COMICS 
                </p>
            </div>
            <div class="item-container flex">
                <img src="../assets/images/img/buy-comics-subscriptions.png" alt="Subscription">
                <p>
                    DIGITAL COMICS 
                </p>
            </div>
            <div class="item-container flex">
                <img src="../assets/images/img/buy-comics-shop-locator.png" alt="Comic Shop Locator">
                <p>
                    DIGITAL COMICS 
                </p>
            </div>
            <div class="item-container flex">
                <img src="../assets/images/img/buy-dc-power-visa.svg" alt="DC Power Visa">
                <p>
                    DIGITAL COMICS 
                </p>
            </div>
        </div>

    </section>
</template>

<style lang="scss">

@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

section{
    display: flex;
    height: 160px;
    background-color:$lightblue;
    display: flex;
    @include centering(center, center);
    color: $whiteText;
    font-size: .9rem;
}

div.main-section{
    width: 1100px;
    display: flex;
    justify-content: space-around;
}

div.item-container img{
    width: 1100px;
    width: 42px;
    height: 50px;
}

div.item-container p{
    align-items: center;
    display: flex;
    margin-left: 1rem;
}


</style>