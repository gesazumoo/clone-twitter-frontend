<template>
  <div id="app">
    <div>{{ msg }}</div>
    <button :disabled="isButtonDisabled">button</button>
    {{ 1 + 1 }}
    {{ "msg : " + msg }}
    {{ true ? "true" : "not" }}
  </div>
</template>

<script>
export default {
  name: "App",
  components: {},
  data() {
    return {
      msg: "Hello, Vue!",
      isButtonDisabled: false,
    };
  },
};
</script>

<style></style>
