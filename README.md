{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Poppins', sans-serif;
  background-color: #0f0f1a;
  color: #e6e6f0;
  scroll-behavior: smooth;
}

/* Navbar */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 8%;
  background-color: #0f0f1a;
  position: sticky;
  top: 0;
  z-index: 100;
  border-bottom: 1px solid #1f1f30;
}

.logo {
  font-size: 24px;
  font-weight: 700;
  color: #ffffff;
}

.logo span {
  color: #7c5cff;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 32px;
}

.nav-links a {
  text-decoration: none;
  color: #c4c4d4;
  font-weight: 400;
  transition: color 0.3s ease;
}

.nav-links a:hover {
  color: #7c5cff;
}

/* Hero Section */
.hero {
  min-height: 90vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 0 8%;
  background: radial-gradient(circle at top right, #1b1b2f, #0f0f1a 70%);
}

.greeting {
  color: #7c5cff;
  font-size: 18px;
  margin-bottom: 8px;
  letter-spacing: 1px;
}

.hero h1 {
  font-size: 64px;
  font-weight: 700;
  color: #ffffff;
  margin-bottom: 8px;
}

.hero h2 {
  font-size: 24px;
  font-weight: 400;
  color: #a0a0b8;
  margin-bottom: 20px;
}

.tagline {
  font-size: 16px;
  color: #8a8aa3;
  max-width: 500px;
  margin: 0 auto 32px;
}

.hero-buttons {
  display: flex;
  gap: 20px;
  justify-content: center;
}

.btn {
  padding: 12px 28px;
  border-radius: 30px;
  text-decoration: none;
  font-weight: 600;
  font-size: 15px;
  transition: all 0.3s ease;
}

.btn-primary {
  background-color: #7c5cff;
  color: #ffffff;
}

.btn-primary:hover {
  background-color: #6a4be0;
  transform: translateY(-2px);
}

.btn-outline {
  border: 1px solid #7c5cff;
  color: #7c5cff;
}

.btn-outline:hover {
  background-color: #7c5cff;
  color: #ffffff;
  transform: translateY(-2px);
}

/* Section Common */
.section {
  padding: 80px 8%;
}

.alt-bg {
  background-color: #14141f;
}

.section-title {
  font-size: 36px;
  font-weight: 700;
  color: #ffffff;
  text-align: center;
  margin-bottom: 48px;
  position: relative;
}

.section-title::after {
  content: '';
  width: 60px;
  height: 4px;
  background-color: #7c5cff;
  display: block;
  margin: 12px auto 0;
  border-radius: 2px;
}

/* About */
.about-content {
  max-width: 700px;
  margin: 0 auto;
  text-align: center;
  font-size: 17px;
  color: #b0b0c4;
  line-height: 1.8;
}

/* Skills */
.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 24px;
  max-width: 900px;
  margin: 0 auto;
}

.skill-card {
  background-color: #1b1b2f;
  border: 1px solid #2a2a40;
  padding: 24px;
  text-align: center;
  border-radius: 12px;
  font-weight: 600;
  color: #d0d0e0;
  transition: all 0.3s ease;
}

.skill-card:hover {
  border-color: #7c5cff;
  transform: translateY(-5px);
  box-shadow: 0 10px 25px rgba(124, 92, 255, 0.15);
}

/* Projects */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 28px;
  max-width: 1000px;
  margin: 0 auto;
}

.project-card {
  background-color: #1b1b2f;
  border: 1px solid #2a2a40;
  padding: 28px;
  border-radius: 14px;
  transition: all 0.3s ease;
}

.project-card:hover {
  transform: translateY(-6px);
  border-color: #7c5cff;
  box-shadow: 0 12px 30px rgba(124, 92, 255, 0.15);
}

.project-card h3 {
  color: #ffffff;
  margin-bottom: 12px;
  font-size: 20px;
}

.project-card p {
  color: #9a9ab0;
  font-size: 14px;
  line-height: 1.6;
  margin-bottom: 16px;
}

.project-link {
  color: #7c5cff;
  text-decoration: none;
  font-weight: 600;
  font-size: 14px;
}

.project-link:hover {
  text-decoration: underline;
}

/* Contact */
.contact-text {
  text-align: center;
  color: #a0a0b8;
  margin-bottom: 32px;
}

.contact-links {
  display:…# portfolio
