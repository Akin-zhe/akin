<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Akin — Product Designer</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:ital,wght@0,400;0,500;0,600;0,700;0,800;1,600;1,700&family=Caveat:wght@600&display=swap" rel="stylesheet">
<link rel="stylesheet" href="styles.css">
</head>
<body>

<!-- ===== NAVBAR ===== -->
<header class="navbar-wrap">
  <nav class="navbar">
    <a href="#" class="logo">
      <span class="logo-badge">A</span>
      Akin<span class="accent">.</span>
    </a>
    <ul class="nav-links">
      <li><a href="#" class="active">Home</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#blogs">Blogs</a></li>
      <li><a href="#testimonials">Testimonials</a></li>
    </ul>
    <a href="#contact" class="btn btn-white">Contact Me</a>
    <button class="menu-toggle" aria-label="Toggle menu">
      <span></span><span></span><span></span>
    </button>
  </nav>
</header>

<!-- ===== HERO ===== -->
<section class="hero">
  <div class="hero-inner">
    <div class="hero-text">
      <div class="tag-box">Hello There!</div>
      <h1>
        I'm <span class="accent italic">Akin,</span><br>
        Product Designer<br>
        Based in USA.
      </h1>
      <p class="hero-desc">I'm an experienced Product Designer with 18+ years in the field, collaborating with various companies and startups.</p>
      <div class="hero-ctas">
        <a href="#projects" class="btn btn-dark-pill">
          View My Portfolio
          <span class="play-circle">▶</span>
        </a>
        <a href="#contact" class="btn btn-outline">Hire Me</a>
      </div>
    </div>

    <div class="hero-media">
      <div class="blob"></div>
      <div class="photo-frame">
        <img src="portrait.svg" alt="Akin, Product Designer" class="portrait">
      </div>
      <div class="hire-badge">
        <svg viewBox="0 0 100 100" class="hire-badge-text">
          <path id="circlePath" d="M 50, 50 m -38, 0 a 38,38 0 1,1 76,0 a 38,38 0 1,1 -76,0" fill="none"/>
          <text font-size="10.5" letter-spacing="1.5" fill="#f5f1e8">
            <textPath href="#circlePath">HIRE ME • HIRE ME • HIRE ME • </textPath>
          </text>
        </svg>
        <span class="hire-arrow">↗</span>
      </div>
      <span class="floating-pill pill-role">UI/UX Designer</span>
      <span class="floating-pill pill-role2">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="M5 12h14M13 6l6 6-6 6" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
        Product Designer
      </span>
    </div>
  </div>

  <div class="marquee-strip">
    <div class="marquee-track">
      <span class="marquee-item">✳ App Design</span>
      <span class="marquee-item">✳ Website Design</span>
      <span class="marquee-item">✳ Dashboard</span>
      <span class="marquee-item">✳ Wireframe</span>
      <span class="marquee-item">✳ App Design</span>
      <span class="marquee-item">✳ Website Design</span>
      <span class="marquee-item">✳ Dashboard</span>
      <span class="marquee-item">✳ Wireframe</span>
    </div>
  </div>
</section>

<!-- ===== SERVICES ===== -->
<section class="services" id="services">
  <div class="section-inner">
    <div class="services-head">
      <div>
        <p class="eyebrow">— Services</p>
        <h2><span class="accent italic">Services</span> I Provide</h2>
      </div>
      <a href="#" class="btn btn-dark-pill small">
        View All Services
        <span class="play-circle">→</span>
      </a>
    </div>

    <div class="services-grid">
      <div class="service-card">
        <div class="service-icon">🎨</div>
        <h3>UI/UX Design</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor…</p>
        <a href="#" class="learn-more">Learn more →</a>
      </div>
      <div class="service-card">
        <div class="service-icon">✏️</div>
        <h3>Application Design</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor…</p>
        <a href="#" class="learn-more">Learn more →</a>
      </div>
      <div class="service-card">
        <div class="service-icon">🖥️</div>
        <h3>Website Design</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor…</p>
        <a href="#" class="learn-more">Learn more →</a>
      </div>
    </div>
  </div>
</section>

<!-- ===== ABOUT ===== -->
<section class="about" id="about">
  <div class="section-inner about-grid">
    <div class="about-media">
      <div class="about-blob"></div>
      <div class="about-photo-frame">
        <img src="portrait2.svg" alt="Portrait of Akin" class="about-portrait">
      </div>
      <span class="tag tag-1">UX/UI Design</span>
      <span class="tag tag-2">Mobile App Design</span>
      <span class="tag tag-3">Website Design</span>
      <span class="tag tag-4">Design System</span>
      <span class="tag tag-5">Prototype</span>
      <span class="tag tag-6">Dashboard</span>
      <span class="tag tag-7">Wireframe Design</span>
      <div class="point-arrow">↗</div>
    </div>

    <div class="about-text">
      <p class="eyebrow light">— About Me</p>
      <h2 class="light-h">Who is <span class="accent italic">Akin?</span></h2>
      <p class="about-desc">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>

      <div class="stats-row">
        <div class="stat">
          <strong>600+</strong>
          <span>Project Completed</span>
        </div>
        <div class="stat">
          <strong>50+</strong>
          <span>Industry Covered</span>
        </div>
        <div class="stat">
          <strong>18+</strong>
          <span>Years of Experience</span>
        </div>
      </div>

      <div class="about-cta-row">
        <a href="#" class="btn btn-gold-pill">
          Download CV
          <span class="play-circle dark">→</span>
        </a>
        <span class="signature">Akin</span>
      </div>
    </div>
  </div>
</section>

<!-- ===== TOOLS ===== -->
<section class="tools">
  <div class="section-inner tools-inner">
    <p class="eyebrow center">— My Favorite Tools</p>
    <h2 class="center-h">
      <span class="accent italic">Exploring the Tools</span><br>
      Behind My Designs
    </h2>
    <div class="tools-row">
      <div class="tool-icon" style="color:#F24E1E">◆</div>
      <div class="tool-icon" style="color:#FDB300">◇</div>
      <div class="tool-icon ps">Ps</div>
      <div class="tool-icon xd">Xd</div>
      <div class="tool-icon in">in</div>
      <div class="tool-icon s">S.</div>
    </div>
  </div>
</section>

<!-- ===== FOOTER ===== -->
<footer class="footer" id="contact">
  <div class="section-inner footer-inner">
    <div>
      <a href="#" class="logo footer-logo">
        <span class="logo-badge">A</span>
        Akin<span class="accent">.</span>
      </a>
      <p class="footer-tag">Product Designer crafting thoughtful digital experiences.</p>
    </div>
    <div class="footer-links">
      <h4>Navigate</h4>
      <a href="#">Home</a>
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
    </div>
    <div class="footer-links">
      <h4>Get in touch</h4>
      <a href="mailto:hello@akin.design">hello@akin.design</a>
      <a href="#">LinkedIn</a>
      <a href="#">Dribbble</a>
    </div>
  </div>
  <div class="footer-bottom">© 2026 Akin. All rights reserved.</div>
</footer>

</body>
</html>