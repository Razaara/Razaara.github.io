<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Rasara Gunawardana | Portfolio</title>
  <link rel="stylesheet" href="css/style.css"/>
  <link rel="preconnect" href="https://fonts.googleapis.com"/>
  <link href="https://fonts.googleapis.com/css2?family=Space+Mono:ital,wght@0,400;0,700;1,400&family=Syne:wght@400;600;700;800&display=swap" rel="stylesheet"/>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>
</head>
<body>

  <!-- Custom Cursor -->
  <div class="cursor" id="cursor"></div>
  <div class="cursor-follower" id="cursor-follower"></div>

  <!-- Loader -->
  <div class="loader" id="loader">
    <div class="loader-text">RG<span class="blink">_</span></div>
    <div class="loader-bar"><div class="loader-fill"></div></div>
  </div>

  <!-- Navigation -->
  <nav class="nav" id="nav">
    <div class="nav-logo">RG<span class="accent">.</span></div>
    <ul class="nav-links">
      <li><a href="#about" class="nav-link">About</a></li>
      <li><a href="#skills" class="nav-link">Skills</a></li>
      <li><a href="#projects" class="nav-link">Projects</a></li>
      <li><a href="#contact" class="nav-link">Contact</a></li>
    </ul>
    <div class="nav-hamburger" id="hamburger">
      <span></span><span></span><span></span>
    </div>
  </nav>

  <!-- Mobile Menu -->
  <div class="mobile-menu" id="mobileMenu">
    <ul>
      <li><a href="#about" class="mobile-link">About</a></li>
      <li><a href="#skills" class="mobile-link">Skills</a></li>
      <li><a href="#projects" class="mobile-link">Projects</a></li>
      <li><a href="#contact" class="mobile-link">Contact</a></li>
    </ul>
  </div>

  <!-- Hero Section -->
  <section class="hero" id="home">
    <div class="hero-bg-grid"></div>
    <div class="hero-noise"></div>
    <div class="hero-orb orb1"></div>
    <div class="hero-orb orb2"></div>
    <div class="hero-orb orb3"></div>

    <div class="hero-content">
      <div class="hero-tag reveal">
        <span class="tag-dot"></span>
        Available for internships & collaborations
      </div>
      <h1 class="hero-title reveal">
        <span class="line">Rasara</span>
        <span class="line accent-line">Gunawardana</span>
      </h1>
      <p class="hero-subtitle reveal">
        Undergraduate @ University of Sri Jayewardenepura<br/>
        Faculty of Applied Science &mdash; CS &bull; Mathematics &bull; Statistics
      </p>
      <div class="hero-cta reveal">
        <a href="#projects" class="btn btn-primary">View Projects <i class="fa-solid fa-arrow-right"></i></a>
        <a href="#contact" class="btn btn-ghost">Let's Talk</a>
      </div>
    </div>

    <div class="hero-scroll">
      <span>Scroll</span>
      <div class="scroll-line"></div>
    </div>
  </section>

  <!-- About Section -->
  <section class="about section" id="about">
    <div class="container">
      <div class="section-label reveal">01 — About</div>
      <div class="about-grid">
        <div class="about-visual reveal">
          <div class="about-card">
            <div class="about-avatar">
              <div class="avatar-letters">RG</div>
            </div>
            <div class="about-card-info">
              <div class="info-row"><i class="fa-solid fa-location-dot"></i> Sri Lanka</div>
              <div class="info-row"><i class="fa-solid fa-graduation-cap"></i> USJ — Applied Science</div>
              <div class="info-row"><i class="fa-solid fa-code"></i> Full Stack & Data Science</div>
            </div>
            <div class="about-card-tags">
              <span>CS</span><span>Math</span><span>Stats</span>
            </div>
          </div>
        </div>
        <div class="about-text reveal">
          <h2 class="section-title">Turning data &amp; code<br/>into real solutions.</h2>
          <p>I'm Rasara, an undergraduate student in the Faculty of Applied Science at the University of Sri Jayewardenepura, pursuing a triple specialisation in <strong>Computer Science, Mathematics, and Statistics.</strong></p>
          <p>I love building full-stack web applications, exploring machine learning pipelines, and working with data to extract meaningful insights. My projects reflect my curiosity across multiple disciplines.</p>
          <div class="about-stats">
            <div class="stat">
              <span class="stat-num" data-target="3">0</span>+
              <span class="stat-label">GitHub Projects</span>
            </div>
            <div class="stat">
              <span class="stat-num" data-target="10">0</span>+
              <span class="stat-label">Technologies</span>
            </div>
            <div class="stat">
              <span class="stat-num" data-target="3">0</span>
              <span class="stat-label">Disciplines</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Skills Section -->
  <section class="skills section" id="skills">
    <div class="container">
      <div class="section-label reveal">02 — Skills</div>
      <h2 class="section-title reveal">What I work with</h2>

      <div class="skills-grid">
        <div class="skill-category reveal">
          <div class="skill-cat-header">
            <div class="skill-icon"><i class="fa-solid fa-globe"></i></div>
            <h3>Web Development</h3>
          </div>
          <div class="skill-tags">
            <span class="stag">HTML</span>
            <span class="stag">CSS</span>
            <span class="stag">JavaScript</span>
            <span class="stag">PHP</span>
            <span class="stag">React</span>
            <span class="stag">Node.js</span>
          </div>
        </div>

        <div class="skill-category reveal">
          <div class="skill-cat-header">
            <div class="skill-icon"><i class="fa-solid fa-database"></i></div>
            <h3>Data & Programming</h3>
          </div>
          <div class="skill-tags">
            <span class="stag">Python</span>
            <span class="stag">Java</span>
            <span class="stag">SQL</span>
            <span class="stag">Jupyter Notebook</span>
          </div>
        </div>

        <div class="skill-category reveal">
          <div class="skill-cat-header">
            <div class="skill-icon"><i class="fa-solid fa-chart-bar"></i></div>
            <h3>Statistics & Analytics</h3>
          </div>
          <div class="skill-tags">
            <span class="stag">R</span>
            <span class="stag">SPSS</span>
            <span class="stag">Minitab</span>
          </div>
        </div>
      </div>

      <!-- Skill Bars -->
      <div class="skill-bars reveal">
        <div class="skill-bar-item">
          <div class="skill-bar-label"><span>JavaScript / Web</span><span>85%</span></div>
          <div class="skill-bar-track"><div class="skill-bar-fill" data-width="85"></div></div>
        </div>
        <div class="skill-bar-item">
          <div class="skill-bar-label"><span>Python / Data</span><span>80%</span></div>
          <div class="skill-bar-track"><div class="skill-bar-fill" data-width="80"></div></div>
        </div>
        <div class="skill-bar-item">
          <div class="skill-bar-label"><span>Statistics (R / SPSS)</span><span>75%</span></div>
          <div class="skill-bar-track"><div class="skill-bar-fill" data-width="75"></div></div>
        </div>
        <div class="skill-bar-item">
          <div class="skill-bar-label"><span>Java / SQL</span><span>70%</span></div>
          <div class="skill-bar-track"><div class="skill-bar-fill" data-width="70"></div></div>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section class="projects section" id="projects">
    <div class="container">
      <div class="section-label reveal">03 — Projects</div>
      <h2 class="section-title reveal">Things I've built</h2>
      <div class="projects-grid">

        <div class="project-card reveal">
          <div class="project-num">01</div>
          <div class="project-icon"><i class="fa-solid fa-hotel"></i></div>
          <h3>Hotel Operational System</h3>
          <p>A comprehensive system for managing hotel operations including bookings, room management, billing, and staff workflows.</p>
          <div class="project-tech">
            <span>Java</span><span>SQL</span><span>PHP</span>
          </div>
          <a href="https://github.com/Razaara/Hotel-Operational-System" target="_blank" class="project-link">
            View on GitHub <i class="fa-brands fa-github"></i>
          </a>
        </div>

        <div class="project-card reveal">
          <div class="project-num">02</div>
          <div class="project-icon"><i class="fa-solid fa-cart-shopping"></i></div>
          <h3>E-Commerce Website</h3>
          <p>A full-featured online store with product listings, cart functionality, user authentication, and payment flow.</p>
          <div class="project-tech">
            <span>HTML</span><span>CSS</span><span>JavaScript</span><span>PHP</span>
          </div>
          <a href="https://github.com/Razaara/E-Commerce-Website" target="_blank" class="project-link">
            View on GitHub <i class="fa-brands fa-github"></i>
          </a>
        </div>

        <div class="project-card reveal">
          <div class="project-num">03</div>
          <div class="project-icon"><i class="fa-solid fa-paintbrush"></i></div>
          <h3>Graphics Samples</h3>
          <p>A collection of creative graphics and visual design samples demonstrating design thinking and digital art skills.</p>
          <div class="project-tech">
            <span>Design</span><span>Graphics</span>
          </div>
          <a href="https://github.com/Razaara/Graphics-Samples" target="_blank" class="project-link">
            View on GitHub <i class="fa-brands fa-github"></i>
          </a>
        </div>

      </div>
      <div class="projects-footer reveal">
        <a href="https://github.com/Razaara" target="_blank" class="btn btn-ghost">
          <i class="fa-brands fa-github"></i> See all on GitHub
        </a>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section class="contact section" id="contact">
    <div class="container">
      <div class="section-label reveal">04 — Contact</div>
      <h2 class="section-title reveal">Get in touch</h2>
      <p class="contact-sub reveal">Have an idea, opportunity, or just want to say hi? My inbox is always open.</p>

      <div class="contact-grid">
        <div class="contact-info reveal">
          <a href="mailto:rasaragunawardana@gmail.com" class="contact-card">
            <div class="contact-card-icon"><i class="fa-solid fa-envelope"></i></div>
            <div>
              <div class="contact-card-label">Email</div>
              <div class="contact-card-value">rasaragunawardana@gmail.com</div>
            </div>
            <i class="fa-solid fa-arrow-up-right contact-arrow"></i>
          </a>

          <a href="https://www.linkedin.com/in/rasara-gunawardana" target="_blank" class="contact-card">
            <div class="contact-card-icon"><i class="fa-brands fa-linkedin-in"></i></div>
            <div>
              <div class="contact-card-label">LinkedIn</div>
              <div class="contact-card-value">Rasara Gunawardana</div>
            </div>
            <i class="fa-solid fa-arrow-up-right contact-arrow"></i>
          </a>

          <a href="https://github.com/Razaara" target="_blank" class="contact-card">
            <div class="contact-card-icon"><i class="fa-brands fa-github"></i></div>
            <div>
              <div class="contact-card-label">GitHub</div>
              <div class="contact-card-value">github.com/Razaara</div>
            </div>
            <i class="fa-solid fa-arrow-up-right contact-arrow"></i>
          </a>
        </div>

        <form class="contact-form reveal" id="contactForm">
          <div class="form-group">
            <label>Your Name</label>
            <input type="text" placeholder="John Doe" required/>
          </div>
          <div class="form-group">
            <label>Email Address</label>
            <input type="email" placeholder="john@example.com" required/>
          </div>
          <div class="form-group">
            <label>Message</label>
            <textarea rows="5" placeholder="What's on your mind?" required></textarea>
          </div>
          <button type="submit" class="btn btn-primary full-width">
            Send Message <i class="fa-solid fa-paper-plane"></i>
          </button>
          <div class="form-note">* Form connects via EmailJS or your preferred backend</div>
        </form>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <div class="container footer-inner">
      <div class="footer-logo">RG<span class="accent">.</span></div>
      <p>© 2025 Rasara Gunawardana. Built with ❤️ in Sri Lanka.</p>
      <div class="footer-links">
        <a href="https://github.com/Razaara" target="_blank"><i class="fa-brands fa-github"></i></a>
        <a href="https://www.linkedin.com/in/rasara-gunawardana" target="_blank"><i class="fa-brands fa-linkedin-in"></i></a>
        <a href="mailto:rasaragunawardana@gmail.com"><i class="fa-solid fa-envelope"></i></a>
      </div>
    </div>
  </footer>

  <script src="js/main.js"></script>
</body>
</html>
