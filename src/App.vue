<template>
  <div id="app">
    <form novalidate @submit.prevent="onSubmit">
      <input type="email" name="email" />
      <button>Sign up for newsletter</button>
    </form>
  </div>
</template>
<script>
export default {
  methods: {
    onSubmit() {
      console.log('Submitted');
    },
  },
};
</script>