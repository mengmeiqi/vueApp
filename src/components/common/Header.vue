<template>
    <div>
        <div class="header" :style="{background:bgColor}">
            <span class="home">首页</span>
            <h2 class="title">
                <slot name="title">默认值</slot>
            </h2>
        </div>
    </div>
</template>

<script>
    export default{
        props: ['bgColor']
    }   
</script>

<style scoped>
.header{
    height:1rem;
    line-height:1rem;
    position:fixed;
    width:100%;
} 
.title{
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(-50%,-50%);
}
.home{
    color:#fff;
}
</style>