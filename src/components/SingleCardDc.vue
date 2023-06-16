<template lang="">
    <article>
        <div class="card-container">
            <img :src="cardElement.thumb" alt="DC Cards" class="card">
            <h3>
            {{cardElement.series}}
            </h3>
        </div>
        
    </article>
    

</template>
<script>
export default {
    name: 'SingleCardDc',
    props: [
        'cardElement'
    ]
}
</script>
<style lang="scss" scoped>

@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

    article{
        width: calc(100% / 6);
    }

    img{
        width: 170px;
        height: 170px;
        margin-top: 1rem;
    }

    div.card-container h3{
        padding-top: .8rem;
        color: $whiteText;
        text-transform: uppercase;
        font-weight: 400;
        font-size: .8rem;

    }
</style>