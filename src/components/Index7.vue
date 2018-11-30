<template>
    <div>
        <vue-banner01a></vue-banner01a>
        <vue-marquee></vue-marquee>
        <vue-newlists8></vue-newlists8>
    </div>
</template>
<script>
    import marquee from './../components/marquee01';
    import newlists8 from './../components/newlists8';
    import banner01a from './../components/banner01_a';
    export default {
        data() {
            return {
                bdTokenUrl: 'http://tiyu.baidu.com/home' //https://m.sporttery.cn/app/zf/fb/livelist.html  https://m.sporttery.cn/app/zf/fb/livelist.html http://m.sporttery.cn/wap/dtc/fb_league_europe.html
            }
        },
        // created() {
        //     this.getUrl();
        //     this.$nextTick(()=>{
        //         this.getCode();
        //     });
        // },
        mounted(){

        },
        components: {
         'vue-marquee':marquee,
         'vue-newlists8':newlists8,
         'vue-banner01a':banner01a,
        },
    }
</script>

<style lang="scss" scoped>
@import "scss/base.scss";
.child-view{
    height:100%;
}
.iftop05{
    height: 100%;
    margin-top:-83px;
    margin-bottom:60px;
}
</style>