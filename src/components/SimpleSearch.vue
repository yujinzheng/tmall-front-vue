<template>
    <div id="simpleSearch">
        <span class="icon iconfont icon-tmalltianmaotmall-logo redColor"></span>
        <div class="search">
            <input type="text" placeholder="平衡车    榨汁机" name="keyword">
            <button class="searchButton" type="submit">搜天猫</button>
            <div class="searchBelow">
                <span><a href="#nowhere">冰箱</a>|</span>
                <span><a href="#nowhere">空调</a>|</span>
                <span><a href="#nowhere">女表</a>|</span>
                <span><a href="#nowhere">男表</a></span>
            </div>
        </div>
    </div>
</template>

<script setup>
import '../assets/iconfont/iconfont.js'
</script>
<style scoped>
    .icon {
        position: absolute;
        font-size: 30px;
        left: 0px;
    }

    .redColor {
        color: #C40000 !important;
    }

    div.search {
        /* background-color: #C40000; */
        width: 400px;
        float: right;
        padding: 1px;
        /* height: 42px; */
    }

    a {
        text-decoration: none;
        color: #999;
    }

    a:hover {
        color: #C40000 !important;
    }

    div.search input {
        width: 274px;
        height: 36px;
        border: 2px solid transparent;
        border-color: #C40000;
        vertical-align: top
    }

    div.search button {
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
        margin-left: -140px;
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
