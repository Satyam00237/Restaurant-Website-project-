# Restaurant-Website-project-
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurents </title>
    <link rel="stylesheet" type="text/css"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css">



  <!--  <link rel="stylesheet" href="style.css">  -->

    <!-- Link Swiper's CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper/swiper-bundle.min.css" />

</head>
<style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700&display=swap');

:root {
    color: #333;
    lighting-color: #cdaa7c;
    box-shadow: 0.5rem 1.5rem rgba(0, 0, 0, .1);

}

* {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
    border: none;
    outline: none;
    text-transform: capitalize;
    transition: all .2s linear;

}

header img {
    height: 50px;
}

header h4 {
    margin-left: 5px;
    color: white;

}

html {
    font-size: 62.5%;
    overflow-x: hidden;
    scroll-behavior: smooth;

}

header {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    background: var(black);
    padding: 1rem 7%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: rgb(29, 29, 29);
    box-shadow: var();
    z-index: 10000;
}

header .navbar a {
    font-size: 1.7rem;
    padding: 0.5rem 1.5rem;
    color: var(lighting-color);
    border: .1rem solid transparent;
}

.navbar a {
    color: #cdaa7c;
}


header .navbar a.active {
    color: #fff;
    border: .1rem solid rgba(205, 170, 124, 0.2);
}

header .navbar a:hover {
    color: #fff;
    border: .1rem solid rgba(205, 170, 124, 0.2);
}

header .icons i {
    cursor: pointer;
    margin-left: .5rem;
    height: 4.5rem;
    width: 4.5rem;
    line-height: 4.5rem;
    background: #cdaa7c;
    text-align: center;
    font-size: 1.7rem;
    color: #fff;
}

header .icons i:hover {
    color: #fff;
    transform: rotate(360deg);
}

header .icons #menu {
    display: none;
}


/* navbar style end here */

/* slider style start*/
.home .home-slider .slide{
    display: flex;
    align-items: center;
    height: 100vh;

    justify-content: flex-start;

}

.home .home-slider .slide1{
    background: url(abc123.jpg);
    
}
.home .home-slider .slide2{
    background: url(2.webp);   
}
.home .home-slider .slide3{
    background: url(zxcv.jpg );
    
}

.home .home-slider .slide1,
.home .home-slider .slide2,
.home .home-slider .slide3
{
    background-size: cover;
    background-repeat: no-repeat;

}
.home .home-slider .slide .content{
    text-align: center;
    padding-left: 9rem;
}
.home .home-slider .slide .content h3{
    color: var(white);
    font-size: 3rem;
    font-weight: 300;

}
.home .home-slider .slide .content h1{
    color: #fff;
    font-size: 8rem;
}
.home .home-slider .slide .content p{
    color: #e6e7e7;
    font-size: 1.8rem;
    letter-spacing: 1px;
    padding: .5rem 0;
    line-height: 1.5;
    font-weight: 200;


}
.btn{
    margin-top: 1rem;
    display: inline-block;
    font-size: 1.7rem;
    color: #fff;
    border: .01rem solid rgba(247, 140, 0, 0.2);
    background: transparent;
    cursor: pointer;
    padding: .8rem 3rem;
    position: relative;
    overflow: hidden; 
    z-index: 1;
}
.btn:before{
    content: ' ';
    width: 100%;
    height: 100%;
    background:var(--light-color);
    z-index: -1; 
   position: absolute;
   top: 0;
   left: -100%;
   transition: .5s;  
   


}
.btn:hover.btn{
    
}
.btn:hover .btn::before{
    left: 0;

}
.swiper-pagination-bullet{
    background: #ff9100!important ;
    width: 15px!important;
    height: 15px!important;
    border-radius: 0!important;

}





/*slider style end */

/* Welcome style starts here*/
section{
    padding: 8rem 9%;
}
.heading{
    text-align: center;
    color: black;
    font-size: 4.5rem;
    padding-bottom:2rem ;
    text-transform: uppercase;
  /*  letter-spacing: .7rem; */
}
.sub-heading{
    text-align: center;
    color: red;
    font-size: 2.5rem;
    padding: .5rem .2rem;
    font-weight: 300;
    margin-bottom: 4rem;
    background: black;
    display: inline-block;
}
.welcome .box-container{
    display: flex;
    gap: 1.5rem;
}
.welcome .box-container .box{
    width: 33%;
    background: black;
    box-shadow: var(--box-shadow);
    text-align: center;
    padding-bottom: 1%;

}

.welcome .box-container .box .image{
    height: 25rem;
    width: 100%;
    overflow: hidden;
    position: relative;
}
.welcome .box-container .box .image img{
    height: 100%;
    width: 100%;
    object-fit: cover;
}
.welcome .box-container .box .image:hover img{
    transform: scale(1.1);
}
.welcome .box-container .box .content{
    padding: 2rem;
    padding-top: 2rem;
}
.welcome .box-container .box .content h3{
    color: orange;
    font-size: 2.2rem;
    font-weight: 400;
}
.welcome .box-container .box .content p{
    color: #fff;
    font-size: 1.4rem;
    font-weight: 300;
    padding: .5rem 0;
    line-height: 1.5;
}



/* Welcome style end here*/

/* our menu starts here*/

.our-menu{
    background: url() left top no-repeat , url(back-1.webp);
}

.our-menu .menu-container{
    padding: 3rem 0;
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(50rem,2fr));
    gap: 5rem 20rem;
}
.our-menu .menu-container .item .item-name{
    display: flex;
    justify-content: space-between;
    padding: 1rem 0;
    margin-top: .5rem;
}
.our-menu .menu-container .item .item-name  h2{
    font-size: 3rem;
    color: #e5e5e5;
    font-weight: 300;

}
.our-menu .menu-container .item .item-menu h3{
    font-size: 2rem;
    color: #e5e5e5;
    font-weight: 200;
    display: inline-block;
}

.our-menu .menu-container .item .item-menu span{
    width: 37%;
    display: inline-block;
    border: 1px dotted #e5e5e5;
}
.our-menu .menu-container .item .item-menu ul{
    display: flex;
    font-size: 1.5rem;
    list-style:none;
    padding: .8rem 0;
    font-weight: 200;
}
.our-menu .menu-container .item .item-menu ul li a{
    color: #b9b9b9;
    color: #b9b9b9;
}

.our-menu .menu-container{
    grid-template-columns: repeat(auto-fit,minmax(30rem,2fr));
}

.our-menu .menu-container .item .item-menu span{
    width: 15%;
}
.our-menu .heading{
    color:white;
}

/* our menu ends here*/
/*reservation section starts here*/
.reservation{
    display: flex;
    width: 100%;
    flex-wrap: wrap;
    background-color: black;
    

}
.reservation .image{
    
    width: 55%;
    background:url(menu-3.png);
    background-repeat: no-repeat;
    background-position: center center;
    padding-top: 9rem;

}
.reservation .form{
    background: #181818;
    width: 45%;
    padding: 9rem 7%;
}
.reservation .form h1{
    color: #fff;

}
.reservation .form-holder{
    display: flex;
    grid-gap: 3rem;
    width: 100%;
}
.reservation .form form input,
.reservation .form form select{
    display: block;
    margin: 2rem 0;
    width: 100%;
    background: none;
    border-bottom:.1rem solid #b7b3b3 ;
    color: #b7b3b3;
    font-size: 1.8rem;
    font-weight: 300;
}
.reservation .form form input::placeholder{
    color: #b7b3b3;
}

/*reservatio section ends here*/

/*blog section start here*/
.blog .box-container .box{
    background: #fff;

}
.blog .content{
    text-align: left;
    position: relative;
    background-color:black;
}
.blog .content h3,
.blog .content p,
.blog .content a{
   /* color: #333!important;  */
    
}
.blog .content a{
    font-size: 14px;
    display: inline-block;
    padding-top: 1rem;
    text-decoration: underline;
    
}
.blog .content a:hover{
    color: gray;
}
.blog .content img{
    position: absolute;
    right: 0;
    bottom: 0;
    
}


/*blog section end here*/

/*footer section starts */
.footer{
    background: #333;
    text-align: center;
    color: #b2b2b2;
    font-size: 1.3rem;
}
.footer .container{
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(30rem,2fr));
    color: #b2b2b2;
    grid-gap: 1rem;
    padding: 4rem 0;
    border-bottom: 1px solid #b2b2b2;
}

.footer .container div{
    padding: 0 7rem;
}
.footer .container h3{
    color: #fff;
    font-size: 1.5rem;
    padding-bottom: .8rem;
}
.footer .container input{
    width: 100%;
    border: 1px solid #b2b2b2;
    border-radius: 20px;
}
.footer .container ul{
    list-style: none;
    display: flex;
    justify-content: center;
    padding-top: 1rem;
}
.footer .container ul li a{
    color: #b2b2b2;
    margin-left: 10px;
    font-size: 18px;

}
.footer .container span{
    display: block;
}



/*footer section end */

/*CUSTOM SCROLL BAR*/

::-webkit-scrollbar{
    width: 12px;
}
::-webkit-scrollbar-track{
    background: #333;

}

::-webkit-scrollbar-thumb{
    background: #cdaa7c;
}
/*jump to top*/
.topbtn{
    position: fixed;
    right: 2%;
    bottom: 10%;
    width: 30px;
    height: 30px;
    background:#cdaa7c;
    color:#fff;
}

/*media query */

@media (max-width:991px) {
    html {
        font-size: 55%;
    }

    header {
        padding: 1rem 2rem;
    }

    header .logo img {
        height: 7rem;
    }
}

@media(max-width:768px) {

    /* navbar media query*/
    header .logo img {
        height: 7rem;

    }

    header .icons #menu {
        display: inline-block;
    }

    header .navbar {
        position: absolute;
        top: 100%;
        left: 0;
        right: 0;
        background: #eee;
        border-top: .1rem solid rgba(205, 170, 124, 0.2);
        border-bottom: .1rem solid rgba(205, 170, 124, 0.2);
        padding: 1rem;
        clip-path: polygon(0 0, 100% 0, 100% 0, 0 0);

    }

    header .navbar.active {
        clip-path: polygon(0 0, 100% 0, 100% 100%, 0 100%);

    }

    header .navbar a {
        display: block;
        padding: 1.5rem;
        margin: 1rem;
        font-size: 2rem;
        background: black;
    }
    /*slider media query */

    .home .home-slider .slide{
        justify-content: center;
        height: 80vh;
    }
    .home .home-slider .slide .content{
        padding: 0;
    }
    .home .home-slider .slide .content h1{
        font-size: 7rem;
    }

   /* welcome section */

   .welcome .box-container{
    flex-wrap: wrap;

   }
   .welcome .box-container .box{
    width: 100%;
   }
   .reservation .image{
    width: 0;
   }
   .reservation .form{
    width: 100%;
   }
   .reservation .form .form-holder{
    display: block;
   }

}

</style>

<body>
    <!--header section start-->
    <header>
        <div class="satyam">
            <a href="#" class="logo"><img src="logo2.jpg" alt=""> 
                <h4></h4>
            </a>
        </div>

        <nav class="navbar">
            <a href="#home" class="active">home</a>
            <a href="#about">about</a>
           <!-- <a href="#menu">menu</a>
            <a href="#team">team</a>  -->
            <a href="#reservation">reservation</a>
            <a href="#blog">blog</a>
        </nav>

        <div class="icons">
            <i class="fas fa-bars" id="menu"></i>
            <i class="fas fa-search"></i>
            <i class="fas fa-heart"></i>
            <i class="fas fa-shopping-cart"></i>
        </div>
    </header>
    <!--header section end-->
    <!--slider section starts-->

    <div class="home" id="home">
        <div class="swiper home-slider">
            <div class="swiper-wrapper wrapper">
                <div class="swiper-slide slide slide1">
                    <div class="content">
                        <!-- <img src="logo.png" alt=""> -->

                        <h1>gift voucher</h1>
                        <p>
                            give away you beloved customers
                        </p>
                        <a href="#" class="btn">order now</a>
                    </div>
                </div>
                <div class="swiper-slide slide slide2">
                    <div class="content">
                        <!-- <img src="logo.png" alt="" height="150px" > -->
                        <h3>Sale of 10% this dish</h3>
                        <h1>The fresh</h1>
                        <p>
                            food Restaurent
                        </p>
                        <a href="#" class="btn">order now</a>
                    </div>
                </div>

                <div class="swiper-slide slide slide3">
                    <div class="content">
                        <!-- <img src="logo.png" alt="" height="150px" > -->
                        <h3>We are open</h3>
                        <h1>fresh fruits</h1>
                        <p>
                            you will love it
                        </p>
                        <a href="#" class="btn">order now</a>
                    </div>
                </div>



            </div>
            <div class="swiper-pagination"></div>
        </div>
    </div>

    <!--slider section end-->
    <section class="welcome" id="about">
        <h1 class="heading">WELCOME TO RED CHILLI</h1>
        <center>
            <h3 class="sub-heading"> ~ Luxury & Quality</h3>
        </center>

        <div class="box-container">
            <div class="box">
                <div class="image">
                    <img src="qua-4.webp" alt="" height="250px">
                </div>

                <div class="content">
                    <h3>PROFESSIONAL LEVEL</h3>
                    <P>We have professional levels of chef that makes awesome food </P>
                    <a href="" class="btn">Read Mores</a>
                    </P>
                </div>
            </div>

            <div class="box">
                <div class="image">
                    <img src="qua-2.jpg" alt="" height="260px">
                </div>

                <div class="content">
                    <h3>FRESH FOOD GUARANTEED</h3>
                    <P>We are offer fresh food in our Restaurent. Our chefs are best and Our food are also best at best prices.</P>
                    <a href="" class="btn">Read Mores</a>
                    </P>
                </div>
            </div>

            <div class="box">
                <div class="image">
                    <img src="qua-3.jpg" alt="" height="260px">
                </div>

                <div class="content">
                    <h3>THE MENU IS PLENTIFUL</h3>
                    <P>Our Restaurent is offering more than 100 items and Also with a affordable price.</P>
                    <a href="" class="btn">Read Mores</a>
                    </P>
                </div>
            </div>
        </div>

    </section>
    <!--welcome section start here-->

    <!--our menu section start-->
    <section class="our-menu" id="menu">
        <h1 class="heading">our food menu</h1 >
        <center>
            <h3 class="sub-heading"> ~ see what we offer</h3>
        </center>

        <div class="menu-container">

            <div class="item">
                <div class="item-name">
                    <h2>Main course</h2>
                    <img src="" alt="">
                </div>

                <div class="item-body">
                    <div class="item-menu">
                        <h3>Super-Delicioud Zuppa Toscana</h3>
                        <span class="dots"></span>
                        <h3>$26</h3>

                        <ul>
                            <li><a href="">Chicken</a></li>

                            <li><a href="">Italian</a></li>
                            <li><a href="">Sausage</a></li>
                            <li><a href="">Spinach</a></li>
                        </ul>
                    </div>

                    <div class="item-menu">
                        <h3>Super-Delicioud Zuppa Toscana</h3>
                        <span class="dots"></span>
                        <h3>$40</h3>

                        <ul>
                            <li><a href="">Mushroom</a></li>
                            <li><a href="">Italian</a></li>
                            <li><a href="">Sausage</a></li>
                            <li><a href="">Spinach</a></li>
                        </ul>
                    </div>
                </div>
            </div>

            <div class="item">
                <div class="item-name">
                    <h2>Soups & Salads</h2>
                    <img src="" alt="">
                </div>

                <div class="item-body">
                    <div class="item-menu">
                        <h3>Super-Delicioud Zuppa Toscana</h3>
                        <span class="dots"></span>
                        <h3>$26</h3>

                        <ul>
                            <li><a href="">Chicken</a></li>.

                            <li><a href="">Italian</a></li>
                            <li><a href="">Sausage</a></li>
                            <li><a href="">Spinach</a></li>
                        </ul>
                    </div>

                    <div class="item-menu">
                        <h3>Super-Delicioud Zuppa Toscana</h3>
                        <span class="dots"></span>
                        <h3>$40</h3>

                        <ul>
                            <li><a href="">Mushroom</a></li>
                            <li><a href="">Italian</a></li>
                            <li><a href="">Sausage</a></li>
                            <li><a href="">Spinach</a></li>
                        </ul>
                    </div>
                </div>
            </div>


            <div class="item">
                <div class="item-name">
                    <h2>Drinks</h2>
                    <img src="" alt="">
                </div>

                <div class="item-body">
                    <div class="item-menu">
                        <h3>Super-Delicioud Zuppa Toscana</h3>
                        <span class="dots"></span>
                        <h3>$26</h3>

                        <ul>
                            <li><a href="">Chicken</a></li>

                            <li><a href="">Italian</a></li>
                            <li><a href="">Sausage</a></li>
                            <li><a href="">Spinach</a></li>
                        </ul>
                    </div>

                    <div class="item-menu">
                        <h3>Super-Delicioud Zuppa Toscana</h3>
                        <span class="dots"></span>
                        <h3>$40</h3>

                        <ul>
                            <li><a href="">Mushroom</a></li>
                            <li><a href="">Italian</a></li>
                            <li><a href="">Sausage</a></li>
                            <li><a href="">Spinach</a></li>
                        </ul>
                    </div>
                </div>
            </div>

            <div class="item">
                <div class="item-name">
                    <h2>Desserts</h2>
                    <img src="" alt="">
                </div>

                <div class="item-body">
                    <div class="item-menu">
                        <h3>Super-Delicioud Butter Chicken</h3>
                        <span class="dots"></span>
                        <h3>$26</h3>

                        <ul>
                            <li><a href="">Chicken</a></li>
                            <li><a href="">Butter Chicken </a></li>
                            <li><a href="">Sausage </a></li>
                            <li><a href="">Spinach </a></li>
                        </ul>  
                    </div>

                    <div class="item-menu">
                        <h3>Super-Delicioud Zuppa Toscana</h3>
                        <span class="dots"></span>
                        <h3>$40</h3>

                        <ul>
                            <li><a href="">Mushroom</a></li>
                            <li><a href="">Italian</a></li>
                            <li><a href="">Sausage</a></li>
                            <li><a href="">Spinach</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!--our menu section end-->

   

    <!--reservation  section start-->
    <div class="reservation" id="reservation">
        <div class="image">

        </div>

        <div class="form">
            <h1 class="heading">Book a table</h1>
            <center><h3 class="sub-heading">~ check out our place</h3>
            </center>

            <form>
                <div class="form-holder">
                    <div>
                        <select>
                            <option>1 people</option>
                            <option>2 people</option>
                            <option>3 people</option>
                            <option>4 people</option>
                        </select>

                        <input type="text" name="" placeholder="Time">
                        <input type="text" name="" placeholder="phone">

                    </div>

                    <div>
                        <input type="text" name="" placeholder="Date">
                        <input type="text" name="" placeholder="Name">
                        <input type="email" name="" placeholder="email">
                    </div>
                </div>
                <center><a href="#" class="btn">Book now</a></center>
            </form>
        </div>
    </div>





    <!--reservation  section end-->


    <!--news section start-->
    <section class="blog welcome" id="blog">
        <h1 class="heading">Latest news</h1>
        <center><h3 class="sub-heading"> ~ Greate articles</h3></center>

        <div class="box-container">
            <div class="box">
                <div class="image">
                    <img src="news-1.jpg" alt="" width="220px">
                </div>
                
                <div class="content">
                    <h3>PROFFESSIONAL LEVEL</h3>
                    <P>We have professional levels of chef that makes awesome food</P>
                    <a href="#">READ MORE</a>
                    <img src="" alt="" width="220px">
                </div>
            </div>

            <div class="box">
                <div class="image">
                    <img src="news-2.jpg" alt="">
                </div>
                
                <div class="content">
                    <h3>FRESH FOOD GUARANTEED</h3>
                    <P>We are offer fresh food in our Restaurent. Our chefs are best and Our food are also best at best prices.</P>
                    <a href="#">READ MORE</a>
                    <img src="" alt="">
                </div>
            </div>

            <div class="box">
                <div class="image">
                    <img src="news-3.jpg" alt="" height="150px" width="220px">
                </div>
                
                <div class="content">
                    <h3> THE MENU IS PLENTIFUL</h3>
                    <P>Our Restaurent is offering more than 100 items and Also with a affordable price.</P>
                    <a href="#">READ MORE</a>
                    <img src="">
                </div>
            </div>
        </div>
    </section>



    <!--news section end-->
    <!--footer section start -->
    <section class="footer">
        <img src="logo2.jpg" class="logo">

        <div class="container">
            <div>
                <h3>ABOUT US</h3>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus at unde eligendi voluptate!</p>
            </div>

            <div>
                <h3>GET NEWS & OFFERS</h3>
                <input type="email" name="" placeholder="Enter your email">
                <ul>
                    <li><a href=""><i class="fa-brands fa-twitter"></i></a></li>
                    <li><a href=""><i class="fa-brands fa-instagram"></i></a></li>
                    <li><a href=""><i class="fa-brands fa-whatsapp"></i></a></li>
                    <li><a href=""><i class="fa-brands fa-linkedin"></i></a></li>
                </ul>

            </div>
            <div>
                <h3>CONTACT US</h3>
                <span>Creative Networks Tohana</span>
                <span>+ (91) 7257008160</span>
                <span>CreativeNetworks001@gmail.com</span>
                <span>www.Creativenetworks.in</span>
            </div>
        </div>

        <p>&copy;2022 Reserved by creative networks</p>



    </section>


    <!--footer section end-->

    <!--jump to top-->
<a href="#"><button class="topbtn"><i class="fa-solid fa-angle-up"></i></button></a>



    <!-- Swiper JS -->
    <script src="https://cdn.jsdelivr.net/npm/swiper/swiper-bundle.min.js"></script>

    <!-- Initialize Swiper -->
    <script>
        var swiper = new Swiper(".home-slider", {
            spaceBetween: 30,
            centeredSlides: true,
            autoplay: {
                delay: 7500,
                disableOnInteraction: false,
            },
            pagination: {
                el: ".swiper-pagination",
                clickable: true,
            },
            loop: true,
        });
    </script>

    <script>
        let menu = document.querySelector('#menu');
        let navbar = document.querySelector('.navbar');

        menu.onclick = () => {
            menu.classList.toggle('fa-times');
            navbar.classList.toggle('active');
        }
    </script>

</body>
</html>
