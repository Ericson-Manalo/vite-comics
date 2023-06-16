<script>
import CardsDc from './CardsDc.vue';

export default{
    name: 'MainDc',
    data(){
        return{

        }
    },
    components:{
        CardsDc
    }
}

</script>

<template>
    <main>
        <div class="jumbotron">
        </div>
        <div class="main-content">
            <CardsDc/>
        </div>

        <div class="load-btn">
            <p class="load-more">
                LOAD MORE
            </p>
        </div>

        <h2>
            CURRENT SERIES
        </h2>
    </main>
</template>

<style lang="scss" scoped>
@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

main{
    background-color: $darkBg;
    position: relative;

    div.main-content{
        display: flex;
        justify-content: center;
        padding: 3rem 0;
    }
}

h2{
    position: absolute;
    left: 20%;
    bottom: 64%;
    color: $whiteText;
    font-size: 1.6rem;
    background-color: $lightblue;
    padding: 1rem 1.5rem;
}


h1{
    color: $whiteText;
}

div.jumbotron{
    background-image: url('../assets/images/img/jumbotron.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    height: 300px;
}

div.load-btn{
    justify-content: center;
    display: flex;
    color: $whiteText;
    padding-bottom: 2rem;
}

div p.load-more{
    background-color: $lightblue;
    padding: 1rem 3rem;
    font-weight: bold;
}


</style>