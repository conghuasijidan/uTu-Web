<template>
    <nav class="navgation" >
        <img src="../images/nav_logo.png" class="logo">
        <div class="navButton first" ><a  href="#row1" id="a1">首页</a></div>
        <div class="navButton" ><a href="#row2" id="a2">旅行纪念</a></div>
        <div class="navButton" ><a href="#row3" id="a3">旅行管家</a></div>
        <div class="navButton" ><a href="#row4" id="a4">关于我们</a></div>
        <div class="navButton" ><a href="#row5" id="a5">成为途友</a></div>
        <div class="last" >
            <!--<a href="#" id="a6">请登录</a>-->
            <div class="avatarView">
                <img src="../images/avatar.png" class="avatarimg">
                <span>接地气啊</span>
                <div class="arrowimg"></div>
            </div>
            <div class="submenu">
                <ul>
                    <li>旅行纪念订单</li>
                    <li>旅行管家订单</li>
                    <li>设置</li>
                    <li>退出</li>
                </ul>
            </div>
        </div>
    </nav>
</template>
<script>
    importScripts('../js/jquery-3.2.1.min.js')

    export default {
        data () {

        },
        methods:{

        },
        computed: {
            upper () {
                return this.msg.toUpperCase();
            }
        }
    }

</script>
<style lang="scss" scoped>
 @import "../css/navigation.css";

</style>