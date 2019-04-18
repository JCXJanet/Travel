<template>
    <div class="wrapper">
        <swiper :options="swiperOption">
<<<<<<< HEAD
            <!-- slides -->
            <swiper-slide v-for="item of swiperList" :key="item.id">
                <img class="swiper-img" :src="item.imgUrl" />
            </swiper-slide>
            <!-- Optional controls -->
            <div class="swiper-pagination"  slot="pagination"></div>
            <!--轮播左右箭头-->
            <!--<div class="swiper-button-prev" slot="button-prev"></div>
            <div class="swiper-button-next" slot="button-next"></div>-->
            <!--阴影-->
            <!--<div class="swiper-scrollbar"   slot="scrollbar"></div>-->
=======
            <swiper-slide v-for="item of swiperList" :key="item.id">
                <img class="swipe-img" :src="item.imgUrl" />
            </swiper-slide>
            <!-- Optional controls -->
            <div class="swiper-pagination"  slot="pagination"></div>
>>>>>>> origin/index-icon
        </swiper>
    </div>
</template>

<script>
export default {
  name: 'HomeSwiper',
  data () {
    return {
      swiperOption: {
        pagination: '.swiper-pagination',
        loop: true
      },
      swiperList: [{
<<<<<<< HEAD
        id: '0001',
        imgUrl: 'http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20194/389d0194766566f8f1185aa19b759c25.jpg_750x200_22620261.jpg'
      }, {
        id: '0002',
=======
        id: '001',
        imgUrl: 'http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20194/389d0194766566f8f1185aa19b759c25.jpg_750x200_22620261.jpg'
      }, {
        id: '002',
>>>>>>> origin/index-icon
        imgUrl: 'http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20194/9f39c398e63315d7375efd08028f040e.jpg_750x200_4f536dd8.jpg'
      }]
    }
  }
}
</script>

<style lang="stylus" scoped>
    .wrapper >>> .swiper-pagination-bullet-active
<<<<<<< HEAD
      background : #fff
    .wrapper
      overflow : hidden
      width : 100%
      /*height : 26.67vw*/
      height: 0
      padding-bottom : 26.67%
      background : #eee
      .swiper-img
=======
        background: #fff
    .wrapper
        overflow : hidden
        width : 100%
        height : 0
        padding-bottom : 26.67%
        background : #eee
      .swipe-img
>>>>>>> origin/index-icon
        width : 100%
</style>
