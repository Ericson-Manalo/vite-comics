<script>
import HeaderDc from './components/HeaderDc.vue'
import MainDc from './components/MainDc.vue'
import SectionDc from './components/SectionDc.vue'
import FooterDc from './components/FooterDc.vue'

export default{
  name: 'App',
  components:{
    HeaderDc,
    MainDc,
    SectionDc,
    FooterDc
  }
}
</script>

<template>
  <HeaderDc/>
  <MainDc/>
  <SectionDc/>
  <FooterDc/>

</template>

<style lang="scss">
  @import './styles/general.scss';
</style>
