<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Title :title="title"/>
    <Index v-model:text="title"/>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Title from '@/components/Title.vue'
import Index from '@/components/inputcomponent/index.vue'




export default {
  name: 'Home',
  data(){
    return{
      title:'Chen'
    }
  },
  components: {
    HelloWorld,
    Title,
    Index
  }
}
</script>
