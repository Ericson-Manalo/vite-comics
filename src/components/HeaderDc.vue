<script>

export default{
    name: 'AppHeader',
    data(){
        return{
            navbarLinks:[
                {
                    text: 'Characters',
                    active: false
                },
                {
                    text: 'Comics',
                    active: true
                },
                {
                    text: 'Movies',
                    active: false
                },
                {
                    text: 'Tv',
                    active: false
                },
                {
                    text: 'Games',
                    active: false
                },
                {
                    text: 'Collectibles',
                    active: false
                },
                {
                    text: 'Videos',
                    active: false
                },
                {
                    text: 'Fans',
                    active: false
                },
                {
                    text: 'News',
                    active: false
                },
                {
                    text: 'Shop',
                    active: false
                }

        ]
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
                <li v-for="link in navbarLinks" :class="link.active ? 'active' : ''">
                    {{ link.text }}
                </li>

            </ul>
        </nav>
        </div>

        
    </header>
</template>

<style lang="scss" scoped>

@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;


header{
    display: flex;
    justify-content: center;

    div.header-section{
        width: 1200px;
        height: 100px;
        @include centering(space-between, center);
    }
}

div.header-section img{
    width: 75px;
    height: 75px;
}

nav{
    height: 100%;
}

nav ul{
    display: flex;
    height: 100%;
    align-items: center;
}

ul li{
    height: 100%;
    align-items: center;
    display: flex;
    border-bottom: 3px solid white;
    cursor:pointer;
}

nav ul li.active{
    color: $lightblue;
    border-bottom: 3px solid $lightblue;

}


li:active{
    color: $lightblue;
    border-bottom: 3px solid $lightblue;
    }

</style>