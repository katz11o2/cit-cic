<script>
  import Logo1 from '../lib/logos/logo1.png';
  import Logo2 from '../lib/logos/logo2.png';
</script>

<style>
  footer {
    background-color: #17194a;
    color: white;
    font-family: 'Poppins', sans-serif;
    width: 100%;
    padding: 30px 0px 0 20px;
  }

  .footer-wrapper {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    width: 100%;
    max-width: 1280px;
    margin: 0 auto;
    position: relative;
  }

  .footer-left,
  .footer-center,
  .footer-right {
    flex: 1;
    min-width: 220px;
    text-align: left;
  }

  .footer-center {
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
    text-align: left;
  }

  .footer-right {
    max-width: 200px;
    padding-right: 1px;
     line-height:2;
  }

  .footer-heading {
    font-size: 15px;
    font-weight: 600;
    margin-bottom: 10px;
    
  }

  .footer-text {
    font-size: 12px;
    opacity: 0.9;
    line-height: 1.8;
    margin-bottom: 12px;
  }

  .footer-logos {
    margin-top: 30px;
    display: flex;
    gap: 40px;
  }

  .footer-logo {
    height: 50px;
    transition: transform 0.3s ease;
  }

  .footer-logo:hover {
    transform: scale(1.05);
  }

  .quick-links a {
    display: block;
    text-decoration: none;
    color: white;
    font-size: 12px;
    margin: 2px 0;
    transition: transform 0.2s ease, color 0.3s;
  }

  .quick-links a:hover {
    transform: translateX(5px);
    color: silver;
  }

  .social-icons {
    display: flex;
    gap: 15px;
    margin-top: 10px;
  }

  .social-icons a {
    color: white;
    font-size: 20px;
    transition: transform 0.2s ease, color 0.3s;
  }

  .social-icons a:hover {
    transform: scale(1.1);
    color: silver;
  }

  .footer-bottom {
    text-align: center;
    font-size: 12px;
    opacity: 0.8;
    margin-top: 0px;
    padding: 10px 0;
    border-top: 1px solid rgba(255, 255, 255, 0.1);
  }

  @media (max-width: 768px) {
    .footer-wrapper {
      flex-wrap: nowrap;
      gap: 10px;
    }

    .footer-left,
    .footer-center,
    .footer-right {
      min-width: 0;
      flex: 1;
    }

    .footer-center {
      position: absolute;
      left: 50%;
      transform: translateX(-50%);
    }

    .footer-heading {
      font-size: 13px;
    }

    .footer-text {
      font-size: 11px;
    }

    .footer-logo {
      height: 22px;
    }

    .social-icons a {
      font-size: 18px;
    }

    .quick-links a {
      font-size: 11px;
    }
  }
</style>

<footer>
  <div class="footer-wrapper">
    <!-- Left Section -->
    <div class="footer-left">
      <div class="footer-heading">
        In Association With MSME - COE (IISc) & <br> Ministry of MSME (GoI)
      </div>
      <div class="footer-text">
        Transforming ideas into breakthrough innovations <br> since 2010.
      </div>
      <div class="footer-logos">
        <img src=src\lib\logos\IISC.png  alt="Logo 1" class="footer-logo" />
        <img src=src\lib\logos\MSME.jpg alt="Logo 2" class="footer-logo" />
      </div>
    </div>

    <!-- Center Section -->
    <div class="footer-center">
      <div class="footer-heading">Connect with us</div>
      <div class="footer-text">
        Follow us on social media<br />and stay updated with our events!
      </div>
      <div class="social-icons">
        <a href="#"><i class="fab fa-youtube"></i></a>
        <a href="#"><i class="fab fa-instagram"></i></a>
        <a href="#"><i class="fab fa-facebook"></i></a>
        <a href="#"><i class="fab fa-linkedin"></i></a>
      </div>
    </div>

    <!-- Right Section -->
    <div class="footer-right quick-links">
      <div class="footer-heading">Quick Links</div>
      <a href="/">Home</a>
      <a href="/about">About Us</a>
      <a href="/services">Facilities</a>
      <a href="/projects">Post Your Design Challenges</a>
      <a href="/contact">Gallery</a>
      <a href="/blog">Calender of events</a>
      <a href="/events">Register/Login</a>
      <a href="/team">Contact us</a>
    </div>
  </div>

  <!-- Bottom Text -->
  <div class="footer-bottom">
    © 2025 Cambrian Innovation and Incubation Center. All rights reserved.
  </div>
</footer>
