<template>
  <div class="card">
    Message: {{ msg }}
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator'

@Component
export default class Card extends Vue {
  @Prop() public msg?: string;
}
</script>

<style lang="scss" scoped>
  .card {
    padding: 16px;
    background: white;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(black, 0.15);
  }
</style>