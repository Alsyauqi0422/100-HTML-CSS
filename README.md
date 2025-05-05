<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="author" content="Syauqi">
  <meta name="description" content="Website dengan Desain Keren">
  <meta name="keywords" content="HTML, CSS, modern, website">
  <title>Website Modern dengan 100 Tag HTML</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header class="hero">
    <div class="hero-content">
      <h1>Selamat Datang di Website Alsyauqi</h1>
      <p>Website ini dibuat dengan menggunakan desain yang keren</p>
      <a href="#about" class="btn-main">Jelajahi Sekarang</a>
    </div>
  </header>

  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section id="home" class="content-section">
    <h2>Home</h2>
    <h3>Hello It's Me</h3>
    <h1>Muh. Al Syauqi</h1>
    <h3>And I’m a <span>Junior Developer</span></h3>
    <p>Setiap ide memiliki potensi untuk menjadi sesuatu yang luar biasa. Dengan kreativitas, keterampilan, dan dedikasi, saya siap mengubah gagasan menjadi karya nyata yang bermakna.</p>
  </section>

  <section id="about" class="content-section">
    <h2>About</h2>
    <p>Selamat datang di website saya! Saya adalah mahasiswa dari program studi Bisnis Digital, dengan minat karier mendalam tentang Pemasaran Digital Marketing, Analisis Data dan Strategi Bisnis di era digital. Di sini, saya berbagi wawasan, pengalaman, serta perkembangan terbaru.</p>
    <img src="https://via.placeholder.com/600x300" alt="About Image" class="img-responsive">
  </section>

  <section id="services" class="content-section">
    <h2>Services</h2>
    <div class="service-cards">
      <div class="service-card">
        <h3>Web Design UI UX</h3>
        <p>Kami menyediakan solusi pengembangan website profesional, mulai dari landing page hingga sistem berbasis web yang kompleks, dengan desain modern dan performa tinggi..</p>
      </div>
      <div class="service-card">
        <h3>Design Grafis</h3>
        <p>Kami menyediakan layanan desain grafis kreatif untuk membantu Anda menyampaikan pesan dengan efektif dan menciptakan desain yang menarik dan berdampak untuk merek Anda.O.</p>
      </div>
      <div class="service-card">
        <h3>Stock Investment Analysis</h3>
        <p>Kami menganalisis tren pasar, laporan keuangan, dan strategi investasi berbasis data untuk membantu pengambilan keputusan yang lebih cerdas di dunia investasi saham.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="content-section">
    <h2>Contact</h2>
    <form>
      <label for="name">Nama:</label>
      <input type="text" id="name" name="name" required>
      
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      
      <label for="message">Pesan:</label>
      <textarea id="message" name="message" required></textarea>
      
      <button type="submit" class="btn-main">Kirim Pesan</button>
    </form>
  </section>

  <footer class="footer">
    <div class="footer-content">
      <p>&copy; 2025 Website Modern dengan menggunakan desain yang keren</p>
      <a href="@alsyauqi0422@gmail.com">alsyauqi0422@gmail.com</a>
    </div>
  </footer>

</body>
</html>


/* Global Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Roboto', sans-serif;
  line-height: 1.6;
  background-color:rgb(108, 156, 149);
  color: #333;
}

/* Hero Section */
.hero {
  background-image: url('https://via.placeholder.com/1500x600');
  background-size: cover;
  background-position: center;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: white;
  padding: 20px;
}

.hero-content h1 {
  font-size: 3rem;
  margin-bottom: 20px;
  font-weight: bold;
}

.hero-content p {
  font-size: 1.2rem;
  margin-bottom: 30px;
}

.btn-main {
  background-color: #ff5f57;
  color: white;
  padding: 15px 30px;
  text-decoration: none;
  font-size: 1.2rem;
  border-radius: 50px;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
  transition: background-color 0.3s ease;
}

.btn-main:hover {
  background-color: #e54b47;
}

/* Navigation */
nav {
  background-color: #333;
  position: sticky;
  top: 0;
  z-index: 1000;
}

nav ul {
  display: flex;
  justify-content: center;
  list-style: none;
  padding: 10px 0;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  text-decoration: none;
  color: white;
  font-size: 1.2rem;
  transition: color 0.3s;
}

nav ul li a:hover {
  color: #ff5f57;
}

/* Content Sections */
.content-section {
  padding: 60px 20px;
  background-color: #fff;
  margin: 20px 0;
  border-radius: 8px;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
  text-align: center;
}

.content-section h2 {
  font-size: 2.5rem;
  margin-bottom: 20px;
  color: #333;
}

.content-section p {
  font-size: 1.1rem;
  color: #555;
}

/* Service Cards */
.service-cards {
  display: flex;
  justify-content: space-between;
  gap: 20px;
  flex-wrap: wrap;
}

.service-card {
  background-color: #f9f9f9;
  padding: 20px;
  flex: 1;
  min-width: 300px;
  border-radius: 8px;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
  text-align: center;
}

.service-card h3 {
  font-size: 1.8rem;
  margin-bottom: 10px;
}

.service-card p {
  font-size: 1rem;
  color: #777;
}

.service-card:hover {
  transform: translateY(-10px);
}

/* Contact Form */
form {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

form label {
  font-size: 1.2rem;
  color: #333;
}

form input, form textarea {
  padding: 15px;
  font-size: 1rem;
  border: 1px solid #ddd;
  border-radius: 5px;
  outline: none;
  transition: border-color 0.3s ease;
}

form input:focus, form textarea:focus {
  border-color: #ff5f57;
}

form button {
  background-color: #ff5f57;
  color: white;
  padding: 15px 30px;
  border: none;
  border-radius: 50px;
  cursor: pointer;
  font-size: 1.2rem;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
  transition: background-color 0.3s ease;
}

form button:hover {
  background-color: #e54b47;
}

/* Footer */
.footer {
  background-color: #333;
  color: white;
  padding: 20px 0;
  text-align: center;
}

.footer-content {
  font-size: 1rem;
}

.footer a {
  color: #ff5f57;
  text-decoration: none;
  font-weight: bold;
}

.footer a:hover {
  text-decoration: underline;
}

/* Responsive Design */
@media (max-width: 768px) {
  .service-cards {
    flex-direction: column;
    align-items: center;
  }

  .service-card {
    width: 80%;
    margin-bottom: 20px;
  }
}
 
