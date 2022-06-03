<template>
    <div class = "demo">
        <h1>学校名称：{{name}}</h1>
        <h1>学校地址：{{address}}</h1>
        <button @click="showName">点我提示学校名</button>
    </div>
</template>

<script>
    export default {
        name:'School',
        date(){
            name:'发财大学'
            address:'广州'
        },
        methods:{
            showName(){
                alert(this.name)
            }
        }
    }
</script>

<style>
    .demo{
        background: green;
    }
</style>