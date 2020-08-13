<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
    <Card msg="This is a card" />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import HelloWorld from '@/components/HelloWorld.vue'
import Card from '@/components/Card.vue'

@Component({
  components: {
    HelloWorld,
    Card
  }
})
export default class Home extends Vue {}
</script>
