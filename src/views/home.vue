<template>
    <div class="home-container">
        <h1>Vue3教学</h1>
        <hr>
        <Mobanyufa></Mobanyufa>
        <Shuxingbangding></Shuxingbangding>
        <Tiaojianxuanran></Tiaojianxuanran>
        <liebiaoxuanran></liebiaoxuanran>  
        <keyguanlizhuangtai></keyguanlizhuangtai> 
        <Shijianchuancan></Shijianchuancan>
    </div>
</template>


<script>
import Mobanyufa from '../components/mobanyufa.vue';
import Shuxingbangding from '../components/shuxingbangding.vue'
import Tiaojianxuanran from '../components/tiaojianxuanran.vue'
import liebiaoxuanran from '../components/liebiaoxuanran.vue';
import keyguanlizhuangtai from '../components/keyguanlizhuangtai.vue'
import Shijianchuancan from '../components/shijianchuancan.vue'

export default {
    name: 'home',
    components: {
        Mobanyufa,
        Shuxingbangding,
        Tiaojianxuanran,
        liebiaoxuanran,
        keyguanlizhuangtai,
        Shijianchuancan
    },
}
</script>

<style scoped>
.home-container {
    position: relative;
    z-index: 10;
}

h1 {
    z-index: 11;
    color: aqua;
}

</style>