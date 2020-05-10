<template>
  <div>
    <p>{{ partner }}</p>
  </div>
</template>

<script>
export default {
  props: {
    partner: {
      required: true,
      type: Object
    }
  }
}
</script>

<style></style>
