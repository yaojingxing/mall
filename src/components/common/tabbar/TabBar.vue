<template>
    <div id="ap">
        <div id="tab-bar">
            <div class="tab-bar-item">home</div>
            <div class="tab-bar-item">category</div>
            <div class="tab-bar-item">home</div>
            <div class="tab-bar-item">home</div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "tabbar"
    }
</script>

<style scoped>
    #tab-bar{
        display:flex;
        background-color: #f6f6f6;
        position:fixed;
        left:0;
        right:0;
        bottom:0;
        box-shadow:10px -3px 1px rgba(100,100,100,.3)
    }
    .tab-bar-item{
        flex:1;
        text-align:center;
        height:49px;

    }
</style>