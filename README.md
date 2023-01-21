# frontend-mentor

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./assets/images/favicon-32x32.png">
  <link rel="stylesheet" href="css/styles.css">
  <link rel="stylesheet" href="Inter-Bold.ttf">
  <link rel="stylesheet" href="Inter-ExtraBold.ttf">
  <link rel="stylesheet" href="Inter-Regular.ttf">

  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

  <title>Frontend Mentor | News homepage</title>

  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
</head>

<body>

  <div class="container-top">
    <svg class="svg" width="65" height="40" xmlns="http://www.w3.org/2000/svg">
      <path
        d="M23.016 39.2c.317 0 .574-.093.77-.28.196-.187.294-.457.294-.812v-1.82c0-.448.033-.84.098-1.176.065-.336.145-.663.238-.98l5.09-18.122 4.822 18.57c.112.384.193.682.243.895l.023.099c.047.215.07.453.07.714v1.82c0 .355.098.625.294.812.196.187.453.28.77.28h10.696c.299 0 .55-.093.756-.28.205-.187.308-.457.308-.812v-1.82c0-.373.023-.705.07-.994.047-.29.135-.677.266-1.162L54.04 7.224c.299-1.25.765-2.254 1.4-3.01.635-.756 1.363-1.311 2.184-1.666l.672-.308c.336-.168.574-.331.714-.49.14-.159.21-.369.21-.63 0-.336-.117-.607-.35-.812C58.637.103 58.287 0 57.82 0h-8.904c-.467 0-.817.103-1.05.308-.233.205-.35.476-.35.812 0 .261.06.471.182.63.121.159.313.303.574.434l.616.224c1.12.41 1.871.999 2.254 1.764s.453 1.661.21 2.688l-5.535 23.486-6.477-25.81c-.133-.58-.17-1.018-.11-1.31l.026-.104c.093-.29.317-.49.672-.602l1.232-.336c.299-.112.518-.257.658-.434a.986.986 0 0 0 .21-.63c0-.355-.112-.63-.336-.826C41.468.098 41.122 0 40.656 0H24.78c-.448 0-.789.098-1.022.294-.233.196-.35.471-.35.826 0 .224.06.415.182.574.121.159.322.294.602.406l1.176.42c.261.093.462.243.602.448.14.205.294.607.462 1.204l1.751 6.742-5.553 19.475L16.128 4.48c-.147-.49-.194-.898-.14-1.223l.028-.135c.093-.345.327-.574.7-.686l1.456-.336c.504-.168.756-.504.756-1.008 0-.336-.112-.602-.336-.798C18.368.098 18.022 0 17.556 0H1.344C.896 0 .56.098.336.294.112.49 0 .756 0 1.092c0 .224.056.434.168.63.112.196.29.35.532.462l1.232.392c.355.13.625.308.812.532.187.224.345.579.476 1.064l7.84 30.408c.112.43.191.751.238.966.047.215.07.462.07.742v1.82c0 .355.103.625.308.812.205.187.467.28.784.28h10.556Zm34.804.7c1.195 0 2.263-.29 3.206-.868a6.338 6.338 0 0 0 2.24-2.338c.55-.98.826-2.04.826-3.178 0-1.157-.275-2.212-.826-3.164a6.325 6.325 0 0 0-2.24-2.282c-.943-.57-2.011-.854-3.206-.854-1.157 0-2.207.285-3.15.854a6.325 6.325 0 0 0-2.24 2.282c-.55.952-.826 2.007-.826 3.164 0 1.139.275 2.198.826 3.178.55.98 1.297 1.76 2.24 2.338.943.579 1.993.868 3.15.868Z"
        fill="#00001A" />
    </svg>

    <div class="top-link">
      <a class="top-link" href="#">Home</a>
      <a class="top-link" href="#">New</a>
      <a class="top-link" href="#">Popular</a>
      <a class="top-link" href="#">Trending</a>
      <a class="top-link" href="#">Categories</a>
    </div>
  </div>



  <section id="img-section">

    <section>
      <div class="products">
        <div class="products-item">
          <h2 class="new">New</h2>
          <a href="" class="container-link">Hydrogen VS Electric cars</a>
          <p>Will hydrogen-fueled cars ever catch up to EVs?</p>
          <hr class="hr">
          <a href="" class="container-link">The Down Sides Of Al Artistry</a>
          <p>What are the possible adverse effects of <br> on-demand AI image generation?</p>
          <hr class="hr">
          <a href="" class="container-link">Is VC Funding Drying Up?</a>
          <p>Private funding by VC firms is down 50% <br> YOY. We take a look at what that means.</p>
        </div>
      </div>
    </section>

    <div class="first-img">
      <img src=".\assets\images\image-web-3-desktop.jpg" alt="img">
    </div>

    <div class="bright-class">
      <h1 class="Bright">The Bright <br> Future Of <br> Web 3.0?</h1>
      <p>We dive into the next evolutionof the web that <br> claims to put the power of the platforms back <br> into the hands of the people. But is it really <br> fulfilling its promise? <br> </p>
      <a href="#" <button type="button" name="button" class="button" href="#">READ MORE</button></a>
    </div>

  </section>


  <section>
    <div class="grid-container row">
      <div class="one col-lg-4 col-md-6 col-sm-12">
        <img class="bottom-img" src="assets\images\image-retro-pcs.jpg" alt="">
        <h2 class="num-1">01</h2>
        <a href="#" class="features">Reviving Retro PCs</a>
        <p>What happens when old pcs <br> are given modern upgrades?</p>
      </div>

      <div class="two col-lg-4 col-md-6 col-sm-12">
        <img class="bottom-img" src="assets\images\image-top-laptops.jpg" alt="">
        <h2 class="num-2">02</h2>
        <a href="#" class="features">Top 10 Laptops of 2022</a>
        <p>Our best picks for various <br> needs and budgets.</p>
      </div>

      <div class="three col-lg-4 col-md-12 col-sm-12">
        <img class="bottom-img" src="assets\images\image-gaming-growth.jpg" alt="">
        <h2 class="num-3">03</h2>
        <a href="#" class="features">The Growth Of Gaming</a>
        <p>How the pandemic has sparked <br> fresh opportunities.</p>
      </div>
    </div>

  </section>

</body>

</html>
