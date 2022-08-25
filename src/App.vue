<template>

  <html>
    <head>
      <title>One lover page</title>
    </head>

    <body>
        <header>
          <nav class="navbar navbar-expand-lg bg-light" style=" background-color: #222222 !important;">
            <div class="container-fluid">
              <a class="navbar-brand" href="#" style="color: white">One page lover</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Home</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link active" href="#">Inspo</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link active" href="#">Templates</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link active" href="#">Domains</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link active" href="#">Vector</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link active" href="#">Resources</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link active" href="#">Info</a>
                  </li>
                            <li class="nav-item dropdown">
                              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                                Info
                              </a>
                              <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="#">About + Contact</a></li>
                                <li><a class="dropdown-item" href="#">Submit</a></li>
                                <li><hr class="dropdown-divider">NEWSLETTERS</li>
                                <li><a class="dropdown-item" href="#">Inspiration only</a></li>
                              </ul>
                            </li>
                </ul>
                <form class="d-flex" role="search">
                  <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                  <button class="btn btn-outline-success" type="submit">Search</button>
                </form>
              </div>
            </div>
          </nav>
        </header>

        <div class="back-top">
        </div>

      <div class="container">
        <div class="main-content">
          <div class="main-content2">
            <h1 class="h1" id="full_name">Sanne Wijbenga</h1>
            <button type="button" class="btn btn-primary" id="kopce"
                    style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">
              VISIT WEBSITE
            </button>
          </div>
            <figcaption id="subname" class="blockquote-footer">
              Sanne Wijbenga
            </figcaption>
            <p id="text" class="lead">
              Long-scrolling One Page portfolio (built with <span style="color: #ff3b5c">Webflow</span>) for Dutch product designer Sanne Wijbenga.
              Neat touch adding the green “available for hire” dot over his logo avatar and clicking it slides up his contact form.
            </p>
          <div class="content-list">

            <div class="grupa-kopcinja">
              <figcaption id="features" class="blockquote-footer">
                Features
              </figcaption>
              <button class="kopce-malo">Accordion</button>
              <button class="kopce-malo">Big Typography</button>
              <button class="kopce-malo">Client Logos</button>
              <button class="kopce-malo">Fixed Header</button>
              <button class="kopce-malo">Full-width Layout</button>
            </div>
            <div class="grupa-kopcinja second">
              <button class="kopce-malo">Long Scrolling</button>
              <button class="kopce-malo">Off-Canvas Content Area</button>
              <button class="kopce-malo">Product Designer</button>
              <button class="kopce-malo">Slider</button>
              <button class="kopce-malo">Testimonials</button>
            </div>

<!--            <div class="btn-group btn-group-sm" id="kopcinja" role="group" aria-label="Small button group">-->
<!--              <button type="button" class="btn btn-outline-dark kopce_malo">Left</button>-->
<!--              <button type="button" class="btn btn-outline-dark kopce_malo">Middle</button>-->
<!--              <button type="button" class="btn btn-outline-dark kopce_malo">Right</button>-->
<!--            </div>-->
          </div>
        </div>
      </div>
    </body>
  </html>

</template>

<!--<script>-->
<!--$(function(){-->
<!--  $('.mydropdownjQuery').hover(function() {-->
<!--        $(this).addClass('open');-->
<!--      },-->
<!--      function() {-->
<!--        $(this).removeClass('open');-->
<!--      });-->
<!--});-->
<!--</script>-->


<style lang="scss">

  body{
    background-color: #a4a4a4 !important;
  }
  ul li{
    color: white;
  }
  .navbar-expand-lg .navbar-nav{
    margin: auto;
  }
  .back-top{
    width: 100%;
    height: 150px;
    background-color: #282828;
    z-index: -1;
  }
  .nav-link{
    color: #7d7d7d !important;
  }
  .nav-link:hover{
    color: white !important;
  }
  .container{
    height: auto;
    background-color: white;
    margin-top: -75px;
  }
  .main-content{
    padding: 50px;
  }
  .main-content2{
    display: flex;
    flex-direction: row;
    //justify-content: space-between;
  }
  #kopce{
    margin-top: 70px;
    width: 100px;
    height: 30px;
    background-color: #ff3b5c;
    border-radius: 50px !important;
  }
  #full_name{
    margin-top: 5%;
    margin-bottom: 2.2%;
    margin-left: 20%;
    margin-right: 20%;
  }

  #subname{
    margin-bottom: 5%;
    margin-left: 20%;
    margin-right: 20%;
  }

  #text{
    margin-left: 20%;
    margin-right: 20%;
  }
  .content-list{
    padding-top: 10%;
  }
  .grupa-kopcinja{
    margin-bottom: 5%;
    margin-left: 20%;
    margin-right: 20%;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
  }
  .kopce-malo{
    width: 100%;
    height: 100%;
    border: 1px solid #ff3b5c;
    border-radius: 20px;
    font-size: 8px;
    white-space: nowrap;
    margin: 2px;
  }
  #features{
    margin-bottom: 5%;
    margin-right: 20%;
    text-transform: uppercase;
  }
  .second{
    margin-left: 36.5%;
    margin-top: -8%;
  }


</style>
