@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');

body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background-color: #0f0f0f;
  color: #ffffff;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: auto;
}

header {
  background: rgba(0,0,0,0.9);
  padding: 20px 0;
  position: sticky;
  top: 0;
  z-index: 1000;
}

header h1 {
  margin: 0;
  font-weight: 600;
  letter-spacing: 1px;
}

nav a {
  color: #ffffff;
  margin-left: 20px;
  text-decoration: none;
  font-weight: 400;
  transition: 0.3s;
}

nav a:hover {
  color: #c00000;
}

.hero {
  background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)),
              url('https://images.unsplash.com/photo-1502877338535-766e1452684a');
  background-size: cover;
  background-position: center;
  padding: 140px 0;
  text-align: center;
}

.hero h2 {
  font-size: 48px;
  font-weight: 700;
}

.hero p {
  font-size: 18px;
  margin-top: 20px;
  opacity: 0.9;
}

.btn {
  display: inline-block;
  padding: 14px 30px;
  margin-top: 30px;
  background: #c00000;
  color: #fff;
  text-decoration: none;
  border-radius: 30px;
  font-weight: 600;
  transition: 0.3s;
}

.btn:hover {
  background: #ff1a1a;
}

.section {
  padding: 80px 0;
}

.section h2 {
  text-align: center;
  margin-bottom: 40px;
  font-weight: 600;
}

ul {
  list-style: none;
  padding: 0;
  max-width: 700px;
  margin: auto;
}

ul li {
  padding: 12px 0;
  border-bottom: 1px solid #222;
}

.dark {
  background: #141414;
}

.cta {
  text-align: center;
  background: #000;
  padding: 100px 0;
}

.cta h2 {
  font-size: 32px;
}

footer {
  background: #000;
  text-align: center;
  padding: 20px 0;
  font-size: 14px;
  opacity: 0.6;
}

/* Floating Call Button */
.call-float {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: #c00000;
  color: white;
  padding: 15px 20px;
  border-radius: 50px;
  text-decoration: none;
  font-weight: 600;
  box-shadow: 0 4px 15px rgba(0,0,0,0.5);
}

