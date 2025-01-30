<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Amit Kumar | Certified Fitness Coach & Health Specialist</title>
  <meta name="description" content="Overcome thyroid, PCOS, diabetes & other health conditions with personalized fitness plans by Certified Coach Amit Kumar. Start your transformation today!">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&family=Montserrat:wght@500;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
  <style>
    :root {
      --primary: #25D366;
      --secondary: #2A5298;
      --accent: #FF6B6B;
      --dark: #1A1A1A;
      --light: #FFFFFF;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: var(--light);
      color: var(--dark);
      line-height: 1.6;
      overflow-x: hidden;
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 20px;
    }

    /* Header */
    .header {
      background: rgba(255, 255, 255, 0.95);
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
      box-shadow: 0 2px 15px rgba(0, 0, 0, 0.1);
    }

    .nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 0;
    }

    .logo {
      font-family: 'Montserrat', sans-serif;
      font-weight: 700;
      color: var(--secondary);
      font-size: 1.5rem;
      text-decoration: none;
    }

    /* Hero Section */
    .hero {
      padding: 150px 0 100px;
      background: linear-gradient(135deg, rgba(255, 255, 255, 0.95), rgba(255, 255, 255, 0.95)), url('https://images.unsplash.com/photo-1571019614242-c5c5dee9f50b') center/cover;
      position: relative;
    }

    .hero-content {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 2rem;
      align-items: center;
    }

    .hero-text {
      animation: slideLeft 1s ease-out;
    }

    .hero-image {
      border-radius: 20px;
      overflow: hidden;
      box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
      animation: slideRight 1s ease-out;
    }

    .hero-image img {
      width: 100%;
      height: auto;
      display: block;
    }

    h1 {
      font-family: 'Montserrat', sans-serif;
      font-size: 3.5rem;
      color: var(--secondary);
      margin-bottom: 1.5rem;
      line-height: 1.2;
    }

    .highlight {
      color: var(--accent);
      position: relative;
      display: inline-block;
    }

    .highlight::after {
      content: '';
      position: absolute;
      bottom: 5px;
      left: 0;
      width: 100%;
      height: 12px;
      background: rgba(255, 107, 107, 0.3);
      z-index: -1;
    }

    /* Features Grid */
    .features {
      padding: 4rem 0;
      background: #F8F9FA;
    }

    .features-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }

    .feature-card {
      background: var(--light);
      padding: 2rem;
      border-radius: 15px;
      text-align: center;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
      transition: transform 0.3s ease;
    }

    .feature-card:hover {
      transform: translateY(-10px);
    }

    .feature-icon {
      font-size: 2.5rem;
      color: var(--primary);
      margin-bottom: 1rem;
    }

    /* Testimonials */
    .testimonials {
      padding: 4rem 0;
    }

    .testimonial-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }

    .testimonial-card {
      background: var(--light);
      padding: 2rem;
      border-radius: 15px;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
      position: relative;
    }

    .testimonial-card::before {
      content: '"';
      font-family: 'Montserrat', sans-serif;
      font-size: 5rem;
      color: var(--primary);
      position: absolute;
      top: -10px;
      left: 10px;
      opacity: 0.2;
    }

    .client-info {
      display: flex;
      align-items: center;
      margin-top: 1.5rem;
    }

    .client-image {
      width: 50px;
      height: 50px;
      border-radius: 50%;
      margin-right: 1rem;
    }

    /* CTA Section */
    .cta-section {
      background: var(--secondary);
      color: var(--light);
      padding: 4rem 0;
      text-align: center;
    }

    /* Animations */
    @keyframes slideLeft {
      from { transform: translateX(-100px); opacity: 0; }
      to { transform: translateX(0); opacity: 1; }
    }

    @keyframes slideRight {
      from { transform: translateX(100px); opacity: 0; }
      to { transform: translateX(0); opacity: 1; }
    }

    .scroll-reveal {
      opacity: 0;
      transform: translateY(30px);
      transition: all 0.6s ease;
    }

    .scroll-reveal.active {
      opacity: 1;
      transform: translateY(0);
    }

    /* Responsive Design */
    @media (max-width: 768px) {
      .hero-content {
        grid-template-columns: 1fr;
        text-align: center;
      }

      h1 {
        font-size: 2.5rem;
      }

      .features-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  <header class="header">
    <nav class="nav container">
      <a href="#" class="logo">AmitFit</a>
      <div class="contact-info">
        <a href="tel:+8210145599" class="contact-link"><i class="fas fa-phone"></i> +82 1014-5599</a>
      </div>
    </nav>
  </header>

  <section class="hero">
    <div class="container">
      <div class="hero-content">
        <div class="hero-text">
          <h1>Transform Your Body & <span class="highlight">Overcome Health Challenges</span></h1>
          <p class="lead">Certified Fitness Coach specializing in thyroid, PCOS, diabetes management and sustainable weight loss.</p>
          <a href="https://wa.me/8210145599" class="cta-button">Start Your Journey Now <i class="fab fa-whatsapp"></i></a>
        </div>
        <div class="hero-image">
          <img src="coach-image.jpg" alt="Amit Kumar Fitness Coach">
        </div>
      </div>
    </div>
  </section>

  <section class="features">
    <div class="container">
      <h2 class="section-title scroll-reveal">Why Choose Me?</h2>
      <div class="features-grid">
        <div class="feature-card scroll-reveal">
          <i class="fas fa-heartbeat feature-icon"></i>
          <h3>Medical Condition Expertise</h3>
          <p>Specialized programs for thyroid, PCOS, diabetes & hypertension management</p>
        </div>
        <div class="feature-card scroll-reveal">
          <i class="fas fa-chart-line feature-icon"></i>
          <h3>Proven Results</h3>
          <p>150+ successful transformations with sustainable results</p>
        </div>
        <div class="feature-card scroll-reveal">
          <i class="fas fa-user-cog feature-icon"></i>
          <h3>Personalized Plans</h3>
          <p>Customized nutrition & workout plans based on your unique needs</p>
        </div>
      </div>
    </div>
  </section>

  <section class="testimonials">
    <div class="container">
      <h2 class="section-title scroll-reveal">Success Stories</h2>
      <div class="testimonial-grid">
        <div class="testimonial-card scroll-reveal">
          <p>"Lost 18kg in 5 months despite my thyroid condition. Amit's approach changed my life!"</p>
          <div class="client-info">
            <img src="client1.jpg" alt="Client" class="client-image">
            <div>
              <h4>Priya Singh</h4>
              <p>PCOS Warrior</p>
            </div>
          </div>
        </div>
        <div class="testimonial-card scroll-reveal">
          <p>"Managed diabetes and lost 12% body fat. Best investment in my health!"</p>
          <div class="client-info">
            <img src="client2.jpg" alt="Client" class="client-image">
            <div>
              <h4>Rajesh Mehta</h4>
              <p>Diabetes Management</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <script>
    // Scroll Reveal Animation
    const scrollReveal = document.querySelectorAll('.scroll-reveal');
    
    const revealOnScroll = () => {
      scrollReveal.forEach(element => {
        const elementTop = element.getBoundingClientRect().top;
        const windowHeight = window.innerHeight;
        
        if (elementTop < windowHeight - 100) {
          element.classList.add('active');
        }
      });
    };

    window.addEventListener('scroll', revealOnScroll);
    window.addEventListener('load', revealOnScroll);
  </script>
</body>
</html>
