<template>
<div>
sasjhaja    
</div>    
</template>
<script>
// import headerTop from './common/headerComponent'
// import homeTestimonial from './common/homeTestimonial'
// import footerBottom from './common/footerComponent'
// import howItWorks from './howItWorks'
// import happinessComponent from './happinessComponent'
// import {
//     mapState,
//     mapActions,
//     mapGetters,
//     mapMutations
// } from 'vuex';
export default {
    // components:{
    //     headerTop,
    //     homeTestimonial,
    //     footerBottom,
    //     howItWorks,
    //     happinessComponent
    // },
   data(){
       return {
           selectedWidth:'8',
           selectedHeight:'8',
           radioSelect: '8x8',
           dynamicPrice: '',
           showLogOutButton: false,
           optionHeight: [],
           optionWidth: [],
           
       }
   },
   head () {
    return {
      title: 'about',
      meta: [
        // hid is used as unique identifier. Do not use `vmid` for it as it will not work
        { hid: 'description', name: 'description', content: 'My custom description' }
      ]
    }
  },
  }
</script>