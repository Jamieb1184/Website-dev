# Website-dev
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewpoint" content="width=device-width, initial-scale=1.0">
   <style>
      .image-row {
  display: flex;
  justify-content: space-between;
  gap: 20px;
}

.image-container {
  position: relative;
  width: 30%;
  text-decoration: none;
  overflow: hidden; /* keeps cropping clean */
}

.image-container img {
  width: 100%;
  height: 300px;
  object-fit: cover;
  opacity: 0.3;
  display: block;
  transition: opacity 0.3s ease;
}

.image-container:hover img {
  opacity: 1;
}

.overlay-text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
  font-size: 24px;
  font-weight: bold;
  text-align: center;
  pointer-events: none;
}

/* Mobile */
@media (max-width: 768px) {
  .image-row {
    flex-direction: column;
  }

  .image-container {
    width: 100%;
  }

  .image-container img {
    height: 200px;
  }
  footer {
  margin-top: 40px;
  padding: 20px;
  text-align: center;
  background-color: #111;
  color: white;
}

footer a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
}

footer a:hover {
  text-decoration: underline;
}
   </style>
</head>
<body>
    <h1>Jamie Baker - Music Photographer</h1>
    <div class="image-row">

        <a href="gallery.html" class="image-container"><img src="" alt="Gallery"> <div           class="overlay-text">Gallery</div></a> 

         <a href="contact.html" class="image-container">
    <img src="" alt="Contact">
    <div class="overlay-text">Contact</div>
          </a>

        <a href="about.html" class="image-container"> 
    <img src="" alt="About Me">
    <div class="overlay-text">About Me</div>
        </a>

  </div>
<footer>
   <p>
      &copy; 2026 Jamie Baker
      <a href="https://www.instagram.com/j.bakermedia" target="_blank">Instagram</a>
   </p>
</footer>
</body>
</html>
   </p>
</footer>
      
