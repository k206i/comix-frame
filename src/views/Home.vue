<template>
  <div class="home">
    <img alt="Vue logo" src="@/assets/images/png/logo.png">
    <HelloWorld msg="Empty template"/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import HelloWorld from '@/components/HelloWorld/HelloWorld.vue' // @ is an alias to /src

@Component({
  components: {
    HelloWorld
  }
})
export default class Home extends Vue {}
</script>
