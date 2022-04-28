<template>
  <div class="header-contaner">

  </div>
</template>

<script>
export default {
  components: {
  },
  data() {
    return {
      searchText: ""
    };
  },
  methods: {
  }
};
</script>

<style lang="scss" scoped>
.header-contaner {
  position: fixed;
  left: 0;
  right: 0;
  top: 0;
  height: 80px;
  background: blue;
  max-width: 1920px;
  margin: 0 auto;
  z-index: 99;
}
</style>
