# Watches
A page where I made a list of my favorite watches including some vintage ones.
<!DOCTYPE html>
<html lang = "en">
    <head>
        <meta charset="UTF-8">
        <title>More Practice</title>
        <link rel="stylesheet" href = css/Watches.css>
        <script src = "js/date and slides.js"></script>
    </head>
    <body>
        <section class="title">
            <div>
        <h1>Different Types of Watches</h1>
        </div>
        </section>
   <section>
       <div>
        <h2>Field Watches</h2>
        </div>
        <div class="field">
        <nav>
        <a href = https://www.hamiltonwatch.com/en-us/h69439363-khaki-field-mechanical.html>Hamilton</a>
        <a href = https://www.macys.com/shop/product/seiko-mens-automatic-5-sports-green-nylon-strap-watch-43mm?ID=13059131&pla_country=US&CAGPSPN=pla&cm_mmc=Google_Watches_PLA-_-G_PLA_Watches_-_Seiko_Seiko-_-200646994774-_-pg1051703792_c_kclickid__kenshoo_clickid__KID_EMPTY_347019891_43037301986_200646994774_pla-545524644621_29665208897USA__c_KID_&trackingid=469x1051703792&m_sc=sem&m_sb=Google&m_tp=PLA&m_ac=Google_Watches_PLA&m_ag=Seiko&m_cn=G_PLA_Watches_-_Seiko&m_pi=go_cmp-347019891_adg-43037301986_ad-200646994774_pla-545524644621_dev-c_ext-_prd-29665208897USA&gclid=CjwKCAjw8KmLBhB8EiwAQbqNoF6dApNVQiiRD5Lx-XWrX92XmYal9DR_YqTEV0KMTxSPo0iH6XSl2RoC8XMQAvD_BwE>Seiko</a>
         </nav>
         </div>
         </section>
        <section>
            <div>
         <h2>Dive Watches</h2>
         </div>
         <div class="dive">
         <nav>
             <a href = https://en.yema.com/products/yema-superman-heritage-u-s-edition-ysup2019c41>Yema Superman</a>
             <a href = https://www.lorierwatches.com/products/neptune-siii-black-gilt>Lorier Neptune</a>
            </nav>
            </div>
            </section>
   <section>
        <div>
         <h2>Luxury</h2>
         </div>
         <div class="luxury">
         <nav>
             <a href = https://www.rolex.com/watches/day-date/m228239-0033.html>Rolex Day Date</a>
             <a href = https://www.oris.ch/en/watch/big-crown-pointer-date/01-754-7741-4065-07-5-20-63>Oris Big Crown</a>

         </nav>
         </div>
            </section>
         
         <section>
             <div>
         <h2>Favorite Watches</h2>
         </div>
         <div>
         <ul>
             <li>Yema Superman</li>
             <li>Rolex Day-Date</li>
             <li>Marathon</li>
             <li>Vostok</li>
         </ul>
         </div>
         </section>
         <section>
             <div>
             <h2>Unusual Watches</h2>
             </div>
             <div>
             <nav>
                 <a href = http://vostok.watch/product/russian-watch-vostok-prestige-retro-2403-583565/ >Vostok</a>
                 <a href = https://www.bulova.com/us/en/product/96A248.html?utm_medium=shopping&utm_campaign=bulova&byPassIntlRedirect=true&gclid=CjwKCAjw8KmLBhB8EiwAQbqNoCZ3zkQ91R1Xg6s5eWvG_Zlzo6prFKf2Yx9u-PNoDy5HUIa6YrWo9hoC2OAQAvD_BwE>Bulova</a>
             </nav>
             </div>
             <!--Picture Slideshow-->
            
            
             <section>
                 <div class="slideshow-container">
                     <p>Vintage Watches</p>
              
             <div class="slideshow fade">
              <div class="numbertext">1/3</div>
              <img src="images/vintage rolex.jpeg" style="width: 50%">
              <div class="text">Vintage Rolex 1</div>
              </div>

              <div class="slideshow fade">
              <div class="numbertext">2/3</div>
              <img src="images/vintage omega.jpeg" style="width: 50%">
              <div class="text">Vintage Omega 2</div>
              </div>

              <div class="slideshow fade">
              <div class="numbertext">3/3</div>
              <img src="images/vintage bulova.jpeg" style="width: 50%">
              <div class="text">Vintage Bulova</div>
              </div>
              <!--Buttons-->
              <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
              <a class="next" onclick="plusSlides(1)">&#10095;</a>
            </div>
           
            <br>

            <!--DotsandCircles-->
            <div style="text-align:center">
                <span class="dot" onclick="currentSlide(1)"></span>
                <span class="dot" onclick="currentSlide(2)"></span>
                <span class="dot" onclick="currentSlide(3)"></span>
              </div>

             </section>
         </section>
         <section id="date">
         <body onload="setDate()">
            <p> The current date is </p>
         </section>

    </body>
body{
    background-image: url("../images/watch gears.jpeg");
    background-repeat: no-repeat;
    background-size: cover;
}
h2{
    color:cornsilk;
}
.title{
    color:cornsilk; 


}
nav>a{
    color:honeydew;
    text-decoration: none;
    opacity: .5px;
    border-radius: 25px;
    background:slateblue;
    padding: 10px;

}


a:hover{
    transition: background-color 1s;
   background-color:gold;
   font-size: 150%;
}


section{
    text-align:center;
}
li{
    color:honeydew;
   list-style-position:inside;
}
#date{
    color: honeydew;
    padding: 50px;
 }

 * {box-sizing:border-box}
body {font-family: Verdana, sans-serif; margin:0}
.slideshow {display: none}
img {vertical-align: middle;}


* {box-sizing:border-box}
body {font-family: Verdana, sans-serif; margin:0}
.slideshow {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 500px;
  position: relative;
  margin: auto;
  padding: 50px;
  color: cornsilk;
}



/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: center;
  top: 100%;
  width: auto;
  margin-top: -22px;
  padding: 80px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover{
  background-color: rgba(0,0,0,0.8);
  background: 50px
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 10px 12px;
  position: center;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 20px 20px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: blanchedalmond;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
  
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4}
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4}
  to {opacity: 1}
}
/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
