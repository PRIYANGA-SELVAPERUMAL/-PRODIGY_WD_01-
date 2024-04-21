# -PRODIGY_WD_01-
RESPONSIVE LANDING PAGE

<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Mera Virtual Hub</title>
 <style>
 body {
 font-family: 'Open Sans', sans-serif;
 font-size: 18px;
 font-weight: 400;
 text-decoration: none;
 background-color: #FFC0CB;
 transition: background-color 0.5s ease;
 }

 body:hover {
 background-color: #87CEEB;
 }

 #navbar {
 background-color: #FFC0CB;
 transition: background-color 0.5s ease;
 }

 #navbar:hover {
 background-color: #87CEEB;
 }

 .jumbotron {
 height: 100vh;
 display: flex;
 align-items: center;
 background-color: #FFC0CB;
 color: #333;
 }

 .jumbotron h1 {
 font-size: 5rem;
 margin-bottom: 1rem;
 }

 .jumbotron p {
 font-size: 2rem;
 margin-bottom: 3rem;
 }

 .container {
 padding: 3rem 1.5rem;
 background-color: #FFC0CB;
 }

 .container h2 {
 font-size: 3rem;
 margin-bottom: 3rem;
 color: #333;
 }

 .container p {
 font-size: 1.5rem;
 color: #333;
 }

 .container a {
 color: #333;
 text-decoration: none;
 transition: color 0.3s ease;
 }

 .container a:hover {
 color: #FFC0CB;
 background-color: #FFC0CB;
 }

 h1, h2, h3, h4, h5, h6 {
 font-family: 'Roboto', sans-serif;
 font-weight: 700;
 text-transform: uppercase;
 letter-spacing: 1px;
 }

 a {
 color: #FFC0CB;
 text-decoration: underline;
 transition: color 0.3s ease;
 }

 a:hover {
 color: #333;
 }

 .form-control {
 width: 100%;
 padding: 0.5rem;
 margin-bottom: 1rem;
 }

 .btn-primary {
 width: 100%;
 padding: 0.5rem;
 }

 @media (max-width: 767px) {
 .jumbotron h1 {
 font-size: 3rem;
 }

 .jumbotron p {
 font-size: 1.5rem;
 }

 .container h2 {
 font-size: 2rem;
 }

 .container p {
 font-size: 1.2rem;
 }
 }
 </style>
</head>
<body>
 <nav id="navbar" class="navbar navbar-expand-lg navbar-light bg-light">
 <div class="container-fluid">
 <a class="navbar-brand" href="#">Mera Virtual Hub</a>
 <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
 <span class="navbar-toggler-icon"></span>
 </button>
 <div class="collapse navbar-collapse" id="navbarNav">
 <ul class="navbar-nav">
 <li class="nav-item">
 <a class="nav-link" href="#home">Home</a>
 </li>
 <li class="nav-item">
 <a class="nav-link" href="#offerings">Our Offerings</a>
 </li>
 <li class="nav-item">
 <a class="nav-link" href="#about">About Us</a>
 </li>
 <li class="nav-item">
 <a class="nav-link" href="#contact">Contact Us</a>
 </li>
 </ul>
 </div>
 </div>
 </nav>
 <header class="jumbotron bg-cover text-white">
 <div class="container text-center">
 <h1 class="display-4">Hello and welcome to Mera Virtual Hub!</h1>
 <p class="lead">Step into a boundless realm of opportunities, where innovation intertwines seamlessly with connectivity. Here, exploration knows no bounds, connections flourish, and growth is inevitable. Join us as we venture together into this captivating journey, where every step unveils new horizons and every moment ignites possibility. Let's embrace the adventure, hand in hand, and unlock the limitless potential that awaits. Together, let's sculpt a future defined by innovation, connectivity, and shared success.</p>
 </div>
 </header>
 <section id="offerings" class="container">
 <h2 class="text-center mb-5">Our Offerings</h2>
 <div class="row">
 <div class="col-md-4 text-center">
 <h3>Web Design</h3>
 <p>Crafting visually captivating and easy-to-navigate websites.</p>
 </div>
 <div class="col-md-4 text-center">
 <h3>Mobile Development</h3>
 <p>Developing dynamic mobile applications optimized for all devices.</p>
 </div>
 <div class="col-md-4 text-center">
 <h3>Digital Marketing</h3>
 <p>Enhancing online presence and fostering growth through strategic marketing efforts.</p>
 </div>
 </div>
 </section>
 <section id="about" class="container">
 <h2 class="text-center mb-5">About Us</h2>
 <div class="row">
 <div class="col-md-6">
 <p>Mera Virtual Hub is more than just a team; we're a collective of passionate web professionals on a mission to redefine the digital landscape. With a deep-seated commitment to excellence, we craft extraordinary digital solutions that transcend expectations.</p>
 <p>At the heart of our ethos lies a dedication to innovation and customer satisfaction. We believe in the transformative power of technology and design, and we harness this belief to propel businesses forward in the digital age.</p>
 <p>Driven by a shared vision of excellence, our diverse team brings together expertise from various domains to deliver holistic digital solutions tailored to meet the unique needs of each client. From captivating web design to seamless mobile development and strategic digital marketing, we offer a comprehensive suite of services designed to elevate your online presence and drive tangible results.</p>
 <p>Our relentless pursuit of perfection is fueled by a genuine desire to see our clients succeed. We understand the challenges of navigating the digital landscape, and we're here to provide the guidance and support needed to thrive in an ever-evolving online world.</p>
 <p>With Mera Virtual Hub as your trusted partner, you can rest assured that your digital aspirations are in capable hands. Let us be the catalyst for your success as we embark on this exciting journey together.</p>
 </div>
 </div>
 </section>
 <section id="contact" class="container">
 <h2 class="text-center mb-5">Contact Us</h2>
 <div class="row">
 <div class="col-md-6">
 <form>
 <div class="mb-3">
 <label for="name" class="form-label">Name</label>
 <input type="text" class="form-control" id="name" placeholder="Your Name">
 </div>
 <div class="mb-3">
 <label for="email" class="form-label">Email</label>
 <input type="email" class="form-control" id="email" placeholder="Your Email">
 </div>
 <div class="mb-3">
 <label for="query" class="form-label">Query</label>
 <textarea class="form-control" id="query" rows="3" placeholder="Your Query"></textarea>
 </div>
 <div class="mb-3">
 <label for="phone" class="form-label">Contact Number</label>
 <input type="text" class="form-control" id="phone" placeholder="Your Contact Number">
 </div>
 <button type="submit" class="btn btn-primary">Submit</button>
 </form>
 </div>
 <div class="col-md-6">
 <p>Don't hesitate to contact us to discuss your project or inquire about our services.<p>
 <p>We're excited to hear from you!</p>
 <p>Email: <a href="mailto:info@meravirtualhub.com">info@meravirtualhub.com</a></p>
 <p>Phone: <a href="tel:+1234567890">+1234567890</a></p>
 </div>
 </div>
 </section>
</body>
</html>
