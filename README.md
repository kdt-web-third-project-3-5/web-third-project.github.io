<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Home</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-iYQeCzEYFbKjA/T2uDLTpkwGzCiq6soy8tYaI1GyVh/UjpbCx/TYkiZhlZB6+fzT" crossorigin="anonymous">
  </head>
  <body class="d-flex flex-column min-vh-100">
    <nav class="navbar navbar-expand-lg bg-black">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <img src="./images/logo.png" alt="Logo" width="50" height="50">
        </a>
        <button class="navbar-toggler bg-white" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link active text-white" aria-current="page" href="./index.html">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white-50" href="./03_community.html">Community</a>
            </li>
            <li class="nav-item">
              <!-- Button trigger modal -->
              <button type="button" class="btn btn-dark text-white-50 px-0" data-bs-toggle="modal" data-bs-target="#exampleModal">
              Login
              </button>

              <!-- Modal -->
              <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
                <div class="modal-dialog">
                  <div class="modal-content">
                    <div class="modal-header">
                      <h5 class="modal-title" id="exampleModalToggleLabel">Modal title</h5>
                      <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                    </div>
                    <div class="mb-3 m-3">
                      <label for="exampleInputEmail1" class="form-label fw-bold" >Email address</label>
                      <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                      <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
                    </div>
                    <div class="mb-3 m-3">
                      <label for="exampleInputPassword1" class="form-label fw-bold">Password</label>
                      <input type="password" class="form-control" id="exampleInputPassword1">
                    </div>
                    <div class="mb-3 form-check m-3">
                      <input type="checkbox" class="form-check-input fw-bold" id="exampleCheck1">
                      <label class="form-check-label fw-bold" for="exampleCheck1">Check me out</label>
                    </div>
                    <div class="modal-footer m-3">
                      <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                      <button type="button" class="btn btn-primary">Summit</button>
                    </div>
                  </div>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <div id="carouselExampleFade" class="carousel slide carousel-fade" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="./images/star_wars_the_rise_of_skywalker_movie_december_2019-wallpaper-1920x600.jpg" class="d-block w-100" alt="...">
        </div>
        <div class="carousel-item">
          <img src="./images/no_time_to_die_movie_james_bond-wallpaper-1920x600.jpg" class="d-block w-100" alt="...">
        </div>
        <div class="carousel-item">
          <img src="./images/peter_morales-wallpaper-1920x600.jpg" class="d-block w-100" alt="...">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
    <div>
      <div class="d-flex justify-content-center fw-bold">
        <h2>Boxoffice</h2>
      </div>
      <div class="container text-center">
        <div class="row row-cols-1 row-cols-sm-2 row-cols-lg-3">
          <div class="my-1">
            <a href="./05_movie.html"><image class="rounded img-fluid" src="./images/movie1.jpg" alt="#"></image>
            </a>
          </div>
          <div class="my-1">
            <image class="rounded img-fluid" src="./images/movie2.jpg" alt="#"></image>
          </div>
          <div class="my-1">
            <image class="rounded img-fluid" src="./images/movie3.jpg" alt="#"></image>
          </div>
          <div class="my-1">
            <image class="rounded img-fluid" src="./images/movie4.jpg" alt="#"></image>
          </div>
          <div class="my-1">
            <image class="rounded img-fluid" src="./images/movie5.jpg" alt="#"></image>
          </div>
          <div class="my-1">
            <image class="rounded img-fluid" src="./images/movie6.jpg" alt="#"></image>
          </div>
        </div>
      </div>
    </div>
    <footer class="mt-auto fixed-bottom">
      <p class="text-white bg-black d-flex justify-content-center align-items-center m-0">© 2022 Movie Ranking</p>
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-u1OknCvxWvY5kfmNBILK2hRnQC3Pr17a+RTT6rIHI7NnikvbZlHgTPOOmMi466C8" crossorigin="anonymous"></script>
  </body>
</html>
