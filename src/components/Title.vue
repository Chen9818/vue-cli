<template>
    <h1>My name is {{ title }}</h1>
</template>

<script>
export default {
    name:'Titlecomponent',
    // data(){
    //     return{
    //         title:'我是陳暐中'
    //     }
    // }
    props:{
        title:{
            type:String,
            required:true
        }
    }
}
</script>


<style scoped>
    h1{
        color: brown;
    }
</style>