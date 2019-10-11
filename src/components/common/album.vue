<template>
<!--可复用的相册组件 这里只完成静态页面 不涉及数据-->
    <div class="album">
        <header id="wx-header">
            <div class="center">
                <router-link to="/self" tag="div" class="iconfont icon-return-arrow">
                    <span>我</span>
                </router-link>
                <span>相册</span>
            </div>
        </header>
        <div class="home-pic">
            <div class="home-pic-base">
                <div class="top-pic">
                    <div class="top-pic-inner">
                        <img src="http://106.15.237.176/images/touxiang.jpg">
                    </div>
                </div>
                <div class="top-name _ellipsis">晓时候</div>
            </div>
            <p class="sign">web前端</p>
        </div>
        <section class="album-box clearfix">
            <div class="post-date">
                <b class="day">12</b>
                <b class="month">3月</b>
            </div>
            <div class="post-content">
                <div class="tumb-box">
                    <img src="http://106.15.237.176/images/touxiang.jpg" alt="">
                    <img src="http://106.15.237.176/images/touxiang.jpg" alt="">
                    <img src="http://106.15.237.176/images/touxiang.jpg" alt="">
                </div>
                <div class="thumb-desc">
                    今天太阳挺好，今天太阳挺好，今天太阳挺好，今天太阳挺好，今天太阳挺好，今天太阳挺好，今天太阳挺好
                    <p class="number">共3张</p>
                </div>
            </div>
        </section>
        <section class="album-box clearfix">
            <div class="post-date">
                <b class="day">20</b>
                <b class="month">7月</b>
            </div>
            <div class="post-content">
                <div class="tumb-box">
                    <img src="http://106.15.237.176/images/touxiang.jpg" alt="">
                     <img src="http://106.15.237.176/images/touxiang.jpg" alt="">
                </div>
                <div class="thumb-desc">
                    提莫队长正在送命
                    <p class="number">共2张</p>
                </div>
            </div>
        </section>
        <section class="album-box clearfix">
            <div class="post-date">
                <b class="day">21</b>
                <b class="month">9月</b>
            </div>
            <div class="post-content">
                <div class="tumb-box">
                    <img src="http://106.15.237.176/images/touxiang.jpg" alt="">
                </div>
                <div class="thumb-desc">
                    断剑重铸之日，骑士归来之时
                    <p class="number">共1张</p>
                </div>
            </div>
        </section>
    </div>
</template>
<script>
    export default {}
</script>
<style>
    @import "../../assets/css/album.css";
</style>