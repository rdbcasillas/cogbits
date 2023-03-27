<template>
  <div class="hello">
    <!-- Banner -->
    <b-container fluid>
      <TopSection />
      <!-- About Section -->
      <hr />
      <AboutSection />
      <hr />
      <!-- Course Section -->
      <learning-goals />
    </b-container>
    <!-- Header section -->
  </div>
</template>

<script>
import TopSection from "./TopSection.vue";
import AboutSection from "./AboutSection.vue";
import LearningGoals from "./LearningGoals.vue";
export default {
  name: "HelloWorld",
  components: {
    TopSection,
    AboutSection,
    LearningGoals,
  },
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
