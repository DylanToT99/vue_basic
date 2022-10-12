<template lang="pug">
      <div>
            <h2>学校名称:{{ schoolName }}</h2>
            <h2>学校地址:{{ address }}</h2>
         <button @click="showName">点我提示学校名</button>
     </div>
</template>
<script>
export default {
    name:'School',
    data() {
        return {
            schoolName:'武汉大学',
            address:'北京昌平'
        }
    },
    methods:{
        showName(){
            alert(this.schoolName)
        }
    }
}
</script>
<style>

</style>