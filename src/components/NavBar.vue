<template>
  <div>
    <nav class="navbar navbar-expand-sm ml-3">
      <span class="title">Socratic Compass</span>
      <!-- <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" href="#about">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#course">Course</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#testimonials">Testimonials</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#signup">Sign Up</a>
        </li>
      </ul> -->
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.navbar {
  background-color: transparent;
  margin-left: 2rem;
  transition: background-color 0.5s ease-in-out;
}

.navbar.scrolled {
  background-color: #343a40;
}
.title {
  background-image: linear-gradient(to right, #e91e63, #9c27b0);
  font-size: 22px;
  font-weight: bold;
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>
