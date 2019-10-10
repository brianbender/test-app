<template>
  <div class="hello">
    <h1 :class="$style.title">{{ msg }}</h1>
  </div>
</template>

<script>
import { createWarehouse } from "@enlearn/warehouse";

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style lang="scss" module>
@import "../Globals";

.title {
  font: 700 $fontSizeBanner $accentFontFamily;
}
</style>
