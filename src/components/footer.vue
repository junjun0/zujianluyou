<template>
        <div class="container index">
            <div class="row"></div>
                <div class="col-xs-7 col-xs-offset-1 aside">
                    <div class="board">
                        <a href="">
                            <img src="" alt="">
                        </a>
                    </div>
            </div>
        </div>
</template>
<script>
export default {
     name:'footer',
  


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
    border: 1px solid red;
}
.row {
    margin-left: -15px;
    margin-right: -15px;
}
.index .aside {
    float: right;
    border: 1px solid red;
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
</style>
