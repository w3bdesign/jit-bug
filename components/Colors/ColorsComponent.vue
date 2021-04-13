<template>
  <div>
    <p v-for="(color, index) in colors" :key="index" :class="`bg-[${color}]`">
      {{ `Color ${index}` }}
    </p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      colors: ['#dc3d4b', '#477b1e', '#24649f', '#e6a708'],
    }
  },
}
</script>

<style></style>
