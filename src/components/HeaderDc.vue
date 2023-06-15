<script>

export default{
    name: 'AppHeader',
    data(){
        return{

        }
    }
}
</script>

<template>
    <header>
        <div class="header-section">
            <img src="../assets/images/img/dc-logo.png" alt="Dc Main Logo">
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
        </div>

        
    </header>
</template>

<style lang="scss">

@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;


    header{
        display: flex;
        justify-content: center;
    
        div.header-section{
            width: 1100px;
            height: 100px;
            @include centering(space-between, center);
        }

    }

    div.header-section img{
        width: 75px;
        height: 75px;
    }

    nav ul{
        display: flex;
    }

</style>