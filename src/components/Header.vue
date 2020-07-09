<template>

    <div class="header">
        <img alt="" src="../assets/cnodejs_light.svg">
        <ul>
            <li><a href="#">首页</a></li>
            <li><a href="#">入门</a></li>
            <li><a href="#">API</a></li>
            <li><a href="#">关于</a></li>
            <li><a href="#">注册</a></li>
            <li><a href="#">登录</a></li>
        </ul>
    </div>
</template>

<script lang="ts">
    export default {
        name: 'Header'
    };
</script>

<style>
    * {
        margin: 0px;
        padding: 0px;
        box-sizing: border-box;
    }

    ol,
    ul {
        list-style: none;
    }

    a {
        text-decoration: none;
    }

    .header {
        background-color: #5a5555;
        height: 50px;
    }

    .header img {
        max-height: 100px;
        max-width: 120px;
        margin-left: 50px;
        margin-top: 8px;
    }

    .header ul {
        float: right;
        margin-right: 50px;
    }

    .header ul li {
        display: inline-block;
        padding: 16px 8px;

    }

    .header ul li a {
        color: #cccccc;
        font-size: 16px;
        text-shadow: none;
    }
</style>