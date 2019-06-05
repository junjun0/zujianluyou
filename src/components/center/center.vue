<template>
    <div class="content">
        <div class="content_c">
            <div class="content_left">
                <ul>
                    <a href="">
                        <li>
                        <i class="el-icon-chat-square"></i>
                        <span>评论</span>
                        </li>
                    </a>
                    <a href=""><li>
                        <i class="el-icon-message"></i>
                        <span>简信</span>
                    </li></a>
                    <a href=""><li>
                        <i class="el-icon-upload2"></i>
                        <span>投稿和请求</span>
                    </li></a>
                    <a href=""><li>
                        <i class="el-icon-star-off"></i>
                        <span>喜欢和赞</span>
                    </li></a>
                    <a href=""><li>
                        <i class="el-icon-user"></i>
                        <span>关注</span>
                    </li></a>
                    <a href=""><li>
                        <i class="el-icon-coin"></i>
                        <span>赞赏和付费</span>
                    </li></a>
                    <a href=""><li>
                        <i class="el-icon-more"></i>
                        <span>其他提醒</span>
                    </li></a>  
                </ul>
            </div>


            <div class="conent_right">
                <div class="content_d">
                    <h1>全部简信</h1>
                    <div class="jianxin">
                        <div class="xinxi"></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'center',
}
</script>

<style>
*{
    padding: 0;
    margin: 0;
    font-family: "微软雅黑";
    box-sizing: border-box;
}
.content{
    width: 60%;
    border: 1px solid red;
    margin: 0 auto;
}
.content_c{
    padding-top: 30px;
    border: 1px solid red;
}
.content_left{
    float: left;
    width: 30%;
    border: 1px solid red;
}
.content_left ul{
    padding: 15px 0 0 8px;
    text-align: left;
    border: 1px solid red;
}
.content_left ul li{
    list-style: none;
    line-height: 50px;
}
.content_left ul li i{
  color: red;
  font-size: 30px;
}
.content_left ul li span{
    font-size: 16px;
    color: black;
    position: relative;
    top: -5px;
    margin-left: 20px;
}
a{
    text-decoration: none;
}
.conent_right{
    width: 70%;
    float: right;
    border: 1px solid red;
}
.content_d{
    width: 100%;
    margin-left: 5%;
}
.content_d h1{
    display: inline-block;
    font-size: 16px;
    float: left;
}
.title{
    width: 100%;
}

</style>
