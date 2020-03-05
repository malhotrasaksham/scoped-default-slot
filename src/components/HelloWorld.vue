<template>
  <div class="hello">
    <slot :message="message"></slot>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      message: "Hello Vue!"
    };
  }
};
</script>