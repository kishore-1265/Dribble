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
 project.html

<title>Dribbble Clone</title> <style> /* Ensuring that all images have consistent dimensions */ .card-img-top { width: 100%; height: 250px; /* Adjust the height to maintain consistent size */ object-fit: cover; /* Ensures that the image covers the area without stretching */ } footer { background-color: #f8f9fa; padding: 20px 0; text-align: center; width: 100%; bottom: 0px; } </style>
Dribbble Clone
Features
Portfolio
Contact
Sign Up
Show Your Creativity to the World
Join the platform where designers share, grow, and inspire.

Get Started
Features
For Designers
Showcase your portfolio and gain exposure to potential clients. Build your brand and get noticed by top businesses and teams.

For Inspiration
Discover creative ideas from a global community of designers. Get inspired by the latest trends and innovative designs from industry experts.

For Businesses
Connect with top designers to bring your ideas to life. Find the right creative talent to help you design and build your brand’s future.

Portfolio
Explore some of the best creative works shared by the community.

Retrospective Branding Design
Retrospective Branding Design
A modern take on retro branding elements, blending classic typography with contemporary aesthetics.

Home Swap Platform UI Elements
Home Swap Platform UI Elements
UI design for a home exchange platform, featuring intuitive navigation and user-friendly interfaces.

Jewelry Website Design
Jewelry Website Design
An elegant e-commerce website design for a jewelry brand, emphasizing luxury and user experience.

EV Charging Station Branding
EV Charging Station Branding
Brand identity design for an electric vehicle charging station, incorporating eco-friendly themes.

Fitness App UI Design
Fitness App UI Design
A sleek and modern user interface design for a fitness tracking mobile application.

Coffee Shop Logo Design
Coffee Shop Logo Design
A minimalist and cozy logo design for a local coffee shop, capturing the essence of warmth.

Contact Us
We'd love to hear from you. Whether you have a question, feedback, or suggestion, feel free to reach out to us using the form below.

Full Name
Email address
Subject
Message <textarea class="form-control" id="message" name="message" rows="4" required></textarea>
Send Message
© 2025 All rights reserved.

Designed by Surya

signup.html <title>Sign Up - Dribbble Clone</title> <style> .container { max-width: 500px; } .form-container { padding: 30px; border-radius: 8px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); background-color: #fff; } </style>
Create an Account
Full Name
Email address
Password
Confirm Password
I agree to the terms and conditions
Sign Up
Already have an account? Login here

views.py from django.shortcuts import render def home_view(request): return render(request, 'project.html') def signup(request): return render(request, 'signup.html') urls.py from django.urls import path from . import views
urlpatterns = [ path('', views.home_view, name='home'), path('signup/', views.signup, name='signup'),

] from django.contrib import admin from django.urls import path, include

urlpatterns = [ path('admin/', admin.site.urls), path('', include('dripple.urls')), ] '''
```
OUTPUT:
Screenshot 2025-10-14 091456 Screenshot 2025-10-14 092850
RESULT:
The Project for responsive web design using Bootstrap is completed successfully.

About
No description, website, or topics provided.
Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 0 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Languages
HTML
65.3%
 
Python
34.7%
Footer
