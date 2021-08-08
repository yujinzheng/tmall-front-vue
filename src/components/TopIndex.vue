<template>
    <nav class="top">
        <a href="#nowhere">
            <span class="icon iconfont icon-tmallhome2 redColor"></span>
            天猫首页
        </a>
        <span>喵，欢迎来到天猫</span>
        <a href="#nowhere">
            请登录
        </a>
        <a href="#nowhere">
            免费注册
        </a>
        <a href="#nowhere">
            <span class="icon iconfont icon-tmallgouwuche2 redColor"></span>
            购物车0件
        </a>
    </nav>
    <a id="logo" href="#nowhere">
        <img src="src\assets\logo.gif">
    </a>
    <div class="center">
        <input type="text" placeholder="时尚男鞋    太阳镜" name="keyword">
        <button class="searchButton" type="submit">搜索</button>
        <div class="searchBelow">
            <span><a href="#nowhere">平衡车</a>|</span>
            <span><a href="#nowhere">扫地机器人</a>|</span>
            <span><a href="#nowhere">原汁机</a>|</span>
            <span><a href="#nowhere">冰箱</a></span>
        </div>
    </div>
</template>

<style scoped>
    a {
        text-decoration: none;
        color: #999;
    }

    nav.top {
        font-size: 12px;
        font-family: Arial;
        background-color: #f2f2f2;
        padding-top: 5px;
        padding-bottom: 5px;
        border-bottom: 1px solid #e7e7e7;
    }

    nav.top span, nav.top a {
        color: #999;
        margin: 0px 10px
    }

    .redColor {
        color: #C40000 !important;
    }

    a:hover {
        color: #C40000 !important;
    }

    #logo {
        position: absolute;
        left: 0px;
        top: 100px;
        z-index: -1;
    }

    div.center {
        /* background-color: #C40000; */
        width: 400px;
        margin: 50px auto;
        padding: 1px;
        /* height: 42px; */
    }

    div.center input {
        width: 274px;
        height: 36px;
        border: 2px solid transparent;
        border-color: #C40000;
        vertical-align: top
    }

    div.center button {
        height: 42px;
        background-color: #C40000;
        border: 1px solid transparent;
        color: white;
        font-size: 20px;
        font-weight: bold;
        width: 110px;
        padding: 0px;
        vertical-align: top
    }

    div.searchBelow {
        margin-top: 3px;
        margin-left: -75px;
    }

    div.searchBelow span {
        color: #999;
    }

    div.searchBelow a {
        display: inline-block;
        padding: 0px 20px 0px 20px;
        font-size: 14px;
    }
</style>
