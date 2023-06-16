<script>

export default{
    name: 'Appmain',
    data(){
        return{

        }
    },
    components:{
        CardDc
    }
}

</script>

<template>
    <main>
        <div class="jumbotron">
        </div>
        <div class="main-content">
            <h1>
            - - Content goes here - -
            </h1>
        </div>
    </main>
</template>

<style lang="scss" scoped>
@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

main{
    background-color: $darkBg;

    div.main-content{
        width: 1100px;
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