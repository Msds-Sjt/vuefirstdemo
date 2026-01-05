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
        <Shijianxiushifu></Shijianxiushifu>
        <Shuzubianhuazhence></Shuzubianhuazhence>
        <Jisuanshuxing></Jisuanshuxing>
        <Classbangding></Classbangding>
        <Stylebangding></Stylebangding>
        <Watchzhenting></Watchzhenting>
        <Shuxingbangding></Shuxingbangding>
        <mobanyinyong></mobanyinyong>
        <zujainqiantao></zujainqiantao>
        <zujianchuanzhiprops></zujianchuanzhiprops>
        <propsjiaoyanA></propsjiaoyanA>
        <zujianshijian></zujianshijian>
        <zujianshijianVmodel></zujianshijianVmodel>
        <chacaoslots></chacaoslots>
        <shengmingzhouqi></shengmingzhouqi>
        <shengmingzhouqiyingyong></shengmingzhouqiyingyong>
        <dongtaizujian></dongtaizujian>
        <yibuzujian></yibuzujian>
        <yilaizhuruparent></yilaizhuruparent>
    </div>
</template>


<script>
import Mobanyufa from '../components/mobanyufa.vue';
import Shuxingbangding from '../components/shuxingbangding.vue'
import Tiaojianxuanran from '../components/tiaojianxuanran.vue'
import liebiaoxuanran from '../components/liebiaoxuanran.vue';
import keyguanlizhuangtai from '../components/keyguanlizhuangtai.vue'
import Shijianchuancan from '../components/shijianchuancan.vue'
import Shijianxiushifu from '../components/shijianxiushifu.vue';
import Shuzubianhuazhence from '../components/shuzubianhuazhence.vue';
import Jisuanshuxing from '../components/jisuanshuxing.vue';
import Classbangding from '../components/classbangding.vue';
import Stylebangding from '../components/stylebangding.vue';
import Watchzhenting from '../components/watchzhenting.vue';
import Biaodanshujvbangding from '../components/biaodanshujvbangding.vue';
import mobanyinyong from '../components/mobanyinyong.vue';
import zujainqiantao from '../components/zujainqiantao.vue';
import zujianchuanzhiprops from '../components/zujianchuanzhiprops.vue';
import propsjiaoyanA from '../components/propsjiaoyanA.vue';
import zujianshijian from '../components/zujianshijian.vue';
import zujianshijianVmodel from '../components/zujianshijianVmodel.vue';
import chacaoslots from '../components/chacaoslots.vue';
import shengmingzhouqi from '../components/shengmingzhouqi.vue';    
import shengmingzhouqiyingyong from '../components/shengmingzhouqiyingyong.vue';
import dongtaizujian from '../components/dongtaizujian.vue';
import yibuzujian from '../components/yibuzujian.vue';
import yilaizhuruparent from '../components/yilaizhuruparent.vue';


export default {
    name: 'home',
    components: {
        Mobanyufa,
        Shuxingbangding,
        Tiaojianxuanran,
        liebiaoxuanran,
        keyguanlizhuangtai,
        Shijianchuancan,
        Shijianxiushifu,
        Shuzubianhuazhence,
        Jisuanshuxing,
        Classbangding,
        Stylebangding,
        Watchzhenting,
        Biaodanshujvbangding,
        mobanyinyong,
        zujainqiantao,
        zujianchuanzhiprops,
        propsjiaoyanA,
        zujianshijian,
        zujianshijianVmodel,
        chacaoslots,
        shengmingzhouqi,
        shengmingzhouqiyingyong,
        dongtaizujian,
        yibuzujian,
        yilaizhuruparent


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