<template>
  <div class="project-card d-flex justify-content-center">
    <div class="content">
      <h2 class="project-number">01</h2>
      <h3 class="project-title">Title</h3>
      <p class="project-description">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam blandit
        hendrerit efficitur. Nunc vel ex sed elit pulvinar placerat. Nullam
        velit neque, consequat eget mi vitae, sodales scelerisque elit.
      </p>
      <a class="project-more">Read More</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "ProjectCard",
};
</script>

<style scoped>
.project-card {
  background-color: white;
  border-radius: 10px;
  width: 450px;
  height: 250px;
  overflow: hidden;
  align-items: center;
  background-color: #1d1d1d;
  box-shadow: 0px 10px 10px rgba(0, 0, 0, 0.2);
}

.content {
  text-align: center;
  color: white;
}
</style>
