<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
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


<!-- As a heading -->
<nav class="navbar navbar-light bg-light">
  <div class="container-fluid">
    <span class="navbar-brand mb-0 h1">Places</span>
  </div>
</nav>
<!--Bootstrap navbar-->
<!--background-->
<div class="background">
  <div class="ratio ratio-16x9">
    <video autoplay muted loop id="bg-video" class="w-100 h-100" style="object-fit:cover;">
      <source src="https://www.pexels.com/download/video/31379008/" type="video/mp4">
      Your browser does not support the video tag.
    </video>
      <div class="overlay-text position-absolute top-50 start-50 translate-middle text-center text-white">
    <h1>Echoes Beneath the Earth </h1>
    <p>Where ancient whispers rise from stone, and history breathes through hidden chambers</p>
  </div>
  </div>
   
<!--background-->

<div class="intro-highlight text-center py-4">
    <strong>
        Discover the <span class="highlight">hidden sanctuaries</span> and <span class="highlight">forgotten empires</span> that shaped our world.
    </strong>
</div>

  

<!--container-->

<div class="container my-5">
    <div class="row g-4">
        <div class="col-md-4">
            <div class="card h-100">
                <img src="https://images.pexels.com/photos/3727264/pexels-photo-3727264.jpeg" class="card-img-top" alt="Petra, Jordan">
                <div class="card-body">
                    <h5 class="card-title">PETRA</h5>
                    <p class="card-text">Petra,Carved into rose-red cliffs, Petra was once a thriving Nabataean trade hub. Its rock-cut architecture and water conduit system reveal advanced engineering. Known as the “Lost City,” it blends Hellenistic façades with Arab craftsmanship.it’s a symbol of resilience and mystery.</p>
                    <p><strong>Location:</strong> Jordan, Middle East </p>
                    <p><strong>Established:</strong>312 BC</p>
                </div>
            </div>
        </div>
            <div class="col-md-4">
                <div class="card h-100">
                    <img src="https://images.pexels.com/photos/3532326/pexels-photo-3532326.jpeg" class="card-img-top" alt="Machu Picchu, Peru">
                    <div class="card-body">
                        <h5 class="card-title">Machu Picchu</h5>
                        <p class="card-text">Nestled in the Andes, this Incan citadel was hidden from the world until 1911. Its terraces, temples, and astronomical alignments reflect deep spiritual and agricultural knowledge. It’s a testament to Incan ingenuity and sacred geography.</p>
                        <p><strong>Location:</strong> Peru, South America</p>
                        <p><strong>Established:</strong> 15th Century</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card h-100">
                    <img src="https://images.pexels.com/photos/965208/pexels-photo-965208.jpeg" class="card-img-top" alt="Siem Reap, Cambodia">
                    <div class="card-body">
                        <h5 class="card-title">Angkor Wat</h5>
                        <p class="card-text">The world’s largest religious monument, built in the 12th century by the Khmer Empire. Originally Hindu, later Buddhist, it showcases celestial symbolism and intricate bas-reliefs. Its grandeur reflects Southeast Asia’s spiritual and political power.</p>
                        <p><strong>Location:</strong> Siem Reap, Cambodia</p>
                        <p><strong>Established:</strong> Circa 1150 CE</p>
                    </div>
                </div>
            </div>
            <div class="row g-4">
                <div class="card h-100">
                    <img src="https://images.pexels.com/photos/12031383/pexels-photo-12031383.jpeg" class="card-img-top" alt="Yucatán, Mexico">
                    <div class="card-body">
                        <h5 class="card-title">Chichén Itzá</h5>
                        <p class="card-text">A Mayan city famed for El Castillo, a pyramid aligned with equinox shadows. It was a center for astronomy, rituals, and trade. The ball court and sacred cenote reveal a complex society with cosmic beliefs.</p>
                        <p><strong>Location:</strong> Yucatán, Mexico</p>
                        <p><strong>Established:</strong> 435 CE</p>
                    </div>
                </div>
            </div>
    <div class="row g-4">
        <div class="col-md-4">
            <div class="card h-100">
                <img src="https://images.pexels.com/photos/17397673/pexels-photo-17397673.jpeg" class="card-img-top" alt="Southeastern Anatolia">
                <div class="card-body">
                    <h5 class="card-title">Göbekli Tepe</h5>
                    <p class="card-text">Dating back to 9600 BCE, this site rewrites history—it predates agriculture and cities. Its T-shaped pillars with animal carvings suggest early ritualistic behavior. It challenges the timeline of human civilization.</p>
                    <p><strong>Location:</strong>Şanlıurfa, Southeastern Anatolia</p>
                    <p><strong>Established:</strong> 9500 BCE- over 11,000 years ago</p>
                </div>
            </div>
        </div>
        <div class="col-md-4">
            <div class="card h-100">
                <img src="https://images.pexels.com/photos/32491217/pexels-photo-32491217.jpeg" class="card-img-top" alt=" Maharastra, India">
                <div class="card-body">
                    <h5 class="card-title">Ajanta Caves</h5>
                    <p class="card-text">A fusion of Hindu, Buddhist, and Jain temples carved into basalt cliffs. The Kailasa temple, sculpted from a single rock, is an architectural marvel. It reflects India’s pluralistic spiritual heritage and artistic mastery.</p>
                    <p><strong>Location:</strong> Aurangabad, Maharastra, India</p>
                    <p><strong>Established:</strong> 1983 (7th Session)</p>
                </div>
            </div>
        </div>
        <div class="col-md-4">
            <div class="card h-100">
                <img src="https://images.pexels.com/photos/1427569/pexels-photo-1427569.jpeg" class="card-img-top" alt="Wiltshire, England">
                <div class="card-body">
                    <h5 class="card-title">Stonehenge</h5>
                    <p class="card-text">Stonehenge holds deep cultural significance as a symbol of ancient human ingenuity, spirituality, and social unity.Associated with death, afterlife, and ancestral worship, supported by nearby burial mounds.</p>
                    <p><strong>Location:</strong> Wiltshire, England</p>
                    <p><strong>Established:</strong> 3000 BCE - 1600 BCE</p>
                </div>
            </div>
        </div>
        <div class="col-md-4">
            <div class="card h-100">
                <img src="https://images.pexels.com/photos/31350284/pexels-photo-31350284.jpeg" class="card-img-top" alt="Colorado, United States">
                <div class="card-body">
                    <h5 class="card-title">Mesa Verde</h5>
                    <p class="card-text">Home to Ancestral Puebloans, its cliff dwellings are carved into canyon walls. The structures reflect communal living and spiritual beliefs tied to nature. It’s a window into Native American heritage.</p>
                    <p><strong>Location:</strong> Colorado, United States</p>
                    <p><strong>Established:</strong>29 June 1906</p>
                </div>
            </div>
        </div>
         <div class="col-md-4">
            <div class="card h-100">
                <img src="https://images.pexels.com/photos/1675184/pexels-photo-1675184.jpeg" class="card-img-top" alt="Wiltshire, England">
                <div class="card-body">
                    <h5 class="card-title">Alhambra</h5>
                    <p class="card-text">Its intricate Islamic architecture—mosaics, calligraphy, and muqarnas ceilings—blends with later Christian additions. The Court of the Lions and Hall of the Ambassadors reflect a golden age of Andalusian art and diplomacy. The Alhambra symbolizes coexistence, conquest, and cultural fusion between Muslim and Christian worlds.</p>
                    <p><strong>Location:</strong>Granada, Spain</p>
                    <p><strong>Established:</strong> 13th century</p>
                </div>
            </div>
        </div>
        <div class="col-md-4">
            <div class="card h-100">
                <img src="https://images.pexels.com/photos/2445852/pexels-photo-2445852.jpeg" class="card-img-top" alt="Pyramids of Giza, Egypt">
                <div class="card-body">
                    <h5 class="card-title">Pyramids of Giza</h5>
                    <p class="card-text">Raised over 4,500 years ago, the Great Pyramid of Khufu stood as the tallest human-made structure for nearly four millennia—proof that ancient vision could defy time.</p>
                    <p><strong>Location:</strong> Giza, Egypt</p>
                    <p><strong>Established:</strong> 2560 BC</p>
                </div>
            </div>
        </div>
        <div class="col-md-4">
            <div class="card h-100">
                <img src="https://cdn.sanity.io/images/cxgd3urn/production/9ee2b03dbbf1e10c9057c59a7b7deac5ee42267f-2000x1329.jpg?rect=0,1,2000,1328&w=1200&h=797&q=85&fit=crop&auto=format" class="card-img-top" alt="Bamyan, Afghanistan">
                <div class="card-body">
                    <h5 class="card-title">Bamiyan Buddhas</h5>
                    <p class="card-text">Once towering statues carved into cliffs, destroyed in 2001. They were part of a Buddhist monastic complex and symbolized cultural tolerance. Their absence now speaks volumes about heritage loss.</p>
                    <p><strong>Location:</strong> Bamyan, Afghanistan</p>
                    <p><strong>Established:</strong>  6th Century</p>
                </div>
            </div>
        </div>
        <div class="col-md-4">
            <div class="card h-100">
                <img src="https://images.pexels.com/photos/13911606/pexels-photo-13911606.jpeg" class="card-img-top" alt=" Rio de Janeiro, Brazil">
                <div class="card-body">
                    <h5 class="card-title">Christ the Redeemer</h5>
                    <p class="card-text">Petra,Carved into rose-red cliffs, Petra was once a thriving Nabataean trade hub. Its rock-cut architecture and water conduit system reveal advanced engineering. Known as the “Lost City,” it blends Hellenistic façades with Arab craftsmanship.it’s a symbol of resilience and mystery.</p>
                    <p><strong>Location:</strong> Corcovado Mountain, Rio de Janeiro, Brazil. </p>
                    <p><strong>Established:</strong>1922 and 1931</p>
                </div>
            </div>
        </div>
        <div class="col-md-4">
                <div class="card h-100">
                    <img src="https://images.pexels.com/photos/33111972/pexels-photo-33111972.jpeg" class="card-img-top" alt="Bamyan, Afghanistan">
                    <div class="card-body">
                        <h5 class="card-title">Moai Statues of Easter Island</h5>
                        <p class="card-text">The Moai are monolithic human figures carved by the Rapa Nui people on Easter Island, a remote Polynesian island known to its inhabitants as Rapa Nu.hese massive stone statues primarily represent deified ancestors, including former chiefs. Nearly 1,000 moai have been found on the island, with many still located in the main quarry of the Rano Raraku volcano.</p>
                        <p><strong>Location:</strong>Rapa Nui (Easter Island), Chile</p>
                        <p><strong>Established:</strong>1250 and 1500 CE</p>
                    </div>
                </div>
            </div>
    </div>
</div>
<!--container-->
</body>
