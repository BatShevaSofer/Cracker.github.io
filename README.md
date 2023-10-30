<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Courgette&family=Nosifer&display=swap" rel="stylesheet">
    <link rel="apple-touch-icon" sizes="180x180" href="./favicon_io/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="./favicon_io/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="./favicon_io/favicon-16x16.png">
    <link rel="manifest" href="/site.webmanifest">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="./bootstrap.min/bootstrap.min.css">
    <link rel="stylesheet" href="./Css_pages/header_footer.css">
    <link rel="stylesheet" href="./Css_pages/home_page.css">
    <title>Cracker</title>
</head>

<body>
    <header class="container-fluid position-sticky top-0 start-0">
        <div class="container">
            <nav class="navbar navbar-expand-lg navbar-dark ">
                <div class="container-fluid">
                    <a class="navbar-brand d-flex align-items-center" href="#">
                        <img src="./Cyber_images/logo.png" alt="" width="86" height="60"
                            class="d-inline-block align-text-top">
                        <div class="cracker">Cracker</div>
                    </a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarNav">
                        <ul class="navbar-nav text-sm-center">
                            <li class="nav-item">
                                <a class="nav-link active" aria-current="page" href="./index.html">Home</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="./Html_pages/about.html">About</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="./Html_pages/gallery.html">Gallery</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="./Html_pages/f_a_q.html">FAQ</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="./Html_pages/contact.html">Contact Us</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="./Html_pages/trivia.html">Trivia</a>
                            </li>
                        </ul>

                    </div>
                    <button class="contact d-none d-lg-block">
                        <a href="./Html_pages/contact.html" class="text-decoration-none">
                            Contact Us
                        </a>
                    </button>
                </div>
            </nav>
        </div>
    </header>


    <div class="bg_big container-fluid d-md-none d-flex justify-content-center align-content-center"
        style="background-image: url(./Cyber_images/slider4.jpg); min-height: 300px; background-size: cover;">
    </div>
    <main class="strip container-fluid p-0 d-md-block d-none mt-0 ">
        <!-- carousel start -->
        <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
                    aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"
                    aria-label="Slide 2"></button>
                <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"
                    aria-label="Slide 3"></button>
                <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="3"
                    aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <!-- <img src="images/cover2.jpg" class="d-block w-100" alt="..."> -->
                    <div class="bg_pic" style="background-image: url(./Cyber_images/slider4.jpg);"></div>
                    <div class="carousel-caption d-none d-md-block slider1">
                        <div data-aos="fade-down-right">
                            <h5>The most innovative</h5>
                            <p>We have the most innovative technologies for the best service for you!</p>
                        </div>
                    </div>
                </div>
                <div class="carousel-item ">
                    <!-- <img src="images/cover2.jpg" class="d-block w-100" alt="..."> -->
                    <div class="bg_pic" style="background-image: url(./Cyber_images/slider2.jpg);"></div>
                    <div class="carousel-caption d-none d-md-block slider2">
                        <h5>Full reports</h5>
                        <p>With us you will receive full reports on every step, how many laws we broke, how many years
                            in prison you will spend on it and what exactly we did on your mission</p>
                    </div>
                </div>
                <div class="carousel-item ">
                    <!-- <img src="f35_images/strip.png" class="d-block w-100" alt="..."> -->
                    <div class="bg_pic" style="background-image: url(./Cyber_images/slider3.jpg);"></div>
                    <div class="carousel-caption d-none d-md-block slider3">
                        <h5>information</h5>
                        <p>All information about your victim will be disclosed to you including all his most
                            confidential information</p>
                    </div>
                </div>

                <div class="carousel-item ">
                    <!-- <img src="f35_images/strip.png" class="d-block w-100" alt="..."> -->
                    <div class="bg_pic" style="background-image: url(./Cyber_images/slider1.jpg);"></div>
                    <div class="carousel-caption d-none d-md-block slider4">
                        <h5>All for you</h5>
                        <p>We will sit for you at all hours of the day until we succeed (don't worry, it won't take long
                            :))</p>
                    </div>
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions"
                data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions"
                data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
    </main>
    <div class="d-none d-lg-block container text-center text-white p-2 victim">
        <h2>Our victims</h2>
    </div>
    <section class="d-none d-lg-block container p-3 d-flex flex-nowrap">
        <div class="row justify-content-between align-items-center">

            <div class="col m-2">
                <img src="./Cyber_images/icons/129px-Interpol_logo.jpg" alt="">
            </div>
            <div class="col m-2">
                <img src="./Cyber_images/icons/CIA-Seal-BW@2x@2x-bd6f6da4ab65dc1fe7aeb76fe043f66f.png" alt="">
            </div>
            <div class="col m-2">
                <img src="./Cyber_images/icons/FBI.png" alt="">
            </div>
            <div class="col m-2">
                <img src="./Cyber_images/icons/IDF.jpg" alt="">
            </div>

            <div class="col m-2">
                <img src="./Cyber_images/icons/Iran_police.png" alt="">
            </div>

            <div class="col m-2">
                <img src="./Cyber_images/icons/mossad.png" alt="">
            </div>
            <div class="col m-2">
                <img src="./Cyber_images/icons/polis.png" alt="">
            </div>
            <div class="col m-2">
                <img src="./Cyber_images/icons/shabak.jpg" alt="">
            </div>


            <!-- <div class="col m-2">
                <img src="./Cyber_images/icons/intel-header-logo.svg" alt="">
            </div> -->

        </div>
    </section>


    <main class="container ">
        <div class="d-flex justify-content-between m-4 p-0" style="min-height: 700px;">
            <div data-aos="flip-left" class="leftMain col-lg-2 bg-info">

            </div>

            <a href="https://www.itgovernance.co.uk/what-is-cybersecurity" target="_blank"
                class="col-lg-7 col-md-12 bg-gradient text-decoration-none">
                <div class="img_cyber m-0 px-0">
                </div>
                <div class="d-flex align-items-center">
                    <div data-aos="fade-down" class="text-center">
                        <p class="m-4">
                            In our organization, the duo "cyber security" is a challenge and stimulates our
                            adrenaline,
                            And the more you bring us a larger and more classified company, the more fun we will
                            have
                            serving
                            you
                            (Don't worry, we manage to break the record of minus 10 service stars)
                        </p>
                    </div>
                </div>
            </a>

            <div data-aos="flip-right" class="rightMain col-lg-2 bg-success">

            </div>

        </div>
    </main>






    <article class="container mt-4">
        <div class="d-lg-flex justify-content-between">
            <div class="img_hover0 col-5 " data-aos="fade-right">
                <!-- <img src="./Cyber_images/3d-internet-secuirty-badge.jpg" width="500px" alt=""> -->
                <div class="overlay overlay0">
                    <p class="p-3">We will try to make sure that all the strongest passwords your victim has are exposed
                        to
                        you, all the security consultants and cyber warriors will not be able to stand against us, we
                        will
                        make sure to leave a back door open for you on your victim's server so that you will always have
                        access to the server.</p>
                </div>
            </div>
            <div data-aos="fade-left" class="col-7 d-lg-block d-none">
                <h2 class="text-white p-3">Trust us</h2>
                <div class="d-flex align-items-center">
                    <p class="p-3 ">We will try to make sure that all the strongest passwords your victim has are
                        exposed to
                        you, all the security consultants and cyber warriors will not be able to stand against us, we
                        will
                        make sure to leave a back door open for you on your victim's server so that you will always have
                        access to the server.</p>
                </div>
            </div>
        </div>
        <div class="d-lg-flex justify-content-between m-3">
            <div data-aos="fade-right" class="col-7 d-lg-block d-none">
                <h2 class="text-white p-3">Anonymity</h2>
                <div class="d-flex align-items-center">

                    <p class="p-3">All our actions will remain anonymous including the access doors we leave for you.
                        No one in the world including the largest intelligence agencies in the world will be able to
                        know
                        who we are.
                        We have no responsibility for you :)
                        Try to be careful and if you don't have too much knowledge in data transfer, it's better not to
                        touch otherwise you will get caught too quickly :).</p>
                </div>
            </div>
            <div data-aos="fade-left" data-aos-delay="600" class="col-5 img_hover1">
                <!-- <img src="./Cyber_images/hacker-3342696_1920.jpg" width="500px" alt=""> -->
                <div class="overlay overlay1">
                    <p class="p-3">All our actions will remain anonymous including the access doors we leave for you.
                        No one in the world including the largest intelligence agencies in the world will be able to
                        know who we are.
                        We have no responsibility for you :)
                        Try to be careful and if you don't have too much knowledge in data transfer, it's better not to
                        touch otherwise you will get caught too quickly :).</p>
                </div>
            </div>
        </div>
    </article>


























    <!-- Site footer -->
    <footer class="site-footer p-4">
        <hr>

        <div class="container">
            <div class="row">
                <div class="col-md-8 col-sm-6 col-xs-12">
                    <p class="copyright-text">Copyright &copy; 2023 All Rights Reserved by
                        <a href="#">Bat Sheva Sofer</a>.
                    </p>
                </div>

                <div class="col-md-4 col-sm-6 col-xs-12">
                    <ul class="social-icons">
                        <li><a class="facebook text-center" href="#"><i class="fa fa-facebook"></i></a></li>
                        <li><a class=" text-center" href="#"><i class="fa fa-twitter"></i></a></li>
                        <li><a class="dribbble text-center" href="#"><i class="fa fa-dribbble"></i></a></li>
                        <li><a class="linkedin text-center" href="#"><i class="fa fa-linkedin"></i></a></li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>



















    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script>
        AOS.init();
    </script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
        crossorigin="anonymous"></script>

    <script src="../JS_pages/home_page.js"></script>

</body>

</html>
