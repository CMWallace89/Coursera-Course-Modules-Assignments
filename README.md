<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Nyla's Playhouse: Module 3 Assignment</title>
  <link rel="stylesheet" href="css/bootstrap.min.css">
  <link rel="stylesheet" href="css/style.css">
  <link href='https://fonts.googleapis.com/css?family=Oxygen:400,300,700' rel='stylesheet'>
  <link href="https://fonts.googleapis.com/css2?family=Playwrite+DE+VA:wght@100..400&display=swap" rel='stylesheet'>
  <style>
    /* Custom CSS inside HTML for testing */
    body {
      font-family: 'Playwrite DE VA', cursive;
      background-color: #A999EB;
      color: #D35E7F;
    }
    .section {
      border: 1px solid #000;
      background-color: #fff;
      padding: 15px;
      margin-bottom: 30px;
      position: relative;
      color: #000;
    }
    .section-title {
      position: absolute;
      top: 0;
      right: 0;
      background-color: #D35E7F;
      padding: 5px 10px;
      color: #fff;
      font-size: 75%;
    }
    /* Header Styles */
    .navbar-default {
      background-color: #fff;
    }
    #header-nav {
      background-color: #D7E97B;
    }
    #logo-img {
      background: url('Images/Ny's Playhouse.jpg') no-repeat;
      width: 150px;
      height: 150px;
      margin: 10px 15px 10px 0;
    }
    .navbar-brand h1 {
      font-family: 'Playwrite DE VA', cursive;
      color: #D35E7F;
      font-size: 1.5em;
      text-transform: uppercase;
      font-weight: bold;
      text-shadow: 1px 1px 1px #222;
    }
    .navbar-brand p {
      color: #000;
      text-transform: uppercase;
      font-size: .7em;
      margin-top: 15px;
    }
    .navbar-brand p img {
      vertical-align: middle;
    }
    #nav-list a {
      color: #D35E7F;
      text-align: center;
    }
    #nav-list a:hover {
      background: #E7E7E7;
    }
    #nav-list a:active {
      color: #D7E97B;
    }
    .container .jumbotron {
      box-shadow: 0 0 50px #A999EB;
      border: 2px solid #A999EB;
    }
  </style>
</head>
<body>
  <header>
    <nav id="header-nav" class="navbar navbar-default">
      <div class="container">
        <div class="navbar-header">
          <a href="index.html" class="pull-left visible-md visible-lg">
            <div id="logo-img"></div>
          </a>
          <div class="navbar-brand">
            <a href="index.html"><h1>Nyla's Playhouse</h1></a>
            <p>
              <img src="Images/Ny Cert.png" alt="Nyla certification">
              <span>Nyla Certified</span>
            </p>
          </div>
          <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
        </div>
        <div class="collapse navbar-collapse" id="collapsable-nav">
          <ul id="nav-list" class="nav navbar-nav navbar-right">
            <li>
              <a href="#">
              <span class="glyphicon glyphicon-heart"></span><br class="hidden-xs"> Playhouse Friends</a>
            </li>
            <li>
              <a href="#">
                <span class="glyphicon glyphicon-home"></span><br class="hidden-xs"> Playhouse Rules</a>
            </li>
            <li>
              <a href="#">
                <span class="glyphicon glyphicon-ice-lolly-tasted"></span><br class="hidden-xs"> Nyla's Memories</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
  <div class="container">
    <h1 class="text-center">Playhouse Friends</h1>
    <div class="row">
      <div class="col-lg-4 col-md-6 col-xs-12">
        <div class="section" id="puppies">
          <div class="section-title">Puppies</div>
          <p>Meet the epitome of boundless energy and unconditional love. Puppies, with their fluffy fur and wagging tails, bring an infectious joy to every corner they explore. Whether they're playfully chasing after a ball or cuddled up for a nap, their adorable antics warm hearts and make even the toughest day brighter.</p>
        </div>
      </div>
      <div class="col-lg-4 col-md-6 col-xs-12">
        <div class="section" id="kittens">
          <div class="section-title">Kittens</div>
          <p>Soft purrs and mischievous eyes define the charm of kittens. With their playful pounces and graceful stretches, these tiny felines effortlessly weave their way into our lives. From exploring new heights to curling up in cozy corners, their curiosity and independence shine through, capturing hearts with each whisker twitch.</p>
        </div>
      </div>
      <div class="col-lg-4 col-md-12 col-xs-12">
        <div class="section" id="fish">
          <div class="section-title">Fish</div>
          <p>Beneath the shimmering surface of an aquatic world, fish glide with elegance and tranquility. From the vibrant hues of tropical fish to the serene movements of koi in a pond, each species tells a tale of underwater grace. Their tranquil presence and mesmerizing beauty bring a sense of peace and wonder, inviting us to glimpse a world of silent enchantment below the waves.</p>
        </div>
      </div>
    </div>
  </div>
  <div id="main-content" class="container">
    <div class="jumbotron">
      <img src="Images/Ny's Playhouse.jpg" alt="Nyla's Playhouse" class="img-responsive visible-xs">
    </div>
  </div>
  <!-- jQuery (Bootstrap JS plugins depend on it) -->
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <script src="js/script.js"></script>
</body>
</html>

