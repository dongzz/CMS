<template>
  <div>
    <router-view></router-view>
  </div>
</template>

<script>
export default {

  data() {
    return {
      name: 'app'
    }
  },
  methods: {

    },
  created: function() {
  }
}
</script>

<style>
  * {
    -webkit-user-select:text;
  }
</style>
