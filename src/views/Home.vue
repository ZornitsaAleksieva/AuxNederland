<template>

  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

@Options({
  components: {
    HelloWorld,
  },
})
export default class Home extends Vue {}
</script>

<style scoped>
.home {
  padding-top: 5rem;
  padding-bottom: 5rem;
  background: rgb(78,60,78);
  background: linear-gradient(0deg, rgba(78,60,78,1) 12%, rgba(69,59,105,1) 100%);
}
</style>
