<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>TinDog</title>
  <script src="https://kit.fontawesome.com/4f9ff9a3d7.js" crossorigin="anonymous"></script>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;900&family=Ubuntu&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="css/styles.css">
  <link rel="stylesheet" href="href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.0.0/animate.min.css"">
</head>

<body>

  <section id="title">
    <div class="container-fluid">



      <!-- Nav Bar -->
      <nav class="navbar  navbar-expand-lg navbar-dark">
        <a class="navbar-brand" href="">tindog</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link" href="#footer">Contact</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#pricing">Pricing</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#cta">Download</a>
            </li>
          </ul>
        </div>
      </nav>



      <!-- Title -->
      <div class="row">


        <div class="col-lg-6">
          <h1>Meet new and interesting dogs nearby.</h1>
          <button type="button" class="btn btn-dark btn-lg download-btn"><i class="fab fa-apple"></i> Download</button>
          <button type="button" class="btn btn-outline-light btn-lg download-btn"><i class="fab fa-google-play"></i></i> Download</button>
        </div>
        <div class="col-lg-6">
          <img src="images/iphone6.png" alt="iphone-mockup" class="title-image">
        </div>
      </div>
    </div>
  </section>


  <!-- Features -->

  <section id="features">
    <div class="row features-padding ">

      <div class="col-lg-4  feature">
        <h1><i class="fas fa-check-circle"></i></h1>
        <h3>Easy to use.</h3>
        <p>So easy to use, even your dog could do it.</p>
      </div>

      <div class="col-lg-4  feature">
        <h1><i class="fas fa-bullseye"></i></h1>
        <h3>Elite Clientele</h3>
        <p>We have all the dogs, the greatest dogs.</p>
      </div>

      <div class="col-lg-4  feature">
        <h1><i class="fas fa-heart"></i></h1>
        <h3>Guaranteed to work.</h3>
        <p>Find the love of your dog's life or your money back.</p>
      </div>

    </div>

  </section>


  <!-- Testimonials -->

  <section id="testimonials">
    <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <h1 class="">I no longer have to sniff other dogs for love. I've found the hottest Corgi on TinDog. Woof.</h1>
          <img class="testimonial-image" src="images/dog-img.jpg" alt="dog-profile">
          <em>Pebbles, New York</em>
        </div>
        <div class="carousel-item ">
          <h1 class=" ">My dog used to be so lonely, but with TinDog's help, they've found the love of their life. I think.</h1>
          <img class="testimonial-image" src="images/lady-img.jpg" alt="lady-profile">
          <em>Beverly, Illinois</em>

        </div>
      </div>
      <a class="carousel-control-prev " href="#carouselExampleControls" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>

  </section>


  <!-- Press -->

  <section id="press">
    <img class="press-logo" src="images/techcrunch.png" alt="tc-logo">
    <img class="press-logo" src="images/tnw.png" alt="tnw-logo">
    <img class="press-logo" src="images/bizinsider.png" alt="biz-insider-logo">
    <img class="press-logo" src="images/mashable.png" alt="mashable-logo">

  </section>


  <!-- Pricing -->

  <section id="pricing">

    <h2 class="price-head">A Plan for Every Dog's Needs</h2>
    <p class="price-head">Simple and affordable price plans for your and your dog.</p>
 <div class="row">
      <div class="col-lg-4 col-md-6">


      <div class="card">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <div class="card-header">
        <h3>Chihuahua</h3>
        </div>
        <div class="card-body">
          <h2>Free</h2>
          <p>5 Matches Per Day</p>
          <p>10 Messages Per Day</p>
          <p>Unlimited App Usage</p>
          <button type="button" class="btn btn-outline-dark btn-lg btn-block">Sign Up</button>
        </div>
      </div>

</div>

  <div class="col-lg-4 col-md-6">
<div class="card ">
  <span></span>
  <span></span>
  <span></span>
  <span></span>
<div class="card-header ">
<h3>Labrador</h3>
</div>
<div class="card-body">
 <h2>$49 / mo</h2>
 <p>Unlimited Matches</p>
 <p>Unlimited Messages</p>
 <p>Unlimited App Usage</p>
 <button type="button" class="btn btn-dark btn-lg btn-block">Sign Up</button>
</div>
</div>
</div>
  <div class="col-lg-4 col-md-12">
  <div class="card ">
    <span></span>
    <span></span>
    <span></span>
    <span></span>
  <div class="card-header">
  <h3>Mastiff</h3>
  </div>
  <div class="card-body">
    <h2>$99 / mo</h2>
    <p>Pirority Listing</p>
    <p>Unlimited Matches</p>
    <p>Unlimited Messages</p>
    <p>Unlimited App Usage</p>
    <button type="button" class="btn btn-dark btn-lg btn-block ">Sign Up</button>
   </div>
  </div>
  </div>
  </div>

  </section>


  <!-- Call to Action -->

  <section id="cta">

    <h3 class="span"><span></span>Find the True Love of Your Dog's Life Today.</h3>
    <button type="button" class="btn btn-dark btn-cta"><i class="fab fa-apple"></i> Download</button>
    <button type="button" class="btn btn-light btn-cta"><i class="fab fa-google-play"></i></i> Download</button>

  </section>


  <!-- Footer -->

  <footer id="footer">
    <i class="fab fa-instagram"></i>
    <i class="fab fa-facebook"></i>
    <i class="fab fa-twitter"></i>
    <i class="fab fa-linkedin-in"></i>
    <p>© Copyright 2018 TinDog</p>

  </footer>


</body>

</html>
