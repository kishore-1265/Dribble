Date:14/10/25
AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

DESIGN STEPS:
Step 1:
Clone the repository from GitHub.

Step 2:
Create Django Admin project.

Step 3:
Create a New App under the Django Admin project.

Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

Step 5:
Create a HTML file and include the needed Bootstrap components.

Step 6:
Publish the website in the LocalHost.

PROGRAM :
```
 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .card-img-top {
      width: 100%;
      height: 250px;
      object-fit: cover;
    }
    footer {
      background-color: #f8f9fa;
      padding: 20px 0;
      text-align: center;
      width: 100%;
    }
    .hero {
      background-image: url('https://images.unsplash.com/photo-1503602642458-232111445657?auto=format&fit=crop&w=1400&q=80');
      background-size: cover;
      background-position: center;
      color: white;
      text-align: center;
      padding: 120px 20px;
    }
  </style>
</head>
<body>

  <!-- Navigation -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">Dribbble Clone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#">Features</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Portfolio</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
          <li class="nav-item"><a class="btn btn-primary text-white ms-2" href="/signup/">Sign Up</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <h1 class="display-5 fw-bold">Show Your Creativity to the World</h1>
    <p class="lead mb-4">Join the platform where designers share, grow, and inspire.</p>
    <a href="/signup/" class="btn btn-light btn-lg">Get Started</a>
  </section>

  <!-- Features Section -->
  <section class="container my-5">
    <h2 class="text-center mb-4">Features</h2>
    <div class="row text-center">
      <div class="col-md-4">
        <h4>For Designers</h4>
        <p>Showcase your portfolio and gain exposure to potential clients. Build your brand and get noticed by top businesses and teams.</p>
      </div>
      <div class="col-md-4">
        <h4>For Inspiration</h4>
        <p>Discover creative ideas from a global community of designers. Get inspired by the latest trends and innovative designs.</p>
      </div>
      <div class="col-md-4">
        <h4>For Businesses</h4>
        <p>Connect with top designers to bring your ideas to life. Find the right creative talent to help you build your brand’s future.</p>
      </div>
    </div>
  </section>

  <!-- Portfolio Section -->
  <section class="container my-5">
    <h2 class="text-center mb-4">Portfolio</h2>
    <div class="row">

      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="https://images.pexels.com/photos/4348403/pexels-photo-4348403.jpeg?auto=compress&cs=tinysrgb&w=800" class="card-img-top" alt="Retrospective Branding Design">
          <div class="card-body">
            <h5 class="card-title">Retrospective Branding Design</h5>
            <p class="card-text">A modern take on retro branding elements, blending classic typography with contemporary aesthetics.</p>
          </div>
        </div>
      </div>

      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="https://images.pexels.com/photos/3184454/pexels-photo-3184454.jpeg?auto=compress&cs=tinysrgb&w=800" class="card-img-top" alt="Home Swap Platform UI Elements">
          <div class="card-body">
            <h5 class="card-title">Home Swap Platform UI Elements</h5>
            <p class="card-text">UI design for a home exchange platform, featuring intuitive navigation and user-friendly interfaces.</p>
          </div>
        </div>
      </div>

      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="https://images.pexels.com/photos/3945631/pexels-photo-3945631.jpeg?auto=compress&cs=tinysrgb&w=800" class="card-img-top" alt="Jewelry Website Design">
          <div class="card-body">
            <h5 class="card-title">Jewelry Website Design</h5>
            <p class="card-text">An elegant e-commerce website design for a jewelry brand, emphasizing luxury and user experience.</p>
          </div>
        </div>
      </div>

      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="https://images.pexels.com/photos/6476589/pexels-photo-6476589.jpeg?auto=compress&cs=tinysrgb&w=800" class="card-img-top" alt="EV Charging Station Branding">
          <div class="card-body">
            <h5 class="card-title">EV Charging Station Branding</h5>
            <p class="card-text">Brand identity design for an electric vehicle charging station, incorporating eco-friendly themes.</p>
          </div>
        </div>
      </div>

      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="https://images.pexels.com/photos/4348404/pexels-photo-4348404.jpeg?auto=compress&cs=tinysrgb&w=800" class="card-img-top" alt="Fitness App UI Design">
          <div class="card-body">
            <h5 class="card-title">Fitness App UI Design</h5>
            <p class="card-text">A sleek and modern user interface design for a fitness tracking mobile application.</p>
          </div>
        </div>
      </div>

      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="https://images.pexels.com/photos/4065898/pexels-photo-4065898.jpeg?auto=compress&cs=tinysrgb&w=800" class="card-img-top" alt="Coffee Shop Logo Design">
          <div class="card-body">
            <h5 class="card-title">Coffee Shop Logo Design</h5>
            <p class="card-text">A minimalist and cozy logo design for a local coffee shop, capturing the essence of warmth.</p>
          </div>
        </div>
      </div>

    </div>
  </section>

  <!-- Contact Section -->
  <section class="container my-5">
    <h2 class="text-center mb-4">Contact Us</h2>
    <form>
      <div class="mb-3">
        <label for="name" class="form-label">Full Name</label>
        <input type="text" class="form-control" id="name" required>
      </div>
      <div class="mb-3">
        <label for="email" class="form-label">Email address</label>
        <input type="email" class="form-control" id="email" required>
      </div>
      <div class="mb-3">
        <label for="subject" class="form-label">Subject</label>
        <input type="text" class="form-control" id="subject" required>
      </div>
      <div class="mb-3">
        <label for="message" class="form-label">Message</label>
        <textarea class="form-control" id="message" rows="4" required></textarea>
      </div>
      <button type="submit" class="btn btn-primary">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 All rights reserved. Designed by Arjun R S</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```
OUTPUT:
<img width="1918" height="902" alt="Screenshot 2025-10-15 155906" src="https://github.com/user-attachments/assets/6180c9a3-63c8-4f62-8bef-89853b0be3c2" />

<img width="912" height="423" alt="Screenshot 2025-10-15 155926" src="https://github.com/user-attachments/assets/5be0a5cb-6a3f-4521-99fa-a257accba34a" />

RESULT:
The Project for responsive web design using Bootstrap is completed successfully.


