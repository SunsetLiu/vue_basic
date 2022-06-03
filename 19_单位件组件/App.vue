<template>
    <!-- 使用组件 -->
    <div>
        <School></School>
        <Student></Student> 
    </div>
</template>

<script>
// 引入组件
import School from './School'
import School from './School.vue'
import Student from './Student'
import Student from './Student.vue'
export default {
    name:'App',
    components:{
        School:School,
        Student:Student
    }
}
</script>