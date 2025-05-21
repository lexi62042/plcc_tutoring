<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>{% block title %}PLCC | Pia Lokkevik Crash Courses{% endblock %}</title>
  
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
  
  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
  
  <!-- Custom CSS -->
  <link rel="stylesheet" href="{{ url_for('static', filename='css/style.css') }}">
  
  {% block extra_head %}{% endblock %}
</head>
<body>
  <!-- Header & Navbar -->
  <header>
    <div class="logo">PLCC | Pia Lokkevik</div>
    <nav>
      <ul>
        <li><a href="{{ url_for('index') }}" {% if active_page == 'home' %}class="active"{% endif %}>Home</a></li>
        <li><a href="{{ url_for('about') }}" {% if active_page == 'about' %}class="active"{% endif %}>About</a></li>
        <li><a href="{{ url_for('social') }}" {% if active_page == 'social' %}class="active"{% endif %}>Social Media</a></li>
        <li><a href="{{ url_for('payment') }}" {% if active_page == 'payment' %}class="active"{% endif %}>Payment Plans</a></li>
        <li><a href="{{ url_for('contact') }}" {% if active_page == 'contact' %}class="active"{% endif %}>Contact</a></li>
      </ul>
      <div class="mobile-menu-toggle">
        <i class="fas fa-bars"></i>
      </div>
    </nav>
  </header>

  <!-- Mobile Navigation Menu -->
  <div class="mobile-menu">
    <ul>
      <li><a href="{{ url_for('index') }}" {% if active_page == 'home' %}class="active"{% endif %}>Home</a></li>
      <li><a href="{{ url_for('about') }}" {% if active_page == 'about' %}class="active"{% endif %}>About</a></li>
      <li><a href="{{ url_for('social') }}" {% if active_page == 'social' %}class="active"{% endif %}>Social Media</a></li>
      <li><a href="{{ url_for('payment') }}" {% if active_page == 'payment' %}class="active"{% endif %}>Payment Plans</a></li>
      <li><a href="{{ url_for('contact') }}" {% if active_page == 'contact' %}class="active"{% endif %}>Contact</a></li>
    </ul>
  </div>

  <!-- Main Content -->
  <main>
    {% block content %}{% endblock %}
  </main>

  <!-- Footer -->
  <footer>
    <div class="footer-content">
      <div class="footer-contact">
        <p><i class="fas fa-envelope"></i> contact@plccteam.com</p>
        <p><i class="fas fa-map-marker-alt"></i> Based in Las Palmas, Spain</p>
      </div>
      <div class="footer-links">
        <a href="#">Privacy Policy</a> | <a href="#">Terms &amp; Conditions</a>
      </div>
      <div class="footer-social">
        <a href="#"><i class="fab fa-facebook-f"></i></a>
        <a href="#"><i class="fab fa-instagram"></i></a>
        <a href="#"><i class="fab fa-youtube"></i></a>
        <a href="#"><i class="fab fa-tiktok"></i></a>
      </div>
    </div>
    <div class="footer-copyright">
      <p>&copy; 2023 PLCC | Pia Lokkevik Crash Courses. All rights reserved.</p>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
  
  <!-- Custom JS -->
  <script src="{{ url_for('static', filename='js/script.js') }}"></script>
  
  {% block extra_scripts %}{% endblock %}
</body>
</html>
