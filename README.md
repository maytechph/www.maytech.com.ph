/* ================================
   MAYTECH MODERN CREATIVE THEME
   ================================ /

:root {
  --main-color: #ff7a00;       / Vibrant Orange /
  --accent-color: #00c4ff;     / Electric Blue Accent /
  --text-color: #222222;       / Charcoal Text /
  --background-color: #ffffff; / Clean White /
  --light-gray: #f7f7f7;       / Section Background /
  --shadow-color: rgba(0, 0, 0, 0.15);
  --font-main: 'Poppins', sans-serif;
}

/ Global Styles /
body {
  font-family: var(--font-main);
  background-color: var(--background-color);
  color: var(--text-color);
  margin: 0;
  padding: 0;
  line-height: 1.6;
}

/ Header /
header {
  background: var(--main-color);
  color: #fff;
  padding: 15px 0;
  text-align: center;
  box-shadow: 0 2px 8px var(--shadow-color);
}

header h1 {
  margin: 0;
  font-size: 2rem;
  letter-spacing: 1px;
}

/ Navigation /
nav {
  background-color: var(--light-gray);
  text-align: center;
  padding: 10px 0;
}

nav a {
  color: var(--text-color);
  text-decoration: none;
  margin: 0 15px;
  font-weight: 600;
  transition: 0.3s;
}

nav a:hover {
  color: var(--main-color);
}

/ Hero Section /
.hero {
  background: linear-gradient(120deg, var(--main-color), var(--accent-color));
  color: #fff;
  text-align: center;
  padding: 80px 20px;
  border-radius: 0 0 40px 40px;
  box-shadow: 0 4px 15px var(--shadow-color);
}

.hero h2 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.2rem;
}

/ Buttons /
button, .btn {
  background-color: var(--main-color);
  color: #fff;
  border: none;
  padding: 12px 25px;
  border-radius: 30px;
  cursor: pointer;
  font-weight: bold;
  letter-spacing: 0.5px;
  box-shadow: 0 4px 10px var(--shadow-color);
  transition: all 0.3s ease;
}

button:hover, .btn:hover {
  background-color: var(--accent-color);
  transform: translateY(-2px);
}

/ Sections /
section {
  padding: 60px 20px;
  text-align: center;
}

section:nth-child(even) {
  background-color: var(--light-gray);
}

/ Cards / Products /
.product-card {
  background: #fff;
  border-radius: 12px;
  box-shadow: 0 4px 12px var(--shadow-color);
  margin: 20px;
  padding: 20px;
  display: inline-block;
  width: 250px;
  transition: 0.3s;
}

.product-card:hover {
  transform: scale(1.05);
}

.product-card img {
  width: 100%;
  border-radius: 10px;
}

.product-card h3 {
  margin-top: 15px;
  color: var(--main-color);
}

/ Footer */
footer {
  background-color: var(--text-color);
  color: #fff;
  text-align: center;
  padding: 20px 0;
  font-size: 0.9rem;
  margin-top: 50px;
}

footer a {
  color: var(--accent-color);
  text-decoration: none;
}
