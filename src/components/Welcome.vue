<template>
  <div>
    <div class="landing-page">
      <header>
        <h1>Tranquil Tides</h1>
        <nav>
          <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
          </ul>
        </nav>
      </header>
      <main>
        <h2>Welcome to Tranquil Tides Counseling</h2>
        <p>
          At Tranquil Tides, we believe that true healing begins with a safe and
          supportive environment, where you can explore your thoughts and
          feelings without judgment.
        </p>
        <p>
          Our approach is to listen carefully to your unique needs and concerns,
          and guide you towards your own solutions through compassionate support
          and evidence-based techniques.
        </p>
        <button>Get in touch</button>
      </main>
      <footer>
        <p>Tranquil Tides Counseling &copy; 2023</p>
      </footer>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.landing-page {
  background-color: #f5f5f5;
  font-family: sans-serif;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  background-color: #ffffff;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

header h1 {
  font-size: 36px;
  color: #336699;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav ul li {
  margin: 0 10px;
}

nav ul li a {
  text-decoration: none;
  color: #336699;
}

main {
  padding: 50px;
  text-align: center;
}

main h2 {
  font-size: 48px;
  color: #336699;
}

main p {
  font-size: 24px;
  line-height: 1.5;
  margin-bottom: 20px;
}

button {
  font-size: 24px;
  padding: 10px 20px;
  background-color: #336699;
  color: #ffffff;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.2s ease-in-out;
}

button:hover {
  background-color: #1c4a8c;
}

footer {
  text-align: center;
  padding: 20px;
  background-color: #ffffff;
  box-shadow: 0 -2px 4px rgba(0, 0, 0, 0.1);
}
</style>
