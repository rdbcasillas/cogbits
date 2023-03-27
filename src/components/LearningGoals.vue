<template>
  <b-container>
    <b-row>
      <b-col>
        <h4 class="aligner">
          Our course is designed to help you improve your
          <span class="highlight">problem-solving abilities </span> and develop
          a more rational approach to
          <span class="highlight">decision making</span> . Throughout the
          program, you'll learn:
        </h4>
        <b-list-group>
          <b-list-group-item variant="primary"
            >How to identify and clarify your goals</b-list-group-item
          >
          <b-list-group-item variant="primary"
            >How to analyze and evaluate primaryrmation</b-list-group-item
          >
          <b-list-group-item variant="primary"
            >How to identify and avoid common cognitive biases and
            fallacies</b-list-group-item
          >
          <b-list-group-item variant="primary"
            >How to make better decisions under uncertainty</b-list-group-item
          >
        </b-list-group>
      </b-col>
    </b-row>
    <hr />
    <b-row class="mb-5">
      <b-col>
        <h4 class="aligner">
          By the end of the course, you'll have learned a variety of practical
          skills and effective strategies to
          <span class="highlight"
            >confidently overcome personal and professional challenges.</span
          >
          You'll be better equipped to:
        </h4>
        <b-list-group>
          <b-list-group-item variant="primary"
            >Make more primaryrmed decisions</b-list-group-item
          >
          <b-list-group-item variant="primary"
            >Develop more accurate beliefs about the world</b-list-group-item
          >
          <b-list-group-item variant="primary"
            >Identify and avoid common cognitive traps</b-list-group-item
          >
          <b-list-group-item variant="primary"
            >Stay focused on your goals and avoid
            distractions</b-list-group-item
          >
        </b-list-group>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.aligner {
  text-align: left;
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
  color: unset;
}
.list-group-item {
  text-align: left;
  font-size: 18px;
  font-weight: bold;
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
}
.highlight {
  color: #8b33f7;
  font-weight: bold;
}
</style>
