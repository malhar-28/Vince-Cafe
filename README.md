<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- 
    - primary meta tags
  -->
  <title>Menu</title>
  <meta name="title" content="Vince - Amazing & Delicious Food">
  <meta name="description" content="This is a Restaurant html template made by codewithsadee">

  <!-- 
    - favicon
  -->
  <link rel="shortcut icon" href="./favicon.svg" type="image/svg+xml">

  <!-- 
    - google font link
  -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;700&family=Forum&display=swap" rel="stylesheet">

  <!-- 
    - custom css link
  -->
  <link rel="stylesheet" href="./assets/css/style.css">

  <!-- 
    - preload images
  -->
<!--   <link rel="preload" as="image" href="./assets/images/hero-slider-1.jpg">
  <link rel="preload" as="image" href="./assets/images/hero-slider-2.jpg">
  <link rel="preload" as="image" href="./assets/images/hero-slider-3.jpg"> -->

</head>

<body id="top">

  <!-- 
    - #PRELOADER
  -->

  <div class="preload" data-preaload>
    <div class="circle"></div>
    <p class="text"><img src="./Menu Images/logo.png" alt="Vince Cafe"></p>
  </div>





  <!-- 
    - #TOP BAR
  -->

  <div class="topbar">
    <div class="container">

      <address class="topbar-item">
        <div class="icon">
          <ion-icon name="location-outline" aria-hidden="true"></ion-icon>
        </div>

        <span class="span">
          Vince Cafe, Opp Taj Skyline,SBR Road,Ahmedabad
        </span>
      </address>

      <div class="separator"></div>

      <div class="topbar-item item-2">
        <div class="icon">
          <ion-icon name="time-outline" aria-hidden="true"></ion-icon>
        </div>

        <span class="span">Daily : 10:00 AM to 2:AM</span>
      </div>

      <a href="tel:+11234567890" class="topbar-item link">
        <div class="icon">
          <ion-icon name="call-outline" aria-hidden="true"></ion-icon>
        </div>

        <span class="span">+91 9825926796</span>
      </a>

      <div class="separator"></div>

      <a href="mailto:vincecafe@gmail.com" class="topbar-item link">
        <div class="icon">
          <ion-icon name="mail-outline" aria-hidden="true"></ion-icon>
        </div>

        <span class="span">vincecafe@gmail.com</span>
      </a>

    </div>
  </div>





  <!-- 
    - #HEADER
  -->

  <header class="header" data-header>
    <div class="container">

     

      <nav class="navbar" data-navbar  style="margin:auto;" >

        <button class="close-btn" aria-label="close menu" data-nav-toggler>
          <ion-icon name="close-outline" aria-hidden="true"></ion-icon>
        </button>

        <a href="index.html" class="logo">
          <img src="./Menu Images/logo.png" width="260" height="100" alt="Vince - Home">
        </a>

        <ul class="navbar-list">

          <li class="navbar-item">
            <a href="#coffee" class="navbar-link hover-underline active">
              <div class="separator"></div>

              <span class="span">Coffee</span>
            </a>
          </li>

          <li class="navbar-item">
            <a href="#apetizers" class="navbar-link hover-underline">
              <div class="separator"></div>

              <span class="span">Apetizers</span>
            </a>
          </li>
          <li class="navbar-item">
            <a href="#burgers" class="navbar-link hover-underline">
              <div class="separator"></div>

              <span class="span">Burgers</span>
            </a>
          </li>


          <li class="navbar-item">
            <a href="#sizzlers" class="navbar-link hover-underline">
              <div class="separator"></div>

              <span class="span">Sizzlers</span>
            </a>
          </li>

          <li class="navbar-item">
            <a href="#pizzapasta" class="navbar-link hover-underline">
              <div class="separator"></div>

              <span class="span">Pizzas & Pastas</span>
            </a>
          </li>

          <li class="navbar-item">
            <a href="#deserts" class="navbar-link hover-underline">
              <div class="separator"></div>

              <span class="span">Deserts</span>
            </a>
          </li>

         
        </ul>
        
       

   
      
        <div class="text-center">
          <p class="headline-1 navbar-title">Visit Us</p>

          <address class="body-4">
            Vince Cafe, Opp Taj Skyline, <br>
            SBR Road,Ahmedabad
          </address>

          <p class="body-4 navbar-text">Open: 10:00 AM to 2:AM</p>

          <a href="mailto:vincecafe@gmail.com" class="body-4 sidebar-link">vincecafe@gnail.com</a>

          <div class="separator"></div>

          <p class="contact-label">Booking Request</p>

          <a href="tel:+88123123456" class="body-1 contact-number hover-underline">
            +91-9825926796
          </a>
        </div>

      </nav>

      <button class="nav-open-btn" aria-label="open menu" data-nav-toggler>
        <span class="line line-1"></span>
        <span class="line line-2"></span>
        <span class="line line-3"></span>
      </button>

      <div class="overlay" data-nav-toggler data-overlay></div>

    </div>
  </header>





  <main>
    <article>

      <!-- 
        - #HERO
      -->

      <section class="section menu" aria-label="menu-label" id="coffee" style="height: auto;">

        <div class="container" style="height: auto;">

          <p class="section-subtitle text-center label-2" style="margin-top: 50px;"> Coffee </p>

        

          <ul class="grid-list">

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Coffee-1.jpg" width="100" height="100" loading="lazy" alt="Coffee-1"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Cappuccino</a>
                    </h3>

                    <span class="span title-2">120 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Strong Brewed Coffee, Steamed Milk  , Whipped Cream , Milk  Foam
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Coffee-2.jpg" width="100" height="100" loading="lazy" alt="Coffee-2"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Hazelnut Rocher</a>
                    </h3>

                    <span class="span title-2">220 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Coffee , Hazelnut Syrup , Chocolate Sryup , Whipped Cream
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Coffee-3.jpg" width="100" height="100" loading="lazy" alt="Coffee-3"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Caremel Irish</a>
                    </h3>

                    <span class="span title-2">180 /-</span>
                  </div>

                  <p class="card-text label-1">
                   Irish Whiskey , Hot Coffee , Caramel Syrup , Whipped Cream
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Coffee-4.jpg" width="100" height="100" loading="lazy" alt="Coffee-4"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Java Choco</a>
                    </h3>

                    
                    <span class="span title-2">200 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Strong Brewed Coffee , Chocolate Syrup , Vanilla Syrup , Cocoa Powder , Chocolate Shavings , Whipped Cream 
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Coffee-5.jpg" width="100" height="100" loading="lazy" alt="Coffee-5"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Hot Mocha</a>
                    </h3>

                    <span class="span title-2">130 /-</span>
                  </div>

                  <p class="card-text label-1">
                   Strong Brewed Coffee , Chocolate Syrup , Cocoa Powder , Steamed Milk , Whipped Cream
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Coffee-6.jpg" width="100" height="100" loading="lazy" alt="Coffee-6"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Honeyed Nut Latte</a>
                    </h3>

                    <span class="span title-2">350 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Espresso , Steamed Milk , Honey Syrup , Nut-Flavoured Extracts , Drizzle of Honey
                  </p>

                </div>

              </div>
            </li>


            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Coffee-7.jpg" width="100" height="100" loading="lazy" alt="Coffee-7"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Classic Ice Coffee</a>
                    </h3>

                    <span class="span title-2">220 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Chilled Espresso , Ice Cubes , Cream , Sweeteners , Caramel Flavouring
                  </p>

                </div>

              </div>
            </li>


            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Coffee-8.png" width="100" height="100" loading="lazy" alt="Coffee-8"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Chocolate Cortado</a>
                    </h3>

                    <span class="span title-2">300 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Espresso , Chocolate Syrup , Cocoa Powder , Steamed Milk 
                  </p>

                </div>

              </div>
            </li>


          </ul>
         

          <img src="./Menu Images/shape-5.png" width="921" height="1036" loading="lazy" alt="shape"
            class="shape shape-2 move-anim">
          <img src="./Menu Images/shape-6.png" width="343" height="345" loading="lazy" alt="shape"
            class="shape shape-3 move-anim">

        </div>

      </section>





      <!-- 
        - #SERVICE
      -->

      <section class="section menu  bg-black-10 " aria-label="menu-label" id="apetizers" style="height: auto;">
        <div class="container" >

          <p class="section-subtitle text-center label-2" > Apetizers</p>

        

          <ul class="grid-list">

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Apetizer-1.jpg" width="100" height="100" loading="lazy" alt="Apetizer-1"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Four Cheese Garlic Bread</a>
                    </h3>

                  

                    <span class="span title-2">280 /-</span>
                  </div>

                  <p class="card-text label-1">
                  Bread , Garlic , Mozzarella Cheese , Cedar Cheese , Parmesan Cheese , Provolane Cheese , Herbs
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Apetizer-2.jpg" width="100" height="100" loading="lazy" alt="Apetizer-2"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">French Fries</a>
                    </h3>

                    <span class="span title-2">200 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Potaoes , Salt , Garlic Parmesan , Ketchup , Mayonnaise
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Apetizer-3.jpg" width="100" height="100" loading="lazy" alt="Apetizer-3"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Nachos Platter</a>
                    </h3>

                    <span class="span title-2">250 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Corm Nachos , Refried Beans , Pickled Jalapenos , Tomatoes , Green Onions , Avocado , salsa Dips , Cheese Dips
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Apetizer-4.jpg" width="100" height="100" loading="lazy" alt="Apetizer-4"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Honey Chilli Potato</a>
                    </h3>

              
                    <span class="span title-2">350 /-</span>
                  </div>

                  <p class="card-text label-1">
                   Potato , Corn Flour , Honey , Chilli Sauce , Cornstarch , Vinegar , Red Chilli Flakes 
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Apetizer-5.jpg" width="100" height="100" loading="lazy" alt="Apetizer-5"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Crispy Vegetables</a>
                    </h3>

                    <span class="span title-2">360 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Bett Papers , Carrots , Brocolli , Cauliflower , Zucchini, ,Garlic-Onion Powder , Herbs
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Apetizer-6.jpg" width="100" height="100" loading="lazy" alt="Apetizer-6"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Veg.Manchurian Dry</a>
                    </h3>

                    <span class="span title-2">350/-</span>
                  </div>

                  <p class="card-text label-1">
                    cabbage , Bell Peppers , Onions , Maida , Corn Flour , Ginger-Garlic Paste , Chilli Sauce
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Apetizer-7.jpg" width="100" height="100" loading="lazy" alt="Apetizer-7"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Paneer 65 Dry</a>
                    </h3>

                    <span class="span title-2">380/-</span>
                  </div>

                  <p class="card-text label-1">
                   Panner , Maida , Ginger-Garlic Paste , Bell Peppers , Vinegar , Cornstarch Slurry
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Apetizer-8.jpg" width="100" height="100" loading="lazy" alt="Apetizer-8"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Lasagna</a>
                    </h3>

                    <span class="span title-2">400/-</span>
                  </div>

                  <p class="card-text label-1">
                    Noodles , Tomato-Marinara Sauce , Mozzarella Cheese , Ricotta Cheese , Garlic , Basil
                  </p>

                </div>

              </div>
            </li>

          </ul>

          <img src="./Menu Images/shape-1.png" width="246" height="412" loading="lazy" alt="shape" style="left:0px;top:200px"
            class="shape shape-1 move-anim" >
          <img src="./Menu Images/shape-2.png" width="343" height="345" loading="lazy" alt="shape" style="left:1600px"
            class="shape shape-2 move-anim" >

        </div>
      </section>





      <section class="section menu" aria-label="menu-label" id="burgers" style="height: auto;">

        <div class="container" style="height: auto;">

          <p class="section-subtitle text-center label-2" > Burgers </p>

        

          <ul class="grid-list">

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Burger-1.jpg" width="100" height="100" loading="lazy" alt="Burger-1"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Spicy Veggie</a>
                    </h3>


                    <span class="span title-2">110 /-</span>
                  </div>

                  <p class="card-text label-1">
                   Veggie Burger Patties , Lettuce Leaved , Sliced Tomatoes-Onions , Jalapenoes , Chipotle Sauce , Mayonnaise
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Burger-2.jpg" width="100" height="100" loading="lazy" alt="Burger-2"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Chilli Cheese</a>
                    </h3>

                    <span class="span title-2">130 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Potato Tikki , Chilli Con Carne , Cheese Slice , Pickled Jalapenos , Mayonnaise , Burger Sauce
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Burger-3.jpg" width="100" height="100" loading="lazy" alt="Burger-3"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Cheese Chedar Paneer</a>
                    </h3>

                    <span class="span title-2">180 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Paneer Cubes , Chedar Cheese , Garam Masala , Herbs , Cumin Seeds , Red Chilli Powder
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Burger-4.jpg" width="100" height="100" loading="lazy" alt="Burger-4"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Paneer Makhani</a>
                    </h3>

                    <span class="badge label-1">BOGO</span>

                    <span class="span title-2">180 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Paneer Patty , Ginger-garlic Paste , Cream , Lettuce Leaves , Cheese Slice , Red Chilli Powder
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Burger-5.jpg" width="100" height="100" loading="lazy" alt="Burger-5"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Mexican Salsa Paneer</a>
                    </h3>

                    <span class="span title-2">260 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Paneer Patty , Taco Seasoning , Chopped Cilantro , Jalapeno Peppers , Sliced Avocado , Sour Cream
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Burger-6.png" width="100" height="100" loading="lazy" alt="Burger-6"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Chargrilled Veggie</a>
                    </h3>

                    <span class="span title-2">240 /-</span>
                  </div>

                  <p class="card-text label-1">
                   Veggie Burger Patty , Legumes , Lettuce Leaves , Mustard Sauce , Mayonnaise , Flaxseeds , Paprika
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Burger-7.jpg" width="100" height="100" loading="lazy" alt="Burger-7"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Tandoori Paneer Tikka</a>
                    </h3>

                    <span class="span title-2">320 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Panner Patty , Tandoori Masala , Ginger-garlic Paste , Red Chilli Powder , Mint-Coriander , Mayonnaise 
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Burger-8.jpg" width="100" height="100" loading="lazy" alt="Burger-8"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Grillable Cheese Veggie </a>
                    </h3>

                    <span class="span title-2">300 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Veggie Burger Patty , Legumes , Cumin , parsley , Cheddar Cheese , Swiss Cheese , Mustard Sauce , Ketchup
                  </p>

                </div>

              </div>
            </li>

          </ul>
         

          <img src="./Menu Images/shape-5.png" width="921" height="1036" loading="lazy" alt="shape"
            class="shape shape-2 move-anim">
          <img src="./Menu Images/shape-6.png" width="343" height="345" loading="lazy" alt="shape"
            class="shape shape-3 move-anim">

        </div>

      </section>





      <!-- 
        - #SERVICE
      -->

      <section class="section menu  bg-black-10 " aria-label="menu-label" id="sizzlers" style="height: auto;">
        <div class="container" >

          <p class="section-subtitle text-center label-2" > sizzlers</p>

        

          <ul class="grid-list">

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Sizzler-1.jpg" width="100" height="100" loading="lazy" alt="Sizzler-1"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Veg Satellite </a>
                    </h3>

                   

                    <span class="span title-2">680 /-</span>
                  </div>

                  <p class="card-text label-1">
                   Vegetable Cutlets , Vegetables , Fries , Chilli Basil Sauce, Cheese
                  </p>

                </div>

              </div>
            </li>
            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Sizzler-2.jpg" width="100" height="100" loading="lazy" alt="Sizzler-2"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Vince Special Sizzler</a>
                    </h3>

                    <span class="span title-2">950 /-</span>
                  </div>

                  <p class="card-text label-1">
                   Cottage Cheese Balls , Veg. Sausages , Grilled Paneer , Fries , Tomato Chilli Sauce , Vegetables , Cheese
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Sizzler-3.jpg" width="100" height="100" loading="lazy" alt="Sizzler-3"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Paneer Shashlik</a>
                    </h3>

                    <span class="span title-2">780 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Grilled Paneer Skewer , Rice , Vegetables , Fries , Garlic Sauce , Pineapple
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Sizzler-4.jpg" width="100" height="100" loading="lazy" alt="Sizzler-4"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Spicy Tossed Veg Sizzler</a>
                    </h3>

                    <span class="span title-2">620 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Vegetables , Paneer , Mushrooms , Chinese Sauce , Fries, Rice
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Sizzler-5.jpg" width="100" height="100" loading="lazy" alt="Sizzler-5"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Hunan Style Paneer Sizzler</a>
                    </h3>

                    

                    <span class="span title-2">780 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Paneer , Spicy Hunan Style Sauce , Rice , Fries , Vegetables 
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Sizzler-6.jpg" width="100" height="100" loading="lazy" alt="Sizzler-6"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Thrid Queen</a>
                    </h3>

                    <span class="span title-2">800 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Vegetable  Cutlets , Cottage Cheese Balls , Tossed vegtabled , Chilli Tomato Sauce 
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Sizzler-7.jpg" width="100" height="100" loading="lazy" alt="Sizzler-7"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Panner Babycorn Platter</a>
                    </h3>

                    <span class="span title-2">790 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Grilled Paneer , Mushroom , Babycorn , Vegetabled , Fries , Hot Chilli Garlic Sauce , Cheese
                  </p>

                </div>

              </div>
            </li>
            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Sizzler-8.jpg" width="100" height="100" loading="lazy" alt="Sizzler-8"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Veg Spaghetti Sizzler</a>
                    </h3>

                    <span class="span title-2">740 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Spaghetti , Chef Special Creamy Red Sauce , Vegetables, Fries , Cutlet , Cheese
                  </p>

                </div>

              </div>
            </li>

          </ul>

          <img src="./Menu Images/shape-1.png" width="246" height="412" loading="lazy" alt="shape" style="left:0px;top:200px"
            class="shape shape-1 move-anim" >
          <img src="./Menu Images/shape-2.png" width="343" height="345" loading="lazy" alt="shape" style="left:1600px"
            class="shape shape-2 move-anim" >

        </div>
      </section>


      <section class="section menu" aria-label="menu-label" id="pizzapasta" style="height: auto;">

        <div class="container" style="height: auto;">

          <p class="section-subtitle text-center label-2" > Pizzas & Pastas </p>

        

          <ul class="grid-list">

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Pizza-1.jpg" width="100" height="100" loading="lazy" alt="Pizza-1"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Cheezy-7 </a>
                    </h3>


                    <span class="span title-2">590 /-</span>
                  </div>

                  <p class="card-text label-1">
                   White Mozzarella , Cream White Cheese , Cheddar Cheese , Monterey Jack Cream , Orange Cheese , Cobly Orange Cheese
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Pasta-1.jpg" width="100" height="100" loading="lazy" alt="Pasta-1"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Pasta Alla Routa</a>
                    </h3>

                    <span class="span title-2">1200 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Spaghetti , Linguini , Hollowed Cheese Wheel , Parmigiano Reggiano
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Pizza-2.jpg" width="100" height="100" loading="lazy" alt="Pizza-2"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Tandoori Paneer</a>
                    </h3>

                    <span class="span title-2">420 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Capsicum , Onion , Paneer , Sweet Corn , Korma Dip , Paprika
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Pasta-2.jpg" width="100" height="100" loading="lazy" alt="Pasta-2"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Fettuccine Alfredo</a>
                    </h3>

                   

                    <span class="span title-2">500 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Fettuccine Pasta , Butter , Heavy Cream , Parmesan Cheese , Nutmeg , Pepper
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Pizza-3.jpg" width="100" height="100" loading="lazy" alt="Pizza-3"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Paneer Tikka Butter Masala</a>
                    </h3>

                    <span class="span title-2">620 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Exotic Paneer Tikka , Onion , Capsicum , Red Paprika , Tandoori Mayonnaise
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Pasta-3.jpg" width="100" height="100" loading="lazy" alt="Pasta-3"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Red Sauce Pasta</a>
                    </h3>

                    <span class="span title-2">350 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Penne Pasta , Tomatoes , Olive , Garlic , Onion , Basil , Oregano , Parsley , Pepper Flakes
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Pizza-4.jpg" width="100" height="100" loading="lazy" alt="Pizza-4"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Burn To Hell</a>
                    </h3>

                    <span class="span title-2">680 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Hot & Garlic Dip , Jalapenoes , Mushrooms , Olives , Capsicum 
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Pasta-4.jpg" width="100" height="100" loading="lazy" alt="Pasta-4"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Spaghetti Aglio-E-Olio</a>
                    </h3>

                    <span class="span title-2">600/-</span>
                  </div>

                  <p class="card-text label-1">
                    Spaghetti Pasta , Garlic , Olive , Red Pepper Flakes , Parsley , Parmesan Cheese
                  </p>

                </div>

              </div>
            </li>

          </ul>
         

          <img src="./Menu Images/shape-5.png" width="921" height="1036" loading="lazy" alt="shape"
            class="shape shape-2 move-anim">
          <img src="./Menu Images/shape-6.png" width="343" height="345" loading="lazy" alt="shape"
            class="shape shape-3 move-anim">

        </div>

      </section>





      <!-- 
        - #SERVICE
      -->

      <section class="section menu  bg-black-10 " aria-label="menu-label" id="deserts" style="height: auto;">
        <div class="container" >

          <p class="section-subtitle text-center label-2" > Derserts</p>

        

          <ul class="grid-list">

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Desert-1.jpg" width="100" height="100" loading="lazy" alt="Greek Salad"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Gulab Jamun</a>
                    </h3>

                   

                    <span class="span title-2">270 /-</span>
                  </div>

                  <p class="card-text label-1">
                  Khoya , Refined Wheat Flour , Butter , Rose Asence , Dry Fruits
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Desert-2.jpg" width="100" height="100" loading="lazy" alt="Lasagne"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Vanilla With Brownie</a>
                    </h3>

                    <span class="span title-2">300 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Vanilla Ice Cream Scoop , Choco Brownie , Choco Chips , Chocolate Syrup , Caramel
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Desert-3.jpg" width="100" height="100" loading="lazy" alt="Butternut Pumpkin"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Ras Malai</a>
                    </h3>

                    <span class="span title-2">320 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Cottage Cheese , Sugar , Milk , cardamon , Saffron , Pistachois , Almonds
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Desert-4.jpg" width="100" height="100" loading="lazy" alt="Tokusen Wagyu"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Choco Truffle</a>
                    </h3>

                    

                    <span class="span title-2">280 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Dark Chocolate , Heavy Cream , Vanilla Extracts , Cocoa Powder , Chopped Nuts
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Desert-5.jpg" width="100" height="100" loading="lazy" alt="Olivas Rellenas"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Rabdi Jalebi</a>
                    </h3>

                    <span class="span title-2">360 /-</span>
                  </div>

                  <p class="card-text label-1">
                   Creamy & Sweetend Milk , Saffron , cardamon , Yogurt , Sugar Syrup , Nuts
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Desert-6.jpg" width="100" height="100" loading="lazy" alt="Opu Fish"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Cassata</a>
                    </h3>

                    <span class="span title-2">350 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Sponge Cake , Ricotta Cheese , Candied Fruits , Nuts , Sugar Syrup , Vanilla Extracts , Marzipan
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Desert-7.jpg" width="100" height="100" loading="lazy" alt="Opu Fish"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Cookies & Cream</a>
                    </h3>

                    <span class="span title-2">220 /-</span>
                  </div>

                  <p class="card-text label-1">
                    Vanilla Ice Cream Base , Chopped Chocolate Cookies Sandwich , ChocolateChips , Crunchy Chocolate Cookie Chips
                  </p>

                </div>

              </div>
            </li>

            <li>
              <div class="menu-card hover:card">

                <figure class="card-banner img-holder" style="--width: 100; --height: 100;">
                  <img src="./Menu Images/Desert-8.jpg" width="100" height="100" loading="lazy" alt="Opu Fish"
                    class="img-cover">
                </figure>

                <div>

                  <div class="title-wrapper">
                    <h3 class="title-3">
                      <a href="#" class="card-title">Red Velvet </a>
                    </h3>

                    <span class="span title-2">450 /-</span>
                  </div>

                  <p class="card-text label-1">
                   Cocoa Powder , Sugar Syrup , Buttermilk , Vinegar , Red Food Colouring
                  </p>

                </div>

              </div>
            </li>

          </ul>

          <img src="./Menu Images/shape-1.png" width="246" height="412" loading="lazy" alt="shape" style="left:0px;top:200px"
            class="shape shape-1 move-anim" >
          <img src="./Menu Images/shape-2.png" width="343" height="345" loading="lazy" alt="shape" style="left:1600px"
            class="shape shape-2 move-anim" >

        </div>
      </section>


     






      




      <!-- 
        - #EVENT
      -->

      <section class="section event bg-black-10" aria-label="event" id="events">
        <div class="container">

          <p class="section-subtitle label-2 text-center">Recent Updates</p>

          <h2 class="section-title headline-1 text-center">Upcoming Event</h2>

          <ul class="grid-list">

            <li>
              <div class="event-card has-before hover:shine">

                <div class="card-banner img-holder" style="--width: 350; --height: 450;">
                  <img src="./Menu Images/Event-1.jpg" width="350" height="450" loading="lazy"
                    alt="Flavour so good you’ll try to eat with your eyes." class="img-cover">

                  <time class="publish-date label-2" datetime="2022-09-15">Weekends</time>
                </div>

                <div class="card-content">
                  <p class="card-subtitle label-2 text-center">DJ Party</p>

                  <h3 class="card-title title-2 text-center">
                    Have a great blast with DJ on every weekends at VINCE.
                  </h3>
                </div>

              </div>
            </li>

            <li>
              <div class="event-card has-before hover:shine">

                <div class="card-banner img-holder" style="--width: 350; --height: 450;">
                  <img src="./Menu Images/Event-2.jpg" width="350" height="450" loading="lazy"
                    alt="Flavour so good you’ll try to eat with your eyes." class="img-cover">

                  <time class="publish-date label-2" datetime="2022-09-08">08/04/2024</time>
                </div>

                <div class="card-content">
                  <p class="card-subtitle label-2 text-center">Good Food Good Mood</p>

                  <h3 class="card-title title-2 text-center">
                    Get Unlimited Burgers and Fries at Just ₹150.
                  </h3>
                </div>

              </div>
            </li>

            <li>
              <div class="event-card has-before hover:shine">

                <div class="card-banner img-holder" style="--width: 350; --height: 450;">
                  <img src="./Menu Images/Event-3.jpg" width="350" height="450" loading="lazy"
                    alt="Flavour so good you'll try to eat with your eyes." class="img-cover">

                  <time class="publish-date label-2" datetime="2022-09-03">01/04/2024</time>
                </div>

                <div class="card-content">
                  <p class="card-subtitle label-2 text-center">Jenga</p>

                  <h3 class="card-title title-2 text-center">
                    Win Jenga , Have a Free Java Choco Coffee
                  </h3>
                </div>
 
              </div>
            </li>

          </ul>

          

        </div>
      </section>

    </article>
  </main>










  <!-- 
    - #BACK TO TOP
  -->

  <a href="#top" class="back-top-btn active" aria-label="back to top" data-back-top-btn>
    <ion-icon name="chevron-up" aria-hidden="true"></ion-icon>
  </a>





  <!-- 
    - custom js link
  -->
  <script src="./assets/js/script.js"></script>

  <!-- 
    - ionicon link
  -->
  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>

</body>

</html>
