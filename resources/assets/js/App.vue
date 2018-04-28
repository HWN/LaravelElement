<template>
    <div>
        <h1>Hello, {{ msg }}!</h1>
        <router-view>
            <!--路由引入的组件将在这里被渲染-->
        </router-view>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                msg: 'Vue'
            }
        }
    }
</script>

<style>
</style>