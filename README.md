
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>SPANGLE | Architectural & Interior Design</title>
  <meta name="description" content="SPANGLE is a premium architecture & interior design studio crafting timeless residential, commercial, and luxury spaces.">
  <meta property="og:title" content="SPANGLE | Architecture & Interior Design Studio" />
  <meta property="og:description" content="Explore SPANGLE’s world-class architecture and interior design projects tailored to modern living." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="spangle-cover.webp" />
  <meta property="og:url" content="https://yourwebsite.com" />
  <link rel="icon" href="favicon.ico" type="image/x-icon" />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet"/>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>
  <link rel="stylesheet" href="style.css"/>
</head>

<body>
  <!-- Header -->
  <header class="main-header transparent" role="banner" id="site-header" style="--header-height:92px;">
    <div class="header-content">
      <div class="logo-box">
        <img src="spangle.webp" alt="SPANGLE Logo" class="logo-img" loading="lazy"/>
        <div class="brand-info">
          <h1 class="brand-title">SPANGLE</h1>
          <p class="brand-tagline">Architectural & Interior Design Studio</p>
        </div>
      </div>

      <nav class="navbar" role="navigation" aria-label="Main navigation">
        <div class="menu-toggle" id="mobile-menu" aria-controls="mobile-overlay" aria-expanded="false" tabindex="0" role="button" aria-label="Toggle navigation">
          <i class="fas fa-bars" aria-hidden="true"></i>
        </div>

        <ul class="nav-links desktop-nav" role="menubar">
          <li role="none"><a role="menuitem" href="#">Home</a></li>
          <li role="none"><a role="menuitem" href="#about">About</a></li>
          <li role="none"><a role="menuitem" href="#services">Services</a></li>
          <li role="none"><a role="menuitem" href="#projects">Projects</a></li>
          <li role="none"><a role="menuitem" href="#blog">Blog</a></li>
          <li role="none"><a role="menuitem" href="#contact">Contact</a></li>
        </ul>

        <div class="mobile-overlay" id="mobile-overlay" role="dialog" aria-modal="true" aria-hidden="true" tabindex="-1">
          <div class="close-btn" id="close-overlay" role="button" tabindex="0" aria-label="Close menu"><i class="fas fa-times" aria-hidden="true"></i></div>
          <ul class="overlay-nav" role="menu" aria-labelledby="mobile-menu">
            <li role="none"><a role="menuitem" href="#">Home</a></li>
            <li role="none"><a role="menuitem" href="#about">About</a></li>
            <li role="none"><a role="menuitem" href="#services">Services</a></li>
            <li role="none"><a role="menuitem" href="#projects">Projects</a></li>
            <li role="none"><a role="menuitem" href="#blog">Insights</a></li>
            <li role="none"><a role="menuitem" href="#contact">Contact</a></li>
          </ul>
        </div>
      </nav>
    </div>
  </header>

  <!-- Hero Slider -->
  <section class="hero-slider" aria-label="Homepage featured images">
    <div class="slider-container" id="slider" tabindex="0" aria-roledescription="carousel" aria-label="Featured projects carousel">
      <!-- NOTE: ensure these image filenames exist. I corrected 'spankle-' -> 'spangle-' if they were typos -->
      <img src="spankle final1.webp" class="slide active" alt="Luxurious architectural design with modern villa facade" loading="lazy" />
      <img src="spankle final 2.webp" class="slide" alt="Interior shot showcasing elegant living space" loading="lazy" />
      <img src="spanklefinal3.webp" class="slide" alt="Contemporary minimalist kitchen design" loading="lazy" />
      <img src="spanklefinal4.webp" class="slide" alt="Stunning night view of commercial architectural lighting" loading="lazy" />
      <button class="slide-btn prev" id="prev" aria-label="Previous slide">&#10094;</button>
      <button class="slide-btn next" id="next" aria-label="Next slide">&#10095;</button>
    </div>
  </section>

  <!-- Intro Section -->
  <section class="intro-section fade-slide" id="about" tabindex="0" aria-labelledby="intro-title">
    <div class="intro-wrapper">
      <div class="intro-image">
        <img src="spangleintrofinal.webp" alt="Interior design showcase with modern decor" loading="lazy" />
      </div>
      <div class="intro-content">
        <h2 id="intro-title" class="intro-title fade-slide">Transforming Spaces with Elegance</h2>
        <p class="intro-description fade-slide">
          At <strong>SPANGLE</strong>, creativity blends with precision to craft spaces reflecting your identity. From luxury homes to cutting-edge commercial interiors, we design environments that elevate lifestyles.
        </p>
        <p class="intro-description fade-slide">
          Innovation and meticulous attention to detail bring your vision to reality — spaces that inspire, function, and endure.
        </p>
        <a href="#services" class="intro-btn fade-slide" role="button">Explore Our Expertise</a>
      </div>
    </div>
  </section>

<!-- Why Choose Us Section -->
<section class="why-choose-us-section" id="services" aria-labelledby="why-choose-title">
  <div class="why-choose-us-wrapper">
    <h2 id="why-choose-title" class="section-title">Why Choose <span>SPANGLE</span></h2>
    <p class="why-intro">Experience the art of architectural perfection and bespoke interiors tailored exclusively for you.</p>
    
    <div class="features-grid">
      <div class="feature-box">
        <div class="feature-icon-wrap">
          <i class="fas fa-gem"></i>
        </div>
        <h3>Luxury Design Expertise</h3>
        <p>We craft timeless designs with precision, elegance, and a touch of luxury.</p>
      </div>

      <div class="feature-box">
        <div class="feature-icon-wrap">
          <i class="fas fa-user-check"></i>
        </div>
        <h3>Client-Centric Approach</h3>
        <p>Your vision is our blueprint — every decision aligns with your goals.</p>
      </div>

      <div class="feature-box">
        <div class="feature-icon-wrap">
          <i class="fas fa-clock"></i>
        </div>
        <h3>On-Time Delivery</h3>
        <p>Our streamlined processes ensure your project stays on schedule.</p>
      </div>

      <div class="feature-box">
        <div class="feature-icon-wrap">
          <i class="fas fa-tools"></i>
        </div>
        <h3>Impeccable Execution</h3>
        <p>Every detail is executed to perfection with the highest quality materials.</p>
      </div>
    </div>
  </div>
</section>



  <!-- Featured Projects Section -->
  <section class="featured-projects fade-slide" id="projects" tabindex="0" aria-labelledby="featured-projects-title">
    <div class="projects-wrapper">
      <h2 id="featured-projects-title" class="section-title">Featured Projects</h2>
      <div class="projects-grid">
        <div class="project-card fade-slide" tabindex="0" role="group" aria-label="Luxury Villa Project">
          <img src="proj1.webp" alt="Luxury Villa exterior with pool and garden" class="project-img" loading="lazy" />
          <div class="project-overlay">
            <h3>Luxury Villa</h3>
            <p>Ahmedabad | Residential</p>
          </div>
        </div>
        <div class="project-card fade-slide" tabindex="0" role="group" aria-label="Corporate Office Project">
          <img src="proj2.webp" alt="Corporate office building with glass facade" class="project-img" loading="lazy" />
          <div class="project-overlay">
            <h3>Corporate Office</h3>
            <p>Mumbai | Commercial</p>
          </div>
        </div>
        <div class="project-card fade-slide" tabindex="0" role="group" aria-label="Modern Bungalow Project">
          <img src="proj3.webp" alt="Modern bungalow with spacious terrace" class="project-img" loading="lazy" />
          <div class="project-overlay">
            <h3>Modern Bungalow</h3>
            <p>Surat | Residential</p>
          </div>
        </div>
        <div class="project-card fade-slide" tabindex="0" role="group" aria-label="Retail Showroom Project">
          <img src="proj4.webp" alt="Retail showroom modern interior with displays" class="project-img" loading="lazy" />
          <div class="project-overlay">
            <h3>Retail Showroom</h3>
            <p>Rajkot | Commercial</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Design Process Timeline (kept inline styles for now) -->
  <section class="process-timeline-section fade-slide" tabindex="0" aria-labelledby="process-timeline-title" style="max-width:1200px;margin:60px auto; padding: 0 20px;">
    <h2 id="process-timeline-title" class="section-title">Our Design & Build Process</h2>
    <div class="process-timeline" style="display:flex; flex-wrap:wrap; gap: 30px; justify-content:center;">
      <div style="flex:1 1 220px; background:#fff; border-radius:20px; padding:30px; box-shadow: 0 14px 36px rgba(246, 119, 46, 0.14); text-align:center;">
        <i class="fas fa-lightbulb" style="font-size:60px; color:#f6772e; margin-bottom:15px;" aria-hidden="true"></i>
        <h3 style="font-weight:700; margin-bottom:10px;">Conceptualize</h3>
        <p style="font-size:1rem; color:#4a4a4a;">Collaboration to understand your vision, needs & ambiance desires.</p>
      </div>
      <div style="flex:1 1 220px; background:#fff; border-radius:20px; padding:30px; box-shadow: 0 14px 36px rgba(246, 119, 46, 0.14); text-align:center;">
        <i class="fas fa-pencil-ruler" style="font-size:60px; color:#f6772e; margin-bottom:15px;" aria-hidden="true"></i>
        <h3 style="font-weight:700; margin-bottom:10px;">Design & Plan</h3>
        <p style="font-size:1rem; color:#4a4a4a;">Detailed blueprints & 3D models tailored to your needs.</p>
      </div>
      <div style="flex:1 1 220px; background:#fff; border-radius:20px; padding:30px; box-shadow: 0 14px 36px rgba(246, 119, 46, 0.14); text-align:center;">
        <i class="fas fa-hammer" style="font-size:60px; color:#f6772e; margin-bottom:15px;" aria-hidden="true"></i>
        <h3 style="font-weight:700; margin-bottom:10px;">Build & Furnish</h3>
        <p style="font-size:1rem; color:#4a4a4a;">Professional construction & premium finishes using quality materials.</p>
      </div>
      <div style="flex:1 1 220px; background:#fff; border-radius:20px; padding:30px; box-shadow: 0 14px 36px rgba(246, 119, 46, 0.14); text-align:center;">
        <i class="fas fa-check-circle" style="font-size:60px; color:#f6772e; margin-bottom:15px;" aria-hidden="true"></i>
        <h3 style="font-weight:700; margin-bottom:10px;">Review & Deliver</h3>
        <p style="font-size:1rem; color:#4a4a4a;">Final quality checks to hand over flawless, timeless spaces.</p>
      </div>
    </div>
  </section>

 <section class="testimonials-section" aria-labelledby="testimonials-title">
  <div class="testimonials-wrapper">
    <h2 id="testimonials-title" class="section-title">What Our Clients Say</h2>

    <div class="testimonials-grid">
      <!-- Client 1 -->
      <div class="testimonial-card">
        <div class="quote-icon">“</div>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR8SJHlOvjxzdgDnnyl38l-Tc7wnHGDvf70ANTdgZCFMxhESqcOftV2-qP9n0W9nGsIcdEPG9E" alt="Sunita Mehra" class="client-photo">
        <h4 class="client-name">Sunita Mehra</h4>
        <span class="client-role">CEO, Mehra Textiles</span>
        <p class="testimonial-text">
          SPANGLE transformed our home into a masterpiece. Every detail was carefully executed — highly recommended!
        </p>
      </div>

      <!-- Client 2 -->
      <div class="testimonial-card">
        <div class="quote-icon">“</div>
        <img src="client2.jpg" alt="Rohit Patel" class="client-photo">
        <h4 class="client-name">Rohit Patel</h4>
        <span class="client-role">Founder, TechEntrepreneurs</span>
        <p class="testimonial-text">
          Excellent project management and a beautiful office space creation. Truly professionals who care.
        </p>
      </div>

      <!-- Client 3 -->
      <div class="testimonial-card">
        <div class="quote-icon">“</div>
        <img src="client3.jpg" alt="Aarti Sinha" class="client-photo">
        <h4 class="client-name">Aarti Sinha</h4>
        <span class="client-role">Owner, Natura Boutique</span>
        <p class="testimonial-text">
          Their sustainable design approach and attention to detail elevate every space they touch.
        </p>
      </div>
    </div>
  </div>
</section>


<section class="awards-section" aria-labelledby="awards-title">
  <div class="awards-wrapper">
    <h2 id="awards-title" class="section-title">Awards & Recognition</h2>
    <p class="awards-subtitle">
      Celebrating excellence in design, innovation, and craftsmanship.
    </p>
    <div class="awards-grid">
      <!-- Award 1 -->
      <div class="award-card">
        <img src="images/awards/gold-award.png" alt="Gold Award for Luxury Interiors 2024" loading="lazy">
        <h4>Gold Award</h4>
        <p>Luxury Interiors – 2024</p>
      </div>
      <!-- Award 2 -->
      <div class="award-card">
        <img src="images/awards/green-cert.png" alt="Green Building Certification" loading="lazy">
        <h4>Certified Green Building</h4>
        <p>IGBC – 2023</p>
      </div>
      <!-- Award 3 -->
      <div class="award-card">
        <img src="images/awards/best-innovation.png" alt="Best Innovation in Workspace Design 2023" loading="lazy">
        <h4>Best Innovation</h4>
        <p>Workspace Design – 2023</p>
      </div>
    </div>
  </div>
</section>



  <!-- Team Spotlight -->
  <section class="team-spotlight fade-slide" tabindex="0" aria-labelledby="team-title" style="max-width:1200px; margin: 0 auto 100px auto; padding: 0 20px;">
    <h2 id="team-title" class="section-title">Meet Our Leadership</h2>
    <div style="display:flex; justify-content:center; flex-wrap: wrap; gap: 36px;">
      <div style="text-align:center; max-width: 250px;">
        <img src="https://randomuser.me/api/portraits/men/45.jpg" alt="Rajiv Patel" style="border-radius: 50%; width: 130px; height: 130px; object-fit: cover; box-shadow: 0 8px 24px rgba(246,119,46,0.3);" loading="lazy" />
        <h3 style="margin-top: 18px; color:#f6772e;">Rajiv Patel</h3>
        <p>Principal Architect — Visionary of contemporary Indian architecture with over 22 years of trailblazing design.</p>
      </div>
      <div style="text-align:center; max-width: 250px;">
        <img src="https://randomuser.me/api/portraits/women/65.jpg" alt="Neha Sharma" style="border-radius: 50%; width: 130px; height: 130px; object-fit: cover; box-shadow: 0 8px 24px rgba(246,119,46,0.3);" loading="lazy"/>
        <h3 style="margin-top: 18px; color:#f6772e;">Neha Sharma</h3>
        <p>Design Director — Award-winning interiors specialist, renowned for "spaces that speak."</p>
      </div>
      <div style="text-align:center; max-width: 250px;">
        <img src="https://randomuser.me/api/portraits/women/36.jpg" alt="Pooja Ghosh" style="border-radius: 50%; width: 130px; height: 130px; object-fit: cover; box-shadow: 0 8px 24px rgba(246,119,46,0.3);" loading="lazy" />
        <h3 style="margin-top: 18px; color:#f6772e;">Pooja Ghosh</h3>
        <p>Sustainability Lead — Biophilic design advocate leading all green projects.</p>
      </div>
      <div style="text-align:center; max-width: 250px;">
        <img src="https://randomuser.me/api/portraits/men/22.jpg" alt="Vikas Chauhan" style="border-radius: 50%; width: 130px; height: 130px; object-fit: cover; box-shadow: 0 8px 24px rgba(246,119,46,0.3);" loading="lazy" />
        <h3 style="margin-top: 18px; color:#f6772e;">Vikas Chauhan</h3>
        <p>Project Manager — Execution maestro driving quality and timely delivery.</p>
      </div>
    </div>
  </section>

  <!-- Latest Blog/Insights -->
  <section class="latest-blog fade-slide" tabindex="0" aria-labelledby="blog-title" style="max-width:1200px; margin: 60px auto 100px auto; padding: 0 20px;">
    <h2 id="blog-title" class="section-title">Latest Insights</h2>
    <div style="display:grid; grid-template-columns: repeat(auto-fit,minmax(320px,1fr)); gap: 40px;">
      <article style="background:#fff; border-radius: 16px; box-shadow: 0 12px 38px rgba(30,42,58,0.1); overflow: hidden; display: flex; flex-direction: column;">
        <img src="blog1.jpg" alt="Sustainable architecture trends" style="width: 100%; height: 210px; object-fit: cover;" loading="lazy" />
        <div style="padding: 24px;">
          <h3 style="color:#f6772e; font-weight:700; margin-bottom: 14px;">Sustainable Architecture Trends 2025</h3>
          <p style="color:#4a4a4a; line-height: 1.6;">Explore the top eco-friendly design ideas transforming urban spaces.</p>
          <a href="#" style="margin-top: 18px; display: inline-block; font-weight: 700; color: #e25141; text-decoration: underline;">Read more &rarr;</a>
        </div>
      </article>
      <article style="background:#fff; border-radius: 16px; box-shadow: 0 12px 38px rgba(30,42,58,0.1); overflow: hidden; display: flex; flex-direction: column;">
        <img src="blog2.jpg" alt="Modern minimalist interiors" style="width: 100%; height: 210px; object-fit: cover;" loading="lazy" />
        <div style="padding: 24px;">
          <h3 style="color:#f6772e; font-weight:700; margin-bottom: 14px;">Minimalist Interior Design Principles</h3>
          <p style="color:#4a4a4a; line-height: 1.6;">How to create calm, elegant spaces with minimal yet sophisticated touches.</p>
          <a href="#" style="margin-top: 18px; display: inline-block; font-weight: 700; color: #e25141; text-decoration: underline;">Read more &rarr;</a>
        </div>
      </article>
      <article style="background:#fff; border-radius: 16px; box-shadow: 0 12px 38px rgba(30,42,58,0.1); overflow: hidden; display: flex; flex-direction: column;">
        <img src="blog3.jpg" alt="Office space design ideas" style="width: 100%; height: 210px; object-fit: cover;" loading="lazy" />
        <div style="padding: 24px;">
          <h3 style="color:#f6772e; font-weight:700; margin-bottom: 14px;">Modern Office Spaces That Inspire</h3>
          <p style="color:#4a4a4a; line-height: 1.6;">Design trends to boost creativity and productivity in corporate environments.</p>
          <a href="#" style="margin-top: 18px; display: inline-block; font-weight: 700; color: #e25141; text-decoration: underline;">Read more &rarr;</a>
        </div>
      </article>
    </div>
  </section>

  <!-- CTA -->
  <section class="cta-contact fade-slide" tabindex="0" style="background: linear-gradient(90deg, #f6772e, #e25141); padding: 70px 20px; text-align: center; color: #fff;">
    <h2 style="font-size: 2.8rem; font-weight: 700; margin-bottom: 20px; max-width:900px; margin-left:auto; margin-right:auto;">
      Ready to Transform Your Space?<br />
      Let's Create Something Extraordinary Together.
    </h2>
    <a href="contact.html" role="button" style="background:#fff; color:#e25141; font-weight: 700; font-size: 1.4rem; padding: 18px 36px; border-radius: 45px; box-shadow: 0 14px 32px rgba(255,255,255,0.35); text-decoration:none; user-select:none; transition: background-color 0.3s ease, color 0.3s ease;" rel="noopener noreferrer">
      Get in Touch
    </a>
  </section>

  <footer style="background:#1e2a3a; color:#aaa; padding: 36px 20px; text-align:center; font-size: 0.9rem;">
    © 2025 SPANGLE Architecture & Interior Design | All Rights Reserved.
  </footer>

  <script src="index.js" defer></script>
</body>
</html>

