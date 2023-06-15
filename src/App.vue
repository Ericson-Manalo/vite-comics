<script>
import HeaderDc from './components/HeaderDc.vue'
import MainDc from './components/MainDc.vue'
import FooterDc from './components/FooterDc.vue'

export default{
  name: 'App',
  components:{
    HeaderDc,
    MainDc,
    FooterDc
  }
}
</script>

<template>
  <HeaderDc/>
  <MainDc/>
  <FooterDc/>

</template>

<style lang="scss">
  @import './styles/general.scss';
</style>
