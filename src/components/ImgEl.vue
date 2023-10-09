<template>

</template>
import { defineComponent } from "vue"
<script>
export default defineComponent ({
  name: 'ImgEl',
  props: {
    svgdata: {
      type: String
    }
  },
  computed: {
    svgstr() {
      return this.svgdata || null
    }
  }
})
</script>
<style></style>