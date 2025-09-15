<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Custom CSS -->
    <link rel="stylesheet" href="styling.css">
</head>
<body>
<!--Bootstrap navbar-->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Heritage Explorer</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="images/images/places.html">Places</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="images/images/about.html">About</a>
        </li>
        
      </ul>
    </div>
  </div>
</nav>
<!--Bootstrap navbar-->
<!--background-->
    <div class="background-image-container position-fixed top-0 start-0 w-100 h-100" style="z-index:-1;">
      <img src="https://images.pexels.com/photos/33899513/pexels-photo-33899513.jpeg" alt="background images" class="w-100 h-100 object-fit-cover" style="min-height:100vh; min-width:100vw;">
    </div>
<!--background-->
<!--hero section-->
<header class="hero-section text-center text-white d-flex align-center justify-content-center">
    <div class="container">
        <h1 class="display-4"> Discover Famous Historical Places </h1>
        <p class="lead">Explore the world's most landmarks and their rich histories </p>
    </div>
</header>
<!--hero section-->
<main>
<section class="d-flex flex-column flex-md-row align-items-center justify-content-center py-5">
  <div class="col-md-6 text-center text-md-start">
  <h1 class="display-5 fw-bold pastel-text">Step Into the Past</h1>
  <p class="lead pastel-text">From ancient wonders to hidden gems, our site brings history to life for every explorer.</p>
    <a href="images/images/places.html" class="btn btn-outline-light btn-lg mt-3">See the Places</a>
  </div>
  <div class="col-md-6 text-center">
    <div class="card card-curve mx-auto" style="max-width: 400px;">
      <img src="https://images.pexels.com/photos/2265876/pexels-photo-2265876.jpeg" class="card-img-top img-fluid" alt="Heritage">
      <div class="card-body">
        <h5 class="card-title">Heritage</h5>
      </div>
    </div>
  </div>
</section>
</main>

<!--bootstrap footer-->

<footer class="bg-dark text-white text-center py-4">
    <div class="container">
        <p class="mb-0">&copy; 2025 Heritage Explorer. All rights are reserved.</p>
</footer>


<!--bootstrap footer-->


    </body>
</html>
