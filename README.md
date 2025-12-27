# Project Responsive Web Design using Bootstrap
# Date:
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>City Pharmacy</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

    <style>
        .bg img{
            position: absolute;
            width: 100%;
            height: 100%;
        }
        .hero-overlay {
            background-color: rgba(0,0,0,0.6);
            padding: 60px;
        }
    </style>
</head>
<body>
    <div class="bg">
        <img src="../static/bgimg.png">
    </div>

<nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <div class="container">
        <a class="navbar-brand" href="#">City Pharmacy</a>
        <button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#navMenu">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navMenu">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
                <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
                <li class="nav-item"><a class="nav-link" href="#products">Products</a></li>
                <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
            </ul>
        </div>
    </div>
</nav>

<section class="hero text-center">
    <div class="hero-overlay">
        <h1>Trusted Pharmacy for Your Health</h1>
        <p class="lead">Quality medicines • Expert advice • Fast service</p>
        <a href="#products" class="btn btn-warning btn-lg">View Products</a>
    </div>
</section>

<section id="services" class="py-5">
    <div class="container">
        <h2 class="text-center mb-4">Our Services</h2>
        <div class="row text-center">
            <div class="col-md-4">
                <div class="card shadow">
                    <div class="card-body">
                        <h5 class="card-title">Prescription Medicines</h5>
                        <p class="card-text">Genuine and safe medicines from trusted brands.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card shadow">
                    <div class="card-body">
                        <h5 class="card-title">Health Consultation</h5>
                        <p class="card-text">Get advice from trained pharmacists.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card shadow">
                    <div class="card-body">
                        <h5 class="card-title">Home Delivery</h5>
                        <p class="card-text">Fast and reliable doorstep delivery.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<section id="products" class="bg-light py-5">
    <div class="container">
        <h2 class="text-center mb-4">Popular Products</h2>
        <div class="row text-center">
            <div class="col-md-3">
                <div class="card">
                    <img src="../static/pain.png" class="card-img-top">
                    <div class="card-body">
                        <h6 class="card-title">Pain Relief Tablets</h6>
                        <p class="card-text">₹120</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card">
                    <img src="../static/vitamin.png" class="card-img-top">
                    <div class="card-body">
                        <h6 class="card-title">Vitamin Supplements</h6>
                        <p class="card-text">₹250</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card">
                    <img src="../static/cough_syrup.png" class="card-img-top">
                    <div class="card-body">
                        <h6 class="card-title">Cough Syrup</h6>
                        <p class="card-text">₹90</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card">
                    <img src="../static/firstaid.png" class="card-img-top">
                    <div class="card-body">
                        <h6 class="card-title">First Aid Kit</h6>
                        <p class="card-text">₹350</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<section id="contact" class="py-5">
    <div class="container">
        <h2 class="text-center mb-4">Contact Us</h2>
        <div class="row justify-content-center">
            <div class="col-md-6">
                <form>
                    <input type="text" class="form-control mb-3" placeholder="Your Name">
                    <input type="email" class="form-control mb-3" placeholder="Your Email">
                    <textarea class="form-control mb-3" placeholder="Message"></textarea>
                    <button class="btn btn-success w-100">Send Message</button>
                </form>
            </div>
        </div>
    </div>
</section>

<footer class="bg-success text-white text-center p-3">
    © 2025 City Pharmacy | All Rights Reserved
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

# OUTPUT:
<img width="1920" height="1080" alt="Screenshot (76)" src="https://github.com/user-attachments/assets/f3f95a41-6088-495b-b994-51395fa2eacd" />
<img width="1920" height="1080" alt="Screenshot (75)" src="https://github.com/user-attachments/assets/6874ba40-fec0-4b0a-93a0-6ef53b33d1cc" />


# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
