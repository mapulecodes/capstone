<template>
  <div class="home-view">
    <header class="header">
      <div class="logo">
        <h1>Salon Inventory Management System</h1>
      </div>
    </header>

    <section class="hero">
      <div class="hero-content">
        <h2>Efficiently Manage Your Inventory</h2>
        <p>Track products, manage stock levels, and optimize your salon's operations.</p>
      </div>
    </section>

    <section id="features" class="features">
      <h3>Key Features</h3>
      <ul>
        <li>Real-time inventory tracking</li>
        <li>Product management</li>
        <li>Automated stock alerts</li>
        <li>Supplier management</li>
        <li>Comprehensive reporting</li>
      </ul>
    </section>

    <footer class="footer">
      <p>&copy; 2024 Salon Inventory Management System. All rights reserved.</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: "HomeView",
};
</script>

<style scoped>
.home-view {
  font-family: Arial, sans-serif;
  color: #333;
}

.header {
  background-color: #BAD6EB;
  padding: 20px;
  text-align: center;
}

.logo h1 {
  margin: 0;
  font-size: 2em;
}

.hero {
  background-color: #f4f4f4;
  padding: 50px 20px;
  text-align: center;
}

.hero-content h2 {
  margin-bottom: 10px;
  font-size: 1.8em;
}

.hero-content p {
  font-size: 1.2em;
}

.features {
  padding: 20px;
  background-color: #ffffff;
  text-align: center;
}

.features h3 {
  margin-bottom: 20px;
  font-size: 1.5em;
}

.features ul {
  list-style: none;
  padding: 0;
}

.features ul li {
  margin-bottom: 10px;
  font-size: 1.1em;
}

.footer {
  background-color: #BAD6EB;
  padding: 10px;
  text-align: center;
}
</style>
