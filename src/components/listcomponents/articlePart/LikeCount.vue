<template>
    <span class="likes">
        <i class="icon iconfont icon-aixin"></i>
        <em>
            <slot></slot>
        </em>
    </span>
</template>

<script>
export default {
    name:'',
    data () {
        return {
        };
    },
}

</script>

<style scoped>
.likes{
    margin-right: 10px;
    font-size: 12px;
    color:#999;
}
.icon{
    font-size: 10px;
    margin-right: 3px;
}
</style>