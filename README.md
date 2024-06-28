<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Module 2 Layout</title>
<link rel="stylesheet" href="css/style.css">
<style>
/* Base styles */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  background-color: #f0f0f0;
  padding: 20px;
}

h1 {
  margin-bottom: 20px;
  text-align: center;
}

.row {
  display: flex;
  flex-wrap: wrap;
  margin: 0 -15px;
}

.col-lg-4 {
  flex: 0 0 auto;
  width: 33.33%;
  padding: 0 15px;
}

.col-md-6 {
  flex: 0 0 auto;
  width: 50%;
  padding: 0 15px;
}

.col-md-12 {
  flex: 0 0 auto;
  width: 100%;
  padding: 0 15px;
}

.section {
  border: 1px solid #000;
  background-color: #A999EB;
  padding: 15px;
  margin-bottom: 30px;
  position: relative;
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

p {
  margin-top: 25px;
}

/* Media Queries */
@media (max-width: 992px) {
  .col-lg-4 {
    width: 50%;
  }
}

@media (min-width: 768) and (max-width: 991px) {
  .col-lg-4, .col-md-6, .col-md-12 {
    width: 100%;
  }
}
</style>
</head>
<body>
<h1>Module 2 Layout</h1>

<div class="row">
  <div class="col-lg-4 col-md-6">
    <div class="section">
      <div class="section-title">Puppies</div>
      <p>Meet the epitome of boundless energy and unconditional love. Puppies, with their fluffy fur and wagging tails, bring an infectious joy to every corner they explore. Whether they're playfully chasing after a ball or cuddled up for a nap, their adorable antics warm hearts and make even the toughest day brighter.</p>
    </div>
  </div>
  <div class="col-lg-4 col-md-6">
    <div class="section">
      <div class="section-title">Kittens</div>
      <p>Soft purrs and mischievous eyes define the charm of kittens. With their playful pounces and graceful stretches, these tiny felines effortlessly weave their way into our lives. From exploring new heights to curling up in cozy corners, their curiosity and independence shine through, capturing hearts with each whisker twitch.</p>
    </div>
  </div>
  <div class="col-lg-4 col-md-12">
    <div class="section">
      <div class="section-title">Fish</div>
      <p>Beneath the shimmering surface of an aquatic world, fish glide with elegance and tranquility. From the vibrant hues of tropical fish to the serene movements of koi in a pond, each species tells a tale of underwater grace. Their tranquil presence and mesmerizing beauty bring a sense of peace and wonder, inviting us to glimpse a world of silent enchantment below the waves.</p>
    </div>
  </div>
</div>

</body>
</html>

