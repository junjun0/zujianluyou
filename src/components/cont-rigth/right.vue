<template>
        <div class="container index">
            <div class="row">
                <div class="col-xs-7 col-xs-offset-1 aside">
                    <div class="board">
                        <a href="">
                            <img src="./images/jshy.png" alt="">
                        </a>
                        <a href="">
                            <img src="./images/yxlz.png" alt="">
                        </a>
                        <a href="">
                            <img src="./images/jsbq.png" alt="">
                        </a>
                        <a href="">
                            <img src="./images/jsdxt.png" alt="">
                        </a>
                    </div>
                        <a class="col-xs-8 download" href="">
                            <img class="qrcode" src="./images/ewm.png" alt="">
                            <div class="info">
                                <div class="title">下载简书手机App<i class="el-icon-arrow-right"></i></div>
                                <div class="description">随时随地发现和创作内容</div>
                            </div>
                            
                        </a>
                        <div class="recommended-author-wrap">
                            <a class="youdao-img-ad ad-1" href="">
                                <span class="ad-badge">广告</span>
                            </a>
                            <div class="recommended-authors">
                                <div class="title">
                                    <span>推荐作者</span>
                                    <a class="page-change" href="">
                                        <i class="el-icon-refresh iconfont"></i>换一批
                                    </a>
                                </div>
                                <ul class="list">
                                    <li>
                                        <a href="" class="avatar">
                                            <img src="./images/p1.webp" alt="">
                                        </a>
                                        <a href="" class="follow">
                                            <i class="el-icon-plus"></i>关注
                                        </a>
                                        <a class="name" href="">
                                            穿着prada挤地铁
                                        </a>
                                        <p>写了357.9k字 · 4.4k喜欢</p>
                                    </li>
                                     <li>
                                        <a href="" class="avatar">
                                            <img src="./images/p2.webp" alt="">
                                        </a>
                                        <a href="" class="follow">
                                            <i class="el-icon-plus"></i>关注
                                        </a>
                                        <a class="name" href="">
                                            北美之北
                                        </a>
                                        <p>写了409.6k字 · 28.9k喜欢</p>
                                    </li>
                                     <li>
                                        <a href="" class="avatar">
                                            <img src="./images/p3.webp" alt="">
                                        </a>
                                        <a href="" class="follow">
                                            <i class="el-icon-plus"></i>关注
                                        </a>
                                        <a class="name" href="">
                                            梅拾璎
                                        </a>
                                        <p>写了263.7k字 · 24.7k喜欢</p>
                                    </li>
                                     <li>
                                        <a href="" class="avatar">
                                            <img src="./images/p4.webp" alt="">
                                        </a>
                                        <a href="" class="follow">
                                            <i class="el-icon-plus"></i>关注
                                        </a>
                                        <a class="name" href="">
                                            遛遛心情的溜妈
                                        </a>
                                        <p>写了652.4k字 · 28.9k喜欢</p>
                                    </li>
                                     <li>
                                        <a href="" class="avatar">
                                            <img src="./images/p5.webp" alt="">
                                        </a>
                                        <a href="" class="follow">
                                            <i class="el-icon-plus"></i>关注
                                        </a>
                                        <a class="name" href="">
                                            老沈1
                                        </a>
                                        <p>写了88.3k字 · 522喜欢</p>
                                    </li>
                                </ul>
                                <a class="find-more" style="" href="">
                                    查看全部
                                    <i class="el-icon-arrow-right"></i>
                                </a>
                                <a class="youdao-img-ad ad-2" href="">
                                    <span class="ad-badge">广告</span>
                                </a>
                            </div>
                        </div>
                </div>
            </div>
        </div>
</template>

<script>
export default {
     name:'right',
  


};
</script>

<style>
*{
    box-sizing: border-box;
}
div {
    display: block;
}
.container {
    width: 960px;
    margin-right: auto;
    margin-left: auto;
    padding-left: 15px;
    padding-right: 15px;
}
.row {
    margin-left: -15px;
    margin-right: -15px;
}
.index .aside {
    float: right;
    padding: 30px 0 0;
}
.col-xs-offset-1 {
    margin-left: 4.16667%;
}
.col-xs-7 {
    width: 30%;
}
.aside .board {
    margin-top: -4px;
    padding-bottom: 4px;
    min-height: 228px;
}
.aside .board img {
    width: 100%;
    min-height: 50px;
    margin-bottom: 6px;
    border-radius: 4px;
}
img{
    vertical-align: middle;
    border: 0;
}
.aside .download {
    display: flex;
    margin-bottom: 30px;
    padding: 10px 22px;
    width: 100%;
    border: 1px solid #f0f0f0;
    border-radius: 6px;
    background-color: #fff;
}
.aside .download .qrcode {
    width: 60px;
    height: 60px;
    opacity: .85;
}
.aside .download .info {
    display: inline-block;
    vertical-align: middle;
    margin-left: 7px;
}
.download .info .title {
    font-size: 15px;
    color: #333;
}

.aside .download .info .description {
    margin-top: 4px;
    font-size: 13px;
    color: #999;
}
.youdao-img-ad {
    position: relative;
    border-radius: 4px;
    display: block;
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    height: 160px;
    width: 100%;
    margin-bottom: 20px;
    overflow: hidden;
    background-color: RGB(241, 243, 244);
}
.youdao-img-ad.ad-1 {   
    background-image: url(./images/bj1.jpg);
}
a{
    text-decoration: none;
        color: #333;
}
.youdao-img-ad .ad-badge {
    position: absolute;
    bottom: 0;
    right: 0;
    color: #fff;
    background-color: #000;
    padding: 0 5px;
    font-size: 12px;
    line-height: 20px;
    opacity: 0.7;
}
.recommended-authors {
    margin-bottom: 20px;
    padding-top: 0;
    font-size: 13px;
    text-align: center;
}
.recommended-authors .title {
    text-align: left;
}
.recommended-authors .title span {
    font-size: 14px;
    color: #969696;
}
.recommended-authors .title .page-change {
    float: right;
    display: inline-block;
    font-size: 14px;
    color: #969696;
}
.recommended-authors .list {
    margin: 0 0 20px;
    text-align: left;
    list-style: none;
}
ul {
    padding-left: 0;
}
.recommended-authors .list li {
    margin-top: 15px;
}
li {
    line-height: 20px;
}
.recommended-authors .list .avatar {
    float: left;
    width: 48px;
    height: 48px;
    margin-right: 10px;
}
.avatar {
    width: 24px;
    height: 24px;
    display: block;
    cursor: pointer;
}
.avatar img {
    width: 100%;
    height: 100%;
    border: 1px solid #ddd;
    border-radius: 50%;
}
.recommended-authors .list .follow{
    float: right;
    margin-top: 5px;
    padding: 0;
    font-size: 13px;
    color: #42c02e;
}
.recommended-authors .list .name {
    padding-top: 5px;
    margin-right: 60px;
    font-size: 14px;
    display: block;
}
.recommended-authors .list p {
    margin-top: 2px;
    font-size: 12px;
    color: #969696;
}
p {
    margin: 0 0 10px;
}
.recommended-authors .find-more{
    display: block;
    padding: 7px 7px 7px 12px;
    left: 0;
    width: 100%;
    font-size: 13px;
    color: #787878;
    background-color: #f7f7f7;
    border: 1px solid #dcdcdc;
    border-radius: 4px;
}
.youdao-img-ad.ad-2 {
    margin-top: 15px;
    background-image: url(./images/bj2.jpg)
}
</style>
