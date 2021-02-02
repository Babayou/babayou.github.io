<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site Portfolio</title>
    <!-- CSS Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-giJF6kkoqNQ00vy+HMDP7azOuL0xtbfIcaT9wjKHr8RbDVddVHyTfAAsrekwKmP1" crossorigin="anonymous">
    <!-- CSS ImageHover (flip effect on portfolio) -->
    <link rel="stylesheet" href="css/imagehover.min.css">
    <!-- mon CSS -->
    <link rel="stylesheet" href="style.css">
</head>

<body id="top">

    <!-- ///////////////////////////////////////////
     //////////Header Navbar sticky/////////////
     Mettre menu burger? 
    ////////////////////////////////////////////   -->

    <ul class="nav bg-primary sticky-top shadow ">
        <div class="col-5 d-flex justify-content-center align-self-center">
            <a href="#top" class="nav-link text-white"> Mon site</a>
        </div>
        <div class="col-7 d-flex justify-content-center">
            <li class="nav-item">
                <a class="nav-link active text-white" aria-current="page" href="#portefolio">Porte Folio</a>
            </li>
            <li class="nav-item">
                <a class="nav-link text-white" href="#about">About</a>
            </li>
            <li class="nav-item">
                <a class="nav-link text-white" href="#contact">Contact</a>
            </li>
        </div>
    </ul>

    <!-- ///////////////////////////////////////////
     ////////////////Carousselle////////////////////
    ////////////////////////////////////////////   -->

    <div id="carouselExampleCaptions" class="carousel slide " data-bs-ride="carousel">
        <ol class="carousel-indicators">
            <li data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"></li>
            <li data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"></li>
        </ol>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="https://via.placeholder.com/1500x500" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Lorem</h5>
                    <p>Nulla vitae elit libero, a pharetra augue mollis interdum.</p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="https://via.placeholder.com/1500x500" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Lorem</h5>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                </div>
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </a>
    </div>



    <!-- ///////////////////////////////////////////
     //////////////Section Porte Folio /////////////
    ////////////////////////////////////////////   -->

    <div class="container-fluid pb-3" id="portefolio">
        <div class=" h3 d-flex justify-content-center pt-5">Porte Folio</div>

        <!-- ligne et éclair -->

        <div class="row">
            <div class="col-2"></div>
            <div class="col-3">
                <hr>
            </div>
            <div class="col-2 text-center"> <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30"
                    fill="currentColor" class="bi bi-lightning-fill" viewBox="0 0 16 16">
                    <path
                        d="M11.251.068a.5.5 0 0 1 .227.58L9.677 6.5H13a.5.5 0 0 1 .364.843l-8 8.5a.5.5 0 0 1-.842-.49L6.323 9.5H3a.5.5 0 0 1-.364-.843l8-8.5a.5.5 0 0 1 .615-.09z" />
                </svg></div>
            <div class="col-3">
                <hr>
            </div>
            <div class="col-2"></div>
        </div>

        <!-- photos -->
        <div class="row">
            <div class="col-12 col-md-6 col-lg-4  d-flex justify-content-center text-center ">
                <figure class="imghvr-flip-vert m-3 shadow rounded bg-primary ">
                    <img src="https://via.placeholder.com/200">
                    <figcaption>
                        Lorem
                    </figcaption>
                </figure>
            </div>

            <div class="col-12 col-md-6 col-lg-4  d-flex justify-content-center text-center ">
                <figure class="imghvr-flip-vert m-3 shadow rounded bg-primary ">
                    <img src="https://via.placeholder.com/200">
                    <figcaption>
                        Lorem
                    </figcaption>
                </figure>
            </div>

            <div class="col-12 col-md-6 col-lg-4  d-flex justify-content-center text-center ">
                <figure class="imghvr-flip-vert m-3 shadow rounded bg-primary ">
                    <img src="https://via.placeholder.com/200">
                    <figcaption>
                        Lorem
                    </figcaption>
                </figure>
            </div>

            <div class="col-12 col-md-6 col-lg-4  d-flex justify-content-center text-center ">
                <figure class="imghvr-flip-vert m-3 shadow rounded bg-primary ">
                    <img src="https://via.placeholder.com/200">
                    <figcaption>
                        Lorem
                    </figcaption>
                </figure>
            </div>

            <div class="col-12 col-md-6 col-lg-4  d-flex justify-content-center text-center ">
                <figure class="imghvr-flip-vert m-3 shadow rounded bg-primary ">
                    <img src="https://via.placeholder.com/200">
                    <figcaption>
                        Lorem
                    </figcaption>
                </figure>
            </div>

            <div class="col-12 col-md-6 col-lg-4  d-flex justify-content-center text-center ">
                <figure class="imghvr-flip-vert m-3 shadow rounded bg-primary ">
                    <img src="https://via.placeholder.com/200">
                    <figcaption>
                        Lorem
                    </figcaption>
                </figure>
            </div>
        </div>
    </div>

    <!-- ///////////////////////////////////////////
 //////////////// ABOUT   ////////////////////
 ////////////////////////////////////////////   -->

    <div class="container-fluid bg-primary shadow pb-3" id="about">
        <div class=" h3 pt-5 text-white d-flex justify-content-center text-center"> About </div>

        <!-- Ligne et lunettes  -->

        <div class="row">
            <div class="col-2"></div>
            <div class="col-3">
                <hr>
            </div>
            <div class="col-2  text-center"><svg xmlns="http://www.w3.org/2000/svg" width="30" height="30"
                    fill="currentColor" class="bi bi-eyeglasses" viewBox="0 0 16 16">
                    <path
                        d="M4 6a2 2 0 1 1 0 4 2 2 0 0 1 0-4zm2.625.547a3 3 0 0 0-5.584.953H.5a.5.5 0 0 0 0 1h.541A3 3 0 0 0 7 8a1 1 0 0 1 2 0 3 3 0 0 0 5.959.5h.541a.5.5 0 0 0 0-1h-.541a3 3 0 0 0-5.584-.953A1.993 1.993 0 0 0 8 6c-.532 0-1.016.208-1.375.547zM14 8a2 2 0 1 1-4 0 2 2 0 0 1 4 0z" />
                </svg></div>
            <div class="col-3">
                <hr>
            </div>
            <div class="col-2"></div>
        </div>


        <!-- texte -->

        <div class="row pb-3">
            <div class="col-2"></div>
            <div class="col-12 col-lg-3   text-justify pt-3">Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                Hic saepe ad
                temporibus quaerat tempore, eius labore ea accusantium exercitationem amet est voluptatum illo
                laboriosam dolor et sed nisi quos a.</div>
            <div class="col-2"></div>
            <div class="col-12 col-lg-3  text-justify pt-3">Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Voluptatem
                incidunt
                molestiae error nobis sit, tenetur aperiam consequatur eveniet obcaecati, quas corporis? At, placeat.
                Magnam nesciunt qui itaque? Iure, asperiores error!</div>
        </div>
        <div class="col-2"></div>
    </div>

    <!-- ///////////////////////////////////////////
 //////////////// CONTACT   ////////////////////
 ////////////////////////////////////////////   -->

    <div class="h3 p-5 d-flex justify-content-center text-center" id="contact">Contactez-moi!</div>
    <div class="container">
        <form>
            <div class="mb-3">
                <label for="name" class="form-label">Name</label>
                <input type="text" class="form-control" id="name">
            </div>
            <div class=" mb-3">
                <label for="exampleInputEmail1" class="form-label">Email address</label>
                <input type="email" class="form-control" id="exampleInputEmail1">
            </div>
            <div class=" mb-3">
                <label for="exampleInputEmail1" class="form-label">Message</label>
                <textarea class="form-control" aria-label="With textarea"></textarea>
            </div>

            <button type="submit" class="btn btn-primary">Send</button>
        </form>
    </div>



    <!-- ///////////////////////////////////////////
 //////////////// FOOTER   ////////////////////
 ////////////////////////////////////////////   -->


    <div class="container-fluid mt-3 bg-primary text-white" ">
        <div class=" row pt-3">
        <div class="col-12 col-lg-4 text-center ">
            <p class="h3">Location</p>
            <p>Adresse</p>
        </div>
        <div class="col-12 col-lg-4 text-center">
            <p class="h3">Around the WEB</p>
            <div class="d-flex justify-content-center">
                <a href="https://www.rencontrevieuxgay.fr/view-profile,321350,gerontophile.html" target="blank"><svg xmlns="http://www.w3.org/2000/svg" width="60" height="60" fill="currentColor"
                        class="bi bi-facebook bg-dark p-2 m-2 rounded-circle  " viewBox="0 0 16 16">
                        <path
                            d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951z" />
                    </svg></a>
                <a href="https://twitter.com/?lang=fr" target="blank"><svg xmlns="http://www.w3.org/2000/svg" width="60" height="60" fill="currentColor"
                        class="bi bi-twitter bg-dark p-2 m-2 rounded-circle" viewBox="0 0 16 16">
                        <path
                            d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382A3.323 3.323 0 0 1 .64 6.575v.045a3.288 3.288 0 0 0 2.632 3.218 3.203 3.203 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z" />
                    </svg></a>
                <a href="https://www.google.fr/" target="blank"><svg xmlns="http://www.w3.org/2000/svg" width="60" height="60" fill="currentColor"
                        class="bi bi-google bg-dark p-2 m-2 rounded-circle" viewBox="0 0 16 16">
                        <path
                            d="M15.545 6.558a9.42 9.42 0 0 1 .139 1.626c0 2.434-.87 4.492-2.384 5.885h.002C11.978 15.292 10.158 16 8 16A8 8 0 1 1 8 0a7.689 7.689 0 0 1 5.352 2.082l-2.284 2.284A4.347 4.347 0 0 0 8 3.166c-2.087 0-3.86 1.408-4.492 3.304a4.792 4.792 0 0 0 0 3.063h.003c.635 1.893 2.405 3.301 4.492 3.301 1.078 0 2.004-.276 2.722-.764h-.003a3.702 3.702 0 0 0 1.599-2.431H8v-3.08h7.545z" />
                    </svg></a>
            </div>
        </div>
        <div class="col-12 col-lg-4 text-center">
            <p class="h3">About Freelance</p>
            <p> Description</p>
        </div>
    </div>
    </div>

    <!-- JS Bootstrap -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ygbV9kiqUc6oa4msXn9868pTtWMgiQaeYH7/t7LECLbyPA2x65Kgf80OJFdroafW"
        crossorigin="anonymous"></script>
</body>

</html>
