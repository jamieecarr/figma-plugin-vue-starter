<template>
  <div>
    <div class="visual-bell">
      <span class="visual-bell__msg">{{ message }}</span>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: "Welcome to your new Figma Plugin"
    };
  }
};
</script>

<style lang="scss" scoped></style>
