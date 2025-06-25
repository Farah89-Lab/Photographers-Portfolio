<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Photographer Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Photographer</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#gallery">Gallery</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <section id="home" class="py-5 text-center bg-light">
        <div class="container">
            <h1 class="display-4">Welcome to My Portfolio</h1>
            <p class="lead">Capturing moments from today... Creating memories for a lifetime.</p>
        </div>
    </section>
    <section id="gallery" class="py-5">
        <div class="container">
            <h2 class="mb-4 text-center">Gallery</h2>
            <div class="row">
                <div class="col-md-4 mb-4">
                    <a href="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=800&q=80" data-bs-toggle="modal" data-bs-target="#lightboxModal" data-img="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=800&q=80">
                        <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=400&q=80" class="img-fluid rounded gallery-img" alt="Sample 1">
                    </a>
                </div>
                <div class="col-md-4 mb-4">
                    <a href="https://images.unsplash.com/photo-1465101046530-73398c7f28ca?auto=format&fit=crop&w=800&q=80" data-bs-toggle="modal" data-bs-target="#lightboxModal" data-img="https://images.unsplash.com/photo-1465101046530-73398c7f28ca?auto=format&fit=crop&w=800&q=80">
                        <img src="https://images.unsplash.com/photo-1465101046530-73398c7f28ca?auto=format&fit=crop&w=400&q=80" class="img-fluid rounded gallery-img" alt="Sample 2">
                    </a>
                </div>
                <div class="col-md-4 mb-4">
                    <a href="https://images.unsplash.com/photo-1519125323398-675f0ddb6308?auto=format&fit=crop&w=800&q=80" data-bs-toggle="modal" data-bs-target="#lightboxModal" data-img="https://images.unsplash.com/photo-1519125323398-675f0ddb6308?auto=format&fit=crop&w=800&q=80">
                        <img src="https://images.unsplash.com/photo-1519125323398-675f0ddb6308?auto=format&fit=crop&w=400&q=80" class="img-fluid rounded gallery-img" alt="Sample 3">
                    </a>
                </div>
            </div>
        </div>
    </section>
    <!-- Lightbox Modal -->
    <div class="modal fade" id="lightboxModal" tabindex="-1" aria-labelledby="lightboxModalLabel" aria-hidden="true">
      <div class="modal-dialog modal-dialog-centered">
        <div class="modal-content bg-transparent border-0">
          <h2 id="lightboxModalLabel" class="visually-hidden">Image Preview</h2>
          <img id="lightboxImage" src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=800&q=80" class="img-fluid rounded shadow" alt="Enlarged">
        </div>
      </div>
    </div>
    <section id="testimonials" class="py-5 bg-light">
        <div class="container">
            <h2 class="mb-4 text-center">Testimonials</h2>
            <div class="row justify-content-center">
                <div class="col-md-6">
                    <blockquote class="blockquote text-center">
                        <p class="mb-0">“Amazing photographer! Captured our wedding perfectly.”</p>
                        <footer class="blockquote-footer">Jane Doe</footer>
                    </blockquote>
                </div>
                <div class="col-md-6">
                    <blockquote class="blockquote text-center">
                        <p class="mb-0">“Professional and creative. Highly recommended.”</p>
                        <footer class="blockquote-footer">John Smith</footer>
                    </blockquote>
                </div>
            </div>
        </div>
    </section>
    <section id="resume" class="py-5">
        <div class="container text-center">
            <h2 class="mb-4">Resume</h2>
            <a href="resume.pdf" class="btn btn-outline-primary" download>Download My Resume</a>
        </div>
    </section>
    <section id="map" class="py-5 bg-light">
        <div class="container">
            <h2 class="mb-4 text-center">Find Me</h2>
            <div class="row justify-content-center">
                <div class="col-md-8">
                    <div class="ratio ratio-16x9">
                        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3151.835434509374!2d144.9537363153169!3d-37.81627977975171!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6ad65d43f1f1f1f1%3A0x5045675218ce6e0!2sMelbourne%20VIC%2C%20Australia!5e0!3m2!1sen!2sus!4v1620000000000!5m2!1sen!2sus" title="Photographer Location" allowfullscreen="" loading="lazy"></iframe>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <footer class="bg-dark text-white text-center py-3">
        <div class="mb-2">
            <a href="https://facebook.com/" class="text-white me-3" title="Facebook" target="_blank" rel="noopener"><i class="bi bi-facebook"></i> <span class="visually-hidden">Facebook</span></a>
            <a href="https://instagram.com/" class="text-white me-3" title="Instagram" target="_blank" rel="noopener"><i class="bi bi-instagram"></i> <span class="visually-hidden">Instagram</span></a>
            <a href="https://twitter.com/" class="text-white me-3" title="Twitter" target="_blank" rel="noopener"><i class="bi bi-twitter"></i> <span class="visually-hidden">Twitter</span></a>
            <a href="https://linkedin.com/" class="text-white" title="LinkedIn" target="_blank" rel="noopener"><i class="bi bi-linkedin"></i> <span class="visually-hidden">LinkedIn</span></a>
        </div>
        &copy; 2025 Photographer Portfolio
        <button id="backToTop" class="btn btn-outline-light btn-sm ms-3">Back to Top</button>
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.js"></script>
    <script>
    // Lightbox functionality
    const lightboxModal = document.getElementById('lightboxModal');
    const lightboxImage = document.getElementById('lightboxImage');
    document.querySelectorAll('.gallery-img').forEach(img => {
        img.parentElement.addEventListener('click', function(e) {
            e.preventDefault();
            lightboxImage.src = this.getAttribute('data-img');
        });
    });
    // Back to Top button
    const backToTop = document.getElementById('backToTop');
    window.onscroll = function() {
        if (document.body.scrollTop > 200 || document.documentElement.scrollTop > 200) {
            backToTop.style.display = 'inline-block';
        } else {
            backToTop.style.display = 'none';
        }
    };
    backToTop.onclick = function() {
        window.scrollTo({top: 0, behavior: 'smooth'});
    };
    </script>
