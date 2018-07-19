<template>
<div class="container">
    <div class="de" @click="bindViewTap">
        测试
    </div>
</div>
</template>

<script>
export default {
    methods: {
        bindViewTap() {
            const url = '../logs/main'
            wx.navigateTo({ url })
        }
    }
}
</script>

<style lang="scss">
.container {
    .de {
        color: red;
    }
}
</style>
