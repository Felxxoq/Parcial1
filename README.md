# Parcial1
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Parcial</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.9.1/font/bootstrap-icons.css" integrity="sha384-xeJqLiuOvjUBq3iGOjvSQSIlwrpqjSHXpduPd6rQpuiM3f5/ijby8pCsnbu5S81n" crossorigin="anonymous">
  </head>
  <body>

    <!-- navbar -->

    <nav class="navbar navbar-expand-lg bg-warning bg-opacity-75 p-2 navbar-dark" >
        <div class="container">
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse align-items-center justify-content-between " id="navbarNavDropdown">
            <div>
                <a class="navbar-brand" href="#">Proyecto final</a>
            </div>
            <div>
                <ul class="navbar-nav ">
                    <li class="nav-item t">
                      <a class="nav-link active " aria-current="page" href="#inicio">Inicio</a>
                    </li>
                    <li class="nav-item ">
                        <a class="nav-link " aria-current="page" href="#datos">Datos generales</a>
                      </li>
                    <li class="nav-item">
                      <a class="nav-link " href="#cursos"> Certificaciones/Cursos</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#habilidades">Habilidades</a>
                    </li>
                    <li class="nav-item">
                      <a class= "nav-link " href="#portafolio">Portafolio</a>
                    </li>
                </ul>
            </div>
          </div>
        </div>
      </nav>

      <!-- showcase -->

    <section class="bg-info p-5 text-white bg-opacity-75" id="inicio" >
        <div class="container">
            <div class="d-sm-flex align-items-center justify-content-between ">
                <div class="col-md  m-5">
                    <h1 class="">Proyecto Final</h1>
                    <p class="lead my-4 ">
                        Te contare sobre mi, mis experiencias y proyectos.
                        No te lo pierdas
                    </p>
                    <button type="button" class="btn btn-warning">Conoceme mas</button>
                </div>
                <img src="./img/img.1.jpg" alt="" class="img-fluid w-40 d-sm-block" width="400">
            </div>
        </div>
    </section>

    <!-- datos -->
    <section id="datos" class="p-5">
        <div class="container">
            <div class="d-md-flex  justify-content-between">
                    <img src="./img/img.jpeg" alt="" class="img-fluid w-25 ">
                <div class=" bg-warning bg-opacity-75 col-md text-center text-white p-3">
                    <h6 >Luis Felipe Quezada Quezada</h6>
                    <h6>luis.lfq@gmail.com</h6>
                    <p>Hola, como ya vieron mi nombe es Luis Felipe Quezada me pueden decir Felipe, soy de El Salvador, Turín Ahuchapán, espero me puedan conocer un pocor,además de conocer mis habilidades y otras muchas mas.</p>
                    <h6>Cursando la carrera de ingeniera en sistemas informaticos </h6>
                    <h6>En la universidad catolica del Salvador</h6>
                    <p> El objetivo de la carrea es de activar o mejorar las habilidades en las areas que conlleva 
                      la informatica, ya se, programacion, html, bases de datos, electronica entre otras. La carrera 
                      tiene una alta variedad de areas en las que te podes especializar y eso es muy bueno porque tenes 
                      bastantes conocimientos sobre las nuevas tecnologias que envuelven a la sociedad. </p>
                    <a href="https://twitter.com/locale=es_LA&_rdr" class="btn btn-info">
                      <i class="bi bi-twitter mx-1" > </i>
                    </a>
  
                    <a href="https://m.facebook.com/?locale=es_LA&_rdr" class="btn btn-primary">
                    <i class="bi bi-facebook mx-1" > </i>
                    </a>
                    <a href="https://www.instagram.com/?locale=es_LA&_rdr" class="btn btn-danger">
                    <i class="bi bi-instagram  mx-1"></i>
                    </a>   
                </div>
            </div>
        </div>
    </section>

    <!-- cursos -->

    <section id="cursos" class="p-5 bg-info bg-opacity-75">
      <div class="container">
          <h2 class="text-center text-white">Cursos</h2> 
          <div class="row g-6 justify-content-between p-3" >
            <div class="col-md-6 col-lg-3">
              <div class="card bg-light">
                <div class="card-body text-center text-light bg-warning bg-opacity-75">
                  <img src="img/img3.jpg" alt=""class="w-100 mb3">
                  <h3 class="card-tittle mb-3 p-2"> Java Netbeans</h3>
                  <p class="card-text">
                    Este curso se basa en el progama de Netbeans usando el legunaje de programacion java script 
                    el objetivo de ello es poder usar el programa de Netbeans a su totalidad y manejar lo que es 
                    el lenguaje de java que es de los mas ocupados actualmente.
                  </p>
                  <a href="https://youtu.be/I75CUdSJifw" class="btn btn-danger p-lg-2 m-lg-2">
                    <i class="bi bi-youtube mx-5 mt-5" > </i>
                   </a> 
                </div>
               </div>
         </div>
            <div class="col-md-6 col-lg-3">
              <div class="card ">
                  <div class="card-body text-center text-light bg-warning bg-opacity-75 ">
                      <img src="img/img2.png" alt=""class="w-75 mb3">
                      <h3 class="card-tittle mb-3 p-2">PHP y MySQL</h3>
                      <p class="card-text">
                      Este curso se basa en los progrmas de PHP y MySQL que se uyilizan para lo que son las bases de datos 
                      y sus diferentes heramientas el objetivo de este curso es aprende nuevas cosas sobre lo que es esta materia y si es posible especializarse 
                      en ella ya que te enseña de lo basico hasta lo mas complejo.
                     <a href="https://youtu.be/I75CUdSJifw" class="btn btn-danger p-lg-2 m-lg-2">
                     <i class="bi bi-youtube mx-5 mt-5" > </i>
                    </a>    
                  </div>
              </div>
            </div>
            <div class="col-md-6 col-lg-3">
              <div class="card bg-light">
                  <div class="card-body text-center text-light bg-warning bg-opacity-75">
                    <img src="img/img5.png" alt=""class="w-100 mb3">
                    <h3 class="card-tittle mb-3 p-2">Python</h3>
                    <p class="card-text">
                      Este curso se basa en el progama de visual studio usando el legunaje de programacion Python 
                      el objetivo de ello es poder usar el programa de visual studio a su totalidad y manejar lo que es 
                      el lenguaje de python que es de los mas ocupados actualmente.
                    </p>
                    <a href="https://youtu.be/DJdBGf7uzg4" class="btn btn-danger p-lg-2 m-lg-2">
                      <i class="bi bi-youtube mx-5 mt-5" > </i>
                     </a> 
                  </div>
                 </div>
          </div>
        </div>
      </div>
  </section>

  <!-- habilidades -->
  <section class="p-5" id="habilidades">
    <div class="container">
      <h1 class="text-center"> Habilidades</h1>
      <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active" data-bs-interval="10000">
            <img src="img/img6.png.crdownload" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5 class="text-danger">Trabajo en equipo</h5>
            </div>
          </div>
          <div class="carousel-item" data-bs-interval="2000">
            <img src="img/img7.jpeg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5 class="text-danger">Conozco varios tipos de lenguajes de programacion</h5>
            </div>
          </div>
          <div class="carousel-item">
            <img src="img/img8.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5 class="text-danger">Puedo desarollar circuitos logicos</h5>
            </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </div>
  </section>

  <!-- portafolo -->
  <section class="p-5 bg-warning bg-opacity-75" id="portafolio">
    <div class="container">
        <h1 class="text-center text-dark mb-4">Portafolio</h1>
        <div class="row g-4 align-items-center justify-content-between">

          <div class="col-md-6 col-lg-3">
                <div class="card-body text-center">
                    <img src="./img/img9.png" alt="" class="w-100">
                    <span class="tema">desarollador <span class="mx-2">
                    <h3 class="card-tittle mb-2">Modelo de un sumador</h3> 
                    <p class="card-text ">
                      El objetivo de nuestro circuito es lograr un sistema para votar de forma electrónica.
                    </p>
                    <div>
                        <button type="button" class="btn btn-info ">Mas info</button>
                    </div>

                </div>
          </div>
          <div class="col-md-6 col-lg-3">
              <div class="card-body text-center">
                <img src="img/img10.png" alt="" class="w-100">
                <span class="tema">desarollador<span class="mx-2">
                <h3 class="card-tittle mb-2">Pag web</h3>
                <p class="card-text">
                    Por medio del html y boostrap se creo lo que es esta pagina web en el progama de visual estudio.
                </p>
                <div>
                    <button type="button" class="btn btn-info">Mas info</button>
                </div>
              </div>
         </div>
          <div class="col-md-6 col-lg-3">
                <div class="card-body text-center">
                  <img src="img/img11.jpeg" alt="" class="w-100">
                  <span class="tema">desarollador<span class="mx-2">
                  <h3 class="card-tittle mb-2">Generar documento</h3> 
                  <p class="card-text">
                    Por medio de lenguaje de programacion java se creo un progama donde el usuario puede elegir como quiere que el documento se descargue
                  </p>
                  <div>
                    <button type="button" class="btn btn-info">Mas info</button>
                </div>
                </div>
        </div>
     </div>
    </div>
</section>

<!-- footer -->

<footer class="p-5 bg-info text-white text-center position-relative">
  <div class="container">
      <div class="lead">Felipe Quezada 
      </div>
      <a href="#" class=" position-absolute bottom-0 end-0 p-5 ">
          <i class="bi bi-arrow-up-circle h1"></i>
      </a>
  </div>
</footer>


  </body>
</html>
