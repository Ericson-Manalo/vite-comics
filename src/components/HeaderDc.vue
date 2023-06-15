<script>

</script>

<template>
    <header>
        <div class="logo">
            <img src="../assets/images/img/dc-logo.png" alt="Dc Main Logo">
        </div>

        <nav class="nav-bar">
            <ul>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>Tv</li>
                <li>Games</li>
                <li>Collectibles</li>
                <li>Videos</li>
                <li>Fans</li>
                <li>News</li>
                <li>Shop</li>
            </ul>
        </nav>
    </header>
</template>

<style lang="scss">

@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;
@import '../styles/general.scss';


    header{
        display: flex;
        justify-content: center;
    
        div.logo{
            width: 1100px;
            height: 100px;
            background-color: aqua;

            div.logo img{
                width: 100px;
                height: 100px;
            }
        }

    }

</style>