<template>
  <div>
    <h1>element-cooking-starter</h1>
    <p>Use Vue 2.0 Today!</p>
    <el-button @click.native="startHacking">Let's do it</el-button>
  </div>
</template>

<script>
  export default {
    name: 'app',

    methods: {
      startHacking() {
        this.$notify({
          title: 'It Works',
          message: 'We have laid the groundwork for you. Now it\'s your time to build something epic!',
          duration: 6000
        });
      }
    }
  };
</script>
