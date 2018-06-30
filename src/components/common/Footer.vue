<template>
    <ul class="footer" :style="{background:bgColor}">
        <li><router-link to='/'>电影</router-link></li>
        <li><router-link to='/music'>音乐</router-link></li>
        <li><router-link to='/book'>书籍</router-link></li>
        <li><router-link to='/photo'>图片</router-link></li>
    </ul>
</template>

<script>
    export default{
        props: ['bgColor']
    }
</script>

<style scoped>

.footer{
    height:1rem;
    line-height:1rem;
    background: rgb(33,150,243);
    color:#fff;
    position:fixed;
    bottom:0;
    width:100%;
    line-height:1rem;
    display:flex;
}
.footer li{
    flex-grow:1;
    text-align: center;
    color:#ccc;
}
</style>

