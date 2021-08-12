<template>
  <div class="page">
    <div class="partitions row g-0">
      <div
        class="left col-6 col-sm-6 col-md-6 col-lg-6 col-xl-6 col-xxl-6"
        style="background-color: blue"
      >
        B
      </div>
      <div
        class="right col-6 col-sm-6 col-md-6 col-lg-6 col-xl-6 col-xxl-6"
        style="background-color: green"
      >
        <div class="test" style="background-color: red">
          <div class="something" style="background-color: purple">YEEE</div>
        </div>
        <div class="test" style="background-color: yellow"></div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import navbar from "@/components/navbar.vue";

export default {
  name: "Home",
  components: {},
};
</script>

}

<style scoped>
.something {
  height: 60vh;
}

.test::-webkit-scrollbar {
  display: none;
}

.test {
  overflow-y: scroll;
  height: 50vh;
}
.left {
  min-height: 100vh;
}

.test {
  min-height: 50vh !important;
}
</style>
