# Website-dev
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewpoint" content="width=device-width, initial-scale=1.0">
   <link href="https://fonts.googleapis.com/css2?family=Viaoda+Libre&display=swap" rel="stylesheet">
<style>
   h1, .overlay-text {
      font-family: "Viaoda Libre", serif;
      letter-spacing: 1px;
      }
   h1 {
      font-size: 48px;
      font-weight: 400;
      }
   .overlay-text {
      font-size: 28px;
      letter-spacing: 2px;
      }
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

        <a href="Gallery.html" class="image-container">
    <img src="IMG_4772.jpeg" alt="Gallery"> <div class="overlay-text">Gallery</div></a> 

         <a href="Contact.html" class="image-container">
    <img src="IMG_4800.jpeg" alt="Contact">
    <div class="overlay-text">Contact</div>
          </a>

        <a href="About.html" class="image-container"> 
    <img src="IMG_4760.jpeg" alt="About Me">
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
      
