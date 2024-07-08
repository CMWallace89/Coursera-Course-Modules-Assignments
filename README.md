<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Nyla's Playhouse: Module 4 Assignment</title>
  <link rel="stylesheet" href="css/bootstrap.min.css">
  <link rel="stylesheet" href="css/style.css">
  <link href='https://fonts.googleapis.com/css?family=Oxygen:400,300,700' rel='stylesheet' type='text/css'>
  <link href="https://fonts.googleapis.com/css2?family=Playwrite+DE+VA:wght@100..400&display=swap" rel='stylesheet' type='text/css'>
  <style>
    /* Base styles */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Playwrite DE VA', cursive;
      font-size: 16px;
      background-color: #A999EB; /* Max Blue Purple */
      color: #D35E7F; /* Cinnamon Satin */
      padding: 20px;
    }

    h1 {
      margin-bottom: 20px;
      text-align: center;
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
      background-color: #D35E7F; /* Cinnamon Satin */
      padding: 5px 10px;
      color: #fff;
      font-size: 75%;
    }

    p {
      margin-top: 25px;
    }

    /* Additional styles */
    .navbar-default {
      background-color: #fff;
    }

    .navbar-toggle {
      float: right;
      margin-right: 10px;
    }

    .navbar-brand {
      float: left;
    }

    /* Header */
    #header-nav {
      background-color: #D7E97B; /* Manz */
      border-radius: 0;
      border: 0;
    }

    #logo-img {
      background: url('../Images/Ny's Playhouse.jpg') no-repeat;
      width: 150px;
      height: 150px;
      margin: 10px 15px 10px 0;
    }

    .navbar-brand {
      padding-top: 25px;
    }

    .navbar-brand h1 { /* Page Name */
      font-family: "Playwrite DE VA", cursive;
      color: #D35E7F; /* Cinnamon Satin */
      font-size: 1.5em;
      text-transform: uppercase;
      font-weight: bold;
      text-shadow: 1px 1px 1px #222;
      margin-top: 0;
      margin-bottom: 0;
      line-height: .75;
    }

    .navbar-brand a:hover, .navbar-brand a:focus {
      text-decoration: none;
    }

    .navbar-brand p { /* Nyla cert */
      color: #000;
      text-transform: uppercase;
      font-size: .7em;
      margin-top: 15px;
    }

    .navbar-brand p span { /* Nyla Cert Pic */
      vertical-align: middle;
    }

    #nav-list {
      margin-top: 10px;
    }

    #nav-list a {
      color: #D35E7F; /* Cinnamon Satin */
      text-align: center;
    }

    #nav-list a:hover {
      background: #E7E7E7;
    }

    #nav-list a:active {
      color: #D7E97B; /* Manz */
    }

    #nav-list a span {
      font-size: 1.8em;
    }

    .navbar-header button.navbar-toggle, .navbar-header .icon-bar {
      border: 1px solid #D35E7F; /* Cinnamon Satin */
    }

    .navbar-header button.navbar-toggle {
      clear: both;
      margin-top: -30px;
    }

    /* Main content */
    .container .jumbotron {
      box-shadow: 0 0 50px #A999EB; /* Max Blue Purple */
      border: 2px solid #A999EB; /* Max Blue Purple */
    }

    /* Media Queries */
    /********** Large devices only **********/
    @media (min-width: 1200px) {
      .container .jumbotron {
        background: url('../Images/Ny's Playhouse 1200.jpg') no-repeat;
        height: 675px;
      }
    }

    /********** Medium devices only **********/
    @media (min-width: 992px) and (max-width: 1199px) {
      /* Header */
      #logo-img {
        background: url('../Images/Ny's Playhouse 992.jpg') no-repeat;
        width: 100%;
        height: 100px;
        margin: 5px 5px 5px 0;
      }
      /* End Header */
      .container .jumbotron {
        background: url('../Images/Ny's Playhouse 992.jpg') no-repeat;
        height: 575px;
      }
    }

    /********** Small devices only **********/
    @media (max-width: 991px) {
      .navbar-brand h1 {
        font-size: 1.2em;
      }

      .container .jumbotron {
        background: url('../Images/Ny's Playhouse 768.jpg') no-repeat;
        height: 375px;
      }

      .navbar-brand p {
        font-size: .6em;
        margin-top: 12px;
      }

      .navbar-brand p img {
        height: 20px;
      }

      #collapsable-nav a {
        font-size: 1.2em;
      }

      #collapsable-nav a span {
        font-size: 1em;
        margin-right: 5px;
      }

      .container .jumbotron {
        margin-top: 30px;
        padding: 0;
      }
    }
  </style>
</head>
<body>
  <header>
    <nav id="header-nav" class="navbar navbar-default">
      <div class="container">
        <div class="navbar-header">
          <a href="index.html" class="pull-left visible-md visible-lg">
            <div id="logo-img" alt="Logo image"></div>
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
      <img src="" alt="Nyla's Playhouse" class="img-responsive visible-xs">
    </div>
  </div>
  <!-- jQuery (Bootstrap JS plugins depend on it) -->
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <script src="js/script.js"></script>
</body>
</html>

