<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link href="https://cdn.jsdelivr.net/npm/remixicon@4.1.0/fonts/remixicon.css" rel="stylesheet"/>
  <link href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" rel="stylesheet"/>
  <link rel="stylesheet" href="styles.css" />
  <title>Fashion Website</title>
</head>
<body> 
                                           <!--==== header =====-->
<header class="header">
<nav>
  <div class="nav__header">
  <div class="logo nav__logo">
    <a href="#">Fashion</a>
  </div>
  <div class="nav__menu__btn" id="menu-btn">
    <span><i class="ri-menu-line"></i></span>
  </div>
  </div>
  <ul class="nav__links" id="nav-links">
    <li class="link"><a href="#home">Home</a></li>
    <li class="link"><a href="#offer">Offer</a></li>
    <li class="link"><a href="#popular">Popular</a></li>
    <li class="link"><a href="#client">Client</a></li>
    <li class="link"><a href="#contact">Contact</a></li>
  </ul>
  <div class="nav__btns">
    <button class="btn">Sign Up</button>
  </div>
</nav>
  <div class="section__container header__container" id="home">
    <h1>Style that speaks<br />louder than<br />words...!</h1>
  </div>
</header>
                                                 <!--==== Offer =====-->
<section class="section__container offer__container" id="offer">
  <div class="offer__image">
    <img src="assets/ddd1.png" alt="offer" />
  </div>
  <div class="offer__content">
    <h3 class="section__subheader">EXCLUSIVE OFFER</h3>
    <h2 class="section__header">Make Every Day a Fashion Show...!</h2>
    <p class="section__description">
      Fashion style is a way of expressing one’s identity through 
      clothing, accessories, and overall aesthetic choices. It reflects 
      personal taste, lifestyle, cultural influences, and sometimes even one’s mood. 
      Styles in fashion are incredibly diverse and constantly evolving, making them a powerful medium for self-expression.
    </p>
    <h5>Long Down Jacket</h5>
  <div class="offer__ratings">
    <span><i class="ri-star-fill"></i></span>
    <span><i class="ri-star-fill"></i></span>
    <span><i class="ri-star-fill"></i></span>
    <span><i class="ri-star-fill"></i></span>
  </div>
  <div class="offer__btn">
     <button class="btn">Buy Now <span><i class="ri-arrow-right-line"></i></span></button>
  </div>
  </div>
</section>
                                                 <!--==== Popular =====-->
<section class="section__container popular__container" id="popular">
    <h3 class="section__subheader">MOST POPULAR </h3>
    <h2 class="section__header">We Provide Popular Jacket for you...!</h2>
  <div class="popular__grid">
  <div class="popular__card">
    <img src="assets/popular1.png" alt="popular" />
  <div class="popular__content">
    <h4>Blue Puffer Jacket</h4>
    <p>50% OFF</p>
  <div class="popular__card__footer">
  <div class="popular__ratings">
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>                
  </div>
  <div class="popular__price">$120</div>
  </div>
  </div>
  </div>
  <div class="popular__card">
    <img src="assets/popular2.png" alt="popular" />
  <div class="popular__content">
    <h4>Grey Puffer Jacket</h4>
    <p>50% OFF</p>
  <div class="popular__card__footer">
  <div class="popular__ratings">
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>            
  </div>
  <div class="popular__price">$200</div>
  </div>
  </div>
  </div>
  <div class="popular__card">
    <img src="assets/popular3.png" alt="popular" />
  <div class="popular__content">
    <h4>Brown Puffer Jacket</h4>
    <p>50% OFF</p>
  <div class="popular__card__footer">
  <div class="popular__ratings">
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
  </div>
  <div class="popular__price">$100</div>
  </div>
  </div>
  </div>
  </div>
</section>
                                              <!--==== Client =====-->
<section class="section__container client__container" id="client">
  <div class="client__image">
     <img src="assets/dddo1.png" alt="client" />
  </div>
  <div class="client__content">
     <h3 class="section__subheader">TESTIMONIALS</h3>
     <h2 class="section__header">Our Client has Expressed...</h2>
  <div class="swiper">
  <div class="swiper-wrapper">
  <div class="swiper-slide">
  <div class="client__card">
     <p>What you wear is how you present yourself to the world, 
        especially today, when human contacts are so quick. Fashion is instant language.
     </p>
  <div class="client__details">
     <img src="assets/user-1.jpg" alt="client" />
  <div>
     <h4>Miuccia Prada</h4>
     <h5>Frontend Developer</h5>
  </div>
  </div>
  </div>
  </div>
  <div class="swiper-slide">
  <div class="client__card">
     <p>I think there is beauty in everything. What 'normal' people 
        perceive as ugly, I can usually see something of beauty in it.
     </p>
  <div class="client__details">
     <img src="assets/user-2.jpg" alt="client" />
  <div>
     <h4>Sonia Rykiel</h4>
     <h5>Financial Analyst</h5>
  </div>
  </div>
  </div>
  </div>
  <div class="swiper-slide">
  <div class="client__card">
     <p>What's my style is not your style, and I don’t see 
        how you can define it. It’s something that expresses who you are in your own way.
     </p>
  <div class="client__details">
     <img src="assets/user-3.jpg" alt="client" />
  <div>
     <h4>Vera Wang</h4>
     <h5>Marketing Executive</h5>
  </div>
  </div>
  </div>
  </div>
  </div>
          <!--  navigation buttons -->
  <div class="client-swiper-btns">
     <div class="swiper-prev"><i class="ri-arrow-left-line"></i></div>
     <div class="swiper-next"><i class="ri-arrow-right-line"></i></div>
  </div>
  </div>
  </div>
</section>
                                                    <!--==== Banner =====-->
<section class="banner">
   <div class="banner__wrapper">
   <div class="banner__card">
     <img src="assets/banner11.png" alt="banner" />
   <div class="banner__content">
     <h4>Japan</h4>
   <div class="banner__ratings">
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
   </div>
   </div>
   </div>
   <div class="banner__card">
     <img src="assets/banner12.png" alt="banner" />
   <div class="banner__content">
     <h4>India</h4>
   <div class="banner__ratings">
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
   </div>    
   </div>
   </div>
   <div class="banner__card">
     <img src="assets/banner13.png" alt="banner" />
   <div class="banner__content">
     <h4>Spain</h4>
   <div class="banner__ratings">
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
   </div>        
   </div>
   </div>
   <div class="banner__card">
     <img src="assets/banner14.png" alt="banner" />
   <div class="banner__content">
     <h4>Germany</h4>
   <div class="banner__ratings">
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
   </div>         
   </div>
   </div>
   <div class="banner__card">
     <img src="assets/banner15.png" alt="banner" />
   <div class="banner__content">
     <h4>America</h4>
   <div class="banner__ratings">
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
   </div>   
   </div>
   </div>
   <div class="banner__card">
     <img src="assets/banner16.png" alt="banner" />
   <div class="banner__content">
     <h4>England</h4>
   <div class="banner__ratings">
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
     <span><i class="ri-star-fill"></i></span>
   </div>          
   </div>
   </div>
   </div>
</section>
                                              <!--==== Newsletter =====-->
<section class="section__container newsletter__container" id="contact">
   <div class="newsletter__content">
     <h2 class="section__header">Subscribe Our Newsletter</h2>
     <p class="section__description">
       Subscribe to our newsletter for exclusive updates, offers, and style inspiration!
     </p>
    <form action="/">
     <input type="text" placeholder="Enter Your Email" />
     <button class="btn">Submit</button>
    </form>
   </div>
</section>
                                               <!--==== Footer =====-->
<footer class="footer">
  <div class="section__container footer__container">
  <div class="footer__col">
  <div class="logo footer__logo">
     <a href="#home">Fashion</a>
  </div>
     <p>Discover a world of endless style possibilities as we curate 
        the best in fashion, from hidden gems to iconic trends.
     </p>
  <div class="footer__socials">
     <a href="#"><i class="ri-youtube-fill"></i></a>
     <a href="#"><i class="ri-twitter-x-fill"></i></a>
     <a href="#"><i class="ri-instagram-fill"></i></a>
     <a href="#"><i class="ri-linkedin-fill"></i></a>
  </div>
  </div>
  <div class="footer__col">
     <h4>Quick Links</h4>
   <ul class="footer__links">
     <li><a href="#">Order Book</a></li>
     <li><a href="#">Exclusive Offers</a></li>
     <li><a href="#">Trendy Clothes</a></li>
     <li><a href="#">Stylish accessories </a></li>
   </ul>
  </div>
  <div class="footer__col">
     <h4>Who Are We</h4>
   <ul class="footer__links">
     <li><a href="#">FAQs</a></li>
     <li><a href="#">Best Seller</a></li>
     <li><a href="#">Terms & Conditions</a></li>
     <li><a href="#">Privacy Policy</a></li>
   </ul>
  </div>
  <div class="footer__col">
     <h4>Contact Us</h4>
   <ul class="footer__links">
     <li><a href="#">Customer Support</a></li>
     <li><a href="#">Customer Helpline</a></li>
     <li><a href="#">Join our Community</a></li>
   </ul>
  </div>
  </div>
  <div class="footer__bar">
     Copyright © 2024 Fashion. All rights reserved.
  </div>
</footer>
                                        <!--==== Script =====-->
 <script src="https://unpkg.com/scrollreveal"></script>
 <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
 <script src="main.js"></script>
</body>
</html>
