<script>
export default {
    name:'Inputcomponent',
    props:{
        text:{
            type:String,
            required:true
        }
    },
    computed:{
        inputText:{
            get(){
                return this.text
            },
            set(val){
                // console.log(val)
                this.$emit('update:text',val)
            }
        }
    }
}
</script>


<template src='./template.html'></template>
<style src='./style.css' scoped></style>