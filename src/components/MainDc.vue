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
    </main>
</template>

<style lang="scss" scoped>
@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

main{
    background-color: $darkBg;

    div.main-content{
        display: flex;
        justify-content: center;
        padding: 3rem 0;
    }
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


</style>