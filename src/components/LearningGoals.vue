<template>
  <b-container>
    <b-row>
      <b-col>
        <h4 class="aligner">
          Our courses are designed to help you improve your
          <span class="highlight">problem-solving abilities </span> and develop
          a more rational approach to
          <span class="highlight">decision making</span> . Throughout the
          program, you'll learn:
        </h4>
        <b-list-group>
          <b-list-group-item variant="success"
            >How to identify and clarify your goals to determine an effective
            course of action</b-list-group-item
          >
          <b-list-group-item variant="success"
            >How to be clear about the reasons behind what we believe or want
            other to believe</b-list-group-item
          >
          <b-list-group-item variant="success"
            >How to identify and avoid common cognitive biases and fallacies in
            order to improve the quality of our heuristics</b-list-group-item
          >
          <b-list-group-item variant="success"
            >How to make better decisions under uncertainty</b-list-group-item
          >
        </b-list-group>
      </b-col>
    </b-row>
    <hr />
    <b-row class="mb-5">
      <b-col>
        <h4 class="aligner">
          By the end of these courses, you'll have learned a variety of
          practical skills and effective strategies to
          <span class="highlight"
            >confidently overcome personal and professional challenges.</span
          >
          You'll be better equipped to:
        </h4>
        <b-list-group>
          <b-list-group-item variant="success"
            >Make more informed decisions</b-list-group-item
          >
          <b-list-group-item variant="success"
            >Develop more accurate beliefs about the world i.e. make your map
            closer to territory</b-list-group-item
          >
          <b-list-group-item variant="success"
            >Make more realistic goals, with clarity on how to achieve them
          </b-list-group-item>
          <b-list-group-item variant="success"
            >Build better personal systems including habits and
            rituals.</b-list-group-item
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
  color: #fdab14;
  font-weight: bold;
}
</style>
