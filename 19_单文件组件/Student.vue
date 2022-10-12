<template lang="pug">
      <div>
            <h2>学生名称:{{ studentName }}</h2>
            <h2>学校年龄:{{ age }}</h2>
         <button @click="showName">点我提示学生名</button>
     </div>
</template>
<script>
export default {
    name:'Student',
    data() {
        return {
            schoolName:'武汉大学',
            age: 18
        }
    },
    methods:{
        showName(){
            alert(this.studentName)
        }
    }
}
</script>
<style>

</style>