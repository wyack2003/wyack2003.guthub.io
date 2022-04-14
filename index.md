<!DOCTYPE html>
<html lang="en">
<head>
  <title>Gallery.html</title>
  <meta charset="utf-8">
      <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">


  <style>
    h1{
      text-align:center;
    }
    nav{
      text-align: right;
    }
body{
  background-color: black;
}
      {box-sizing: border-box;}
      body {font-family: Verdana, sans-serif;}
      .mySlides {display: none;}
      img {vertical-align: middle;}

      /* Slideshow container */
      .slideshow-container {
        max-width: 1000px;
        position: relative;
        margin: auto;
      }

      /* Caption text */
      .text {
        color: #f2f2f2;
        font-size: 15px;
        padding: 8px 12px;
        position: absolute;
        bottom: 8px;
        width: 100%;
        text-align: center;
      }

      /* Number text (1/3 etc) */
      .numbertext {
        color: #f2f2f2;
        font-size: 12px;
        padding: 8px 12px;
        position: absolute;
        top: 0;
      }

      /* The dots/bullets/indicators */
      .dot {
        height: 15px;
        width: 15px;
        margin: 0 2px;
        background-color: #bbb;
        border-radius: 50%;
        display: inline-block;
        transition: background-color 0.6s ease;
      }

      .active {
        background-color: #717171;
      }

      /* Fading animation */
      .fade {
        -webkit-animation-name: fade;
        -webkit-animation-duration: 1.5s;
        animation-name: fade;
        animation-duration: 1.5s;
      }

      -webkit-keyframes fade {
        from {opacity: .4}
        to {opacity: 1}
      }

      keyframes fade {
        from {opacity: .4}
        to {opacity: 1}
      }

      /* On smaller screens, decrease text size */
      media only screen and (max-width: 300px) {
        .text {font-size: 11px}
      }
      div.gallery {
  margin: 10px;
  border: 3px solid #ccc;
  float: right;
  width: 600px;
}

div.gallery:hover {
  border: 10px solid #777;
}

div.gallery img {
  width:100%;
  height: auto;
}

div.desc {
  padding: 0px;
  text-align: left;
}
h2{
  color:white;
}
    </style>
</head>
<body>

<div class="jumbotron">
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="navbar-header"> <!-- Brand-->
          <a href="#" class="navbar-brand"> <img src="https://i.pinimg.com/474x/da/ea/58/daea585b3a4120d4fd25db0f7db20b9b.jpg" width="50px"></a>
        </div>

         <div class="container-fluid">
           <a class="navbar-brand" href="#"><img src="#" width="30px" alt=""></a>
           <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo02" aria-controls="navbarTogglerDemo02" aria-expanded="false" aria-label="Toggle navigation">
             <span class="navbar-toggler-icon"></span>
           </button>
           <div class="collapse navbar-collapse" id="navbarTogglerDemo02">
             <ul class="navbar-nav me-auto mb-2 mb-lg-0">
               <li class="nav-item">
                 <a class="nav-link active" aria-current="page" href="#">Home</a>
               </li>
            <p>   <li class="nav-item">
                 <a class="nav-link" href="#">Gallery</a>
               </li></P>
              <p> <li class="nav-item">
                 <a class="nav-link" href="#">Contact Information</a>
               </li></p>
             </ul>
             <form class="d-flex">
               <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
               <button class="btn btn-outline-success" type="submit">Search</button>
             </form>
           </div>
         </div>
       </nav>
  <h1>Wyatt Ackermanns Gallery</h1>
<p  style="text-align:center;"> I wanted to share the place I want to surf before Im 50.</p>
</div>

<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block w-100" src="https://www.namotuislandfiji.com/wp-content/uploads/2019/01/kite-surfer-in-the-air-next-to-beach-of-namotu-island-fiji-01.jpg" alt="First slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="https://www.namotuislandfiji.com/wp-content/uploads/2019/01/namotu-island-surfing-underwater-image-of-surfer-banner-01-576x384.jpg" alt="Second slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="https://www.namotuislandfiji.com/wp-content/uploads/2019/01/surfer-at-namotu-lefts-surf-break-near-namotu-island-fiji-banner-01-1.jpg" alt="Third slide">
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
<h1 style=color:white;>Gallery</h1>
<br><br>
  <h2 style=text-align:center;>In my gallery Im showing my favorite looking waves at Namotu, Fiji. All of these waves are at Namotu lefts.</h2>
<div class="gallery">
  <a target="_blank" href= "https://i.pcmag.com/imagery/lineups/02EQzmxBV28b44npfNsg5ly-6.fit_lim.size_768x432.v1620053617.jpg">
    <img src="https://i.pcmag.com/imagery/lineups/02EQzmxBV28b44npfNsg5ly-6.fit_lim.size_768x432.v1620053617.jpg" alt="Cinque Terre" width="600" height="400">
  </a>
  <div class="desc"></div>
</div>

<div class="gallery">
  <a target="_blank" href="https://images.tpn.to/rj/mo/rt/mg/content.jpg">
    <img src="https://images.tpn.to/rj/mo/rt/mg/content.jpg" alt="Forest" width="600" height="400">
  </a>
  <div class="desc"></div>
</div>

<div class="gallery">
  <a target="https://www.htsresort.com/wp-content/uploads/Rip-Currents-800x450.jpg">
    <img src="https://www.htsresort.com/wp-content/uploads/Rip-Currents-800x450.jpg" alt="Northern Lights" width="600" height="400">
  </a>
  <div class="desc"></div>
</div>
<div class="gallery">
  <a target="_blank" href="https://photos.tpn.to/ks/np/tf/ee/800x450.jpg">
    <img src="https://photos.tpn.to/ks/np/tf/ee/800x450.jpg" alt="Northern Lights" width="600" height="400">
  </a>
  <div class="desc"></div>
</div>

<div class="gallery">
  <a target="_blank" href="https://photos.tpn.to/gt/lk/st/fp/800x450.jpg">
    <img src="https://photos.tpn.to/gt/lk/st/fp/800x450.jpg" alt="Mountains" width="600" height="400">
  </a>
  <div class="desc"></div>
</div>
<div class="gallery">
  <a target="_blank" href="https://www.outsideonline.com/wp-content/uploads/2017/02/13/kai-lenny-h-scaled.jpg?width=800">
    <img src="https://www.outsideonline.com/wp-content/uploads/2017/02/13/kai-lenny-h-scaled.jpg?width=800" alt="Cinque Terre" width="600" height="400">
  </a>
  <div class="desc"></div>
</div>
<div class="gallery">
  <a target="_blank" href="https://tracksmag.com.au/wp-content/uploads/2021/08/2016-06-jjf-fiji-lead.jpg">
    <img src="https://tracksmag.com.au/wp-content/uploads/2021/08/2016-06-jjf-fiji-lead.jpg" alt="Northern Lights" width="600" height="400">
  </a>
  <div class="desc"></div>
</div>
<div class="gallery">
  <a target="_blank" href="https://www.waterwaystravel.sdacreative.net/wp-content/uploads/2015/08/surfing_tav_5583_5979290901_o.jpg">
    <img src="https://www.waterwaystravel.sdacreative.net/wp-content/uploads/2015/08/surfing_tav_5583_5979290901_o.jpg" alt="Northern Lights" width="600" height="400">
  </a>
  <div class="desc"></div>
</div>

<div class="gallery">
  <a target="_blank" href="https://tracksmag.com.au/wp-content/uploads/2021/08/2016-06-medina-win-fiji.jpg">
    <img src="https://tracksmag.com.au/wp-content/uploads/2021/08/2016-06-medina-win-fiji.jpg" alt="Mountains" width="600" height="400">
  </a>
  <div class="desc"></div>
</div>

<br><br><br><br><br><br><br><br><br><hr><hr><hr><hr><hr><hr><hr><hr><hr><hr><hr><hr><hr><hr><hr><hr><hr><hr><hr><br><br><br><br><br><br><hr><hr><hr><hr><hr><hr><hr><hr><hr><hr><hr><hr><br><br><br><hr><hr><hr><hr><hr><hr><hr><hr><hr><br><br><br><hr><hr><hr><hr><hr><hr><hr><br><br><hr><hr>
<div class="jumbotron">
  <h1>Contact Information</h1>
  <div class="container text-center  j-background border rounded-lg">
             <div class="row d-flex justify-contend-around align-items-center py-5 ">
                 <div  class="col-lg-6 "> <a href="https://www.facebook.com" target="_blank"><i class="fab fa-facebook-square fa-3x f-color"></i></a>
                 </div>

                 <div class="col-lg-6 "> <a href="https://www.twitter.com" target="_blank"><i class="fab fa-twitter-square fa-3x t-color"></i></a>

                 </div>
                 <div class="col-lg-6 "> <a href="https://www.instagram.com" target="_blank"><i class="fab fa-instagram fa-3x i-color"></i></a>

                 </div>
                 <div class="col-lg-6 "> <a href="https://www.youtube.com" target="_blank"><i class="fab fa-youtube-square fa-3x y-color"></i></a>

                 </div>
</div>


 <script src="https://kit.fontawesome.com/b648122ecd.js" crossorigin="anonymous"></script>
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
</body>
</html>

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
