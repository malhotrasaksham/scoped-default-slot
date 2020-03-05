<template>
  <div id="app">
    <h3>Hi</h3>
    <HelloWorld #default="{message}">
      This is the custom content passed on
      from parent with message from child: {{message}}
    </HelloWorld>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
}
</style>
