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
</template>

<style scoped>
    a {
        color: #999;
        text-decoration: none;
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
</style>
