<template>
  <div>{{xx}}</div>
</template>
<script lang="ts">
import { Component, Vue, Prop } from "vue-property-decorator";

@Component
export default class TestComponent extends Vue {
  @Prop({ type: String }) post!: "{ a: 1 }";
  private xx = 1;
  constructor() {
    super();
  }
  //   this.
}
</script>


