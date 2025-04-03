<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sport Car</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="/css/main.css">
    <!-- <link rel="stylesheet" href="/css/tabe.css"> -->

</head>
<body>
  <header>
   
    <nav class="navbar navbar-expand-sm bg-white navbar-light">
  
</div>
        <div class="container">  <!--use container to define the width of the navbar content -->
          <img src="/images/shopping-bag-icon.png" alt="">
          <a class="navbar-brand d-flex align-items-center" href="#"> <!--use for padding ps & pt -->
            <span>Sport Car</span></a>
            <div class = "order-lg-2 nav-btns">
              <button type = "button" class = "btn position-relative">
                  <i class = "fa fa-shopping-cart"></i>
                  <span class = "position-absolute top-0 start-100 translate-middle badge bg-danger">5</span>
              </button>
              <button type = "button" class = "btn position-relative">
                  <i class = "fa fa-heart"></i>
                  <span class = "position-absolute top-0 start-100 translate-middle badge bg-danger">2</span>
              </button>
              <button type = "button" class = "btn position-relative">
                  <i class = "fa fa-search"></i>
              </button>
          </div>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#collapsibleNavbar">
            <span class="navbar-toggler-icon"></span>
          </button>
          
          <div class="collapse navbar-collapse justify-content-center" id="collapsibleNavbar"> <!-- //use justify-content-end to align the content to the right-->
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link " href="#">HOME</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">COLLECTION</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">BLOG</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">ABOUT US</a>
              </li>
            </ul>
          </div>
        </div>
        <!-- <div class="slide">
          <p>Testing and Test</p>
          <h1>Hey You why are u..</h1>
        </div> -->
      </nav>   
   <!-- Carousel -->
   <div id="demo" class="vh-100 carousel slide" data-bs-ride="carousel">

    <!-- Indicators/dots -->
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
      <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
      <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
    </div>
  
    <!-- The slideshow/carousel -->
    <div class="carousel-inner">
      <div class="carousel-item active">
        <!-- <img src="la.jpg" alt="Los Angeles" class="d-block w-100"> -->
        <div class="text-center slide-title text-light">
          <h2>Collection</h2>
          <h1>SUPPER SPORT</h1>
          <a href="" class="btn btn-outline-danger mt-3​ rounded-5 ps-4 pe-4">SHOP NOW</a>
          <!-- mt-3 ដកគម្លាតអក្សរ rounded-5 កោងក្នុងប្រអប់shop now  -->
        </div>
      </div>
      <div class="carousel-item">
        <!-- <img src="chicago.jpg" alt="Chicago" class="d-block w-100"> -->
        <div class="text-center slide-title text-light">
          <h2>SPORT</h2>
          <h1>NEW SEASON</h1>
          <a href="" class="btn btn-outline-danger mt-3​ rounded-5 ps-4 pe-4">SHOP NOW</a>
          <!-- mt-3 ដកគម្លាតអក្សរ rounded-5 កោងក្នុងប្រអប់shop now  -->
        </div>
      </div>
      <div class="carousel-item">
        
        <div class="text-center slide-title text-light">
          <h2>SPORT</h2>
          <h1>NEW SEASON</h1>
          <a href="" class="btn btn-outline-danger mt-3​ rounded-5 ps-4 pe-4">SHOP NOW</a>
          <!-- mt-3 ដកគម្លាតអក្សរ rounded-5 កោងក្នុងប្រអប់shop now  -->
        </div>
      </div>
    </div>
    <!-- Left and right controls/icons -->
    <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
      <span class="carousel-control-prev-icon"></span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
      <span class="carousel-control-next-icon"></span>
    </button>
  </header>  
  
  <div class="container">

    <h2 class ="text-center mt-5 mb-5">
      <span class="border-start border-3 border-danger ps-3"> Collection</span>
    </h2>

 <!-- Nav tabs -->
 <div class="justify-content-center d-flex">
  <ul class="nav nav-tabs border-0">
    <li class="nav-item">
      <a class="nav-link rounded-5 active" data-bs-toggle="tab" href="#All">All</a>
    </li>
    <li class="nav-item">
      <a class="nav-link rounded-5" data-bs-toggle="tab" href="#BestSeller">SUV</a>
    </li>
    <li class="nav-item">
      <a class="nav-link rounded-5" data-bs-toggle="tab" href="#Fealtured">PICK UP</a>
    </li>
    <li class="nav-item">
      <a class="nav-link rounded-5" data-bs-toggle="tab" href="#NewArrival">Sport</a>
    </li>
  </ul>
</div>

<!-- Tab panes -->
<div class="tab-content mt-5">
  <div class="tab-pane container active" id="All">
    <div class="row">
      <div class="col-lg-3">
        <div class="mb-4 shadow">
          <img src="/images/Luxury.jpg" alt="" class="img-fluid">
          <div class="text-center mt-4 pb-4">
            <p class="d-flex justify-content-center">
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-half-o fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-o fa-lg fa-star pe-2"></i>
            </p>
            <p>R1</p>
            <h4>$20.00</h4>
          </div>
        </div>
      </div>
      <div class="col-lg-3">
        <div class="mb-4 shadow">
          <img src="/images/up.jpg" alt="" class="img-fluid">
          <div class="text-center mt-4 pb-4">
            <p class="d-flex justify-content-center">
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-half-o fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-o fa-lg fa-star pe-2"></i>
            </p>
            <p>A2</p>
            <h4>$30</h4>
          </div>
        </div>
      </div>
      <div class="col-lg-3">
        <div class="mb-4 shadow">
          <img src="/images/suv.jpg" alt="" class="img-fluid">
          <div class="text-center mt-4 pb-4">
            <p class="d-flex justify-content-center">
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-half-o fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-o fa-lg fa-star pe-2"></i>
            </p>
            <p>w2</p>
            <h4>$2.00</h4>
          </div>
        </div>
      </div>
      <div class="col-lg-3">
        <div class="mb-4 shadow">
          <img src="/images/sport1.jpg" alt="" class="img-fluid">
          <div class="text-center mt-4 pb-4">
            <p class="d-flex justify-content-center">
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-half-o fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-o fa-lg fa-star pe-2"></i>
            </p>
            <p>f 1</p>
            <h4>$9</h4>
          </div>
        </div>
      </div>

    </div>
  </div>
  
  <div class="tab-pane container fade" id="BestSeller">

    <div class="row">
      <div class="col-lg-3">
        <div class="mb-4 shadow">
          <img src="/images/suv2.jpg" alt="" class="img-fluid">
          <div class="text-center mt-4 pb-4">
            <p class="d-flex justify-content-center">
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-half-o fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-o fa-lg fa-star pe-2"></i>
            </p>
            <p>77</p>
            <h4>$2</h4>
          </div>
        </div>
      </div>

      <div class="col-lg-3">
        <div class="mb-4 shadow">
          <img src="/images/suv3.jpg" alt="" class="img-fluid">
          <div class="text-center mt-4 pb-4">
            <p class="d-flex justify-content-center">
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-half-o fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-o fa-lg fa-star pe-2"></i>
            </p>
            <p>A78</p>
            <h4>$2050</h4>
          </div>
        </div>
      </div>

      <div class="col-lg-3">
        <div class="mb-4 shadow">
          <img src="/images/suv4.jpg" alt="" class="img-fluid">
          <div class="text-center mt-4 pb-4">
            <p class="d-flex justify-content-center">
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-half-o fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-o fa-lg fa-star pe-2"></i>
            </p>
            <p>A79</p>
            <h4>$2.30</h4>
          </div>
        </div>
      </div>

      <div class="col-lg-3">
        <div class="mb-4 shadow">
          <img src="/images/suv.jpg" alt="" class="img-fluid">
          <div class="text-center mt-4 pb-4">
            <p class="d-flex justify-content-center">
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-half-o fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-o fa-lg fa-star pe-2"></i>
            </p>
            <p>CV2</p>
            <h4>$1.030</h4>
          </div>
        </div>
      </div>


    </div>  

  </div>
  
  <div class="tab-pane container fade" id="Fealtured">


    <div class="row">
      <div class="col-lg-3">
        <div class="mb-4 shadow">
          <img src="/images/up.jpg" alt="" class="img-fluid">
          <div class="text-center mt-4 pb-4">
            <p class="d-flex justify-content-center">
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-half-o fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-o fa-lg fa-star pe-2"></i>
            </p>
            <p>990</p>
            <h4>$5200</h4>
          </div>
        </div>
      </div>

      <div class="col-lg-3">
        <div class="mb-4 shadow">
          <img src="/images/up1.jpg" alt="" class="img-fluid">
          <div class="text-center mt-4 pb-4">
            <p class="d-flex justify-content-center">
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-half-o fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-o fa-lg fa-star pe-2"></i>
            </p>
            <p>BC3</p>
            <h4>$20130</h4>
          </div>
        </div>
      </div>

      <div class="col-lg-3">
        <div class="mb-4 shadow">
          <img src="/images/up2.jpg" alt="" class="img-fluid">
          <div class="text-center mt-4 pb-4">
            <p class="d-flex justify-content-center">
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-half-o fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-o fa-lg fa-star pe-2"></i>
            </p>
            <p>AC50</p>
            <h4>$200</h4>
          </div>
        </div>
      </div>

      <div class="col-lg-3">
        <div class="mb-4 shadow">
          <img src="/images/up3.jpg" alt="" class="img-fluid">
          <div class="text-center mt-4 pb-4">
            <p class="d-flex justify-content-center">
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-half-o fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-o fa-lg fa-star pe-2"></i>
            </p>
            <p>H8</p>
            <h4>$232</h4>
          </div>
        </div>
      </div>

    </div>  



  </div>

  <div class="tab-pane container fade" id="NewArrival">

    <div class="row">
      <div class="col-lg-3">
        <div class="mb-4 shadow">
          <img src="/images/sport1.jpg" alt="" class="img-fluid">
          <div class="text-center mt-4 pb-4">
            <p class="d-flex justify-content-center">
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-half-o fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-o fa-lg fa-star pe-2"></i>
            </p>
            <p>JDM</p>
            <h4>$1</h4>
          </div>
        </div>
      </div>

      <div class="col-lg-3">
        <div class="mb-4 shadow">
          <img src="/images/Sport2.jpg" alt="" class="img-fluid">
          <div class="text-center mt-4 pb-4">
            <p class="d-flex justify-content-center">
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-half-o fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-o fa-lg fa-star pe-2"></i>
            </p>
            <p>211</p>
            <h4>$200</h4>
          </div>
        </div>
      </div>

      <div class="col-lg-3">
        <div class="mb-4 shadow">
          <img src="/images/Sport3.jpg" alt="" class="img-fluid">
          <div class="text-center mt-4 pb-4">
            <p class="d-flex justify-content-center">
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-half-o fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-o fa-lg fa-star pe-2"></i>
            </p>
            <p>SV2</p>
            <h4>$2000</h4>
          </div>
        </div>
      </div>

      <div class="col-lg-3">
        <div class="mb-4 shadow">
          <img src="/images/Sport4.jpg" alt="" class="img-fluid">
          <div class="text-center mt-4 pb-4">
            <p class="d-flex justify-content-center">
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-half-o fa-lg fa-star pe-2"></i>
              <i class="fa fa-star-o fa-lg fa-star pe-2"></i>
            </p>
            <p>M416</p>
            <h4>$20.2</h4>
          </div>
        </div>
      </div>

    </div>  


  </div>

</div>


  <!-- </div>

  <div class="justify-content-center d-flex">
  <button class="tablink" onclick="openPage('All', this, 'red')" id="defaultOpen">All</button>
  <button class="tablink" onclick="openPage('BestSeller', this, 'red')">BestSeller</button>
  <button class="tablink" onclick="openPage('Fealtured', this, 'red')">Fealtured</button>
  <button class="tablink" onclick="openPage('NewArrival', this, 'red')">NewArrival</button>
 </div>

  <div id="All" class="tabcontent">
    <h3>Home</h3>
    <p>Home is where the heart is..</p>
  </div>
  
  <div id="BestSeller" class="tabcontent">
    <h3>News</h3>
    <p>Some news this fine day!</p>
  </div>
  
  <div id="Fealtured" class="tabcontent">
    <h3>Contact</h3>
    <p>Get in touch, or swing by for a cup of coffee.</p>
  </div>
  
  <div id="NewArrival" class="tabcontent">
    <h3>About</h3>
    <p>Who we are and what we do.</p>
  </div> -->
    <!-- <script src="/js/tabs.js"></script> -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
