<script>

export default{
    name: 'Appmain',
    data(){
        return{

        }
    }
}

</script>

<template>
    <main>
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
    display: flex;
    justify-content: center;
    background-color: $darkBg;
    padding: 3rem;

    div.main-content{
        width: 1100px;
    }
}

h1{
    color: $whiteText;
}


</style>