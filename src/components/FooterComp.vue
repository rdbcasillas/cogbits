<template>
  <footer class="footer">
    <div class="container">
      <p>
        Copyright © {{ year }} Rational Rabbits
        <!-- Add any additional information here, such as links to terms of service, privacy policy, etc. -->
      </p>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
  data() {
    return {
      year: new Date().getFullYear(),
    };
  },
};
</script>

<style>
.footer {
  padding: 25px 0;
  text-align: center;
  font-size: 14px;
}
</style>
