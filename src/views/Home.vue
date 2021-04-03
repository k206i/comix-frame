<template>
  <div class="home">
    <Header />
    <img alt="Vue logo" src="@/assets/images/png/logo.png">
    <HelloWorld msg="Empty template"/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import HelloWorld from '@/components/HelloWorld/HelloWorld.vue' // @ is an alias to /src
import Header from '@/components/Header/Header.vue'

@Component({
  components: {
    HelloWorld,
    Header
  }
})
export default class Home extends Vue {}
</script>
