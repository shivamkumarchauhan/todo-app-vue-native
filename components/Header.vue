<template>
    <view class="header">
        <text class="title"> {{ title }}</text>
    </view>
</template>

<script>
export default {
    props:['title']
}
</script>

<style>
    .header{
        height: 60px;
        background-color:rgb(0, 0, 0);
        justify-content: center;
        align-items: center;
    }

    .title{
        color: green;
        font-size: 30px;
        font-weight: 900;
        text-transform: uppercase;
    }
</style>