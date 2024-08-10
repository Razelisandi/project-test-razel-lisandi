

<template>
  <!DOCTYPE html>
  <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Document</title>
    </head>

    <body>
        <div class="col-12 topnav me-5">
          <nav class="navbar navbar-expand-lg bg-navbar  ">
            <div class="container-fluid m-2">
              <img class="logo ps-5" src="D:\Download\logo suitmedia png 2.png" href="" alt="">
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <div class="position-absolute end-0 pe-5 me-5">
                  <ul class="navbar-nav">
                    <li class="nav-item">
                      <a class="nav-link text-light" aria-current="page" href="#">Work</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link text-light" href="#">About</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link text-light" href="#">Services</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link text-light  active" href="#">Ideas</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link text-light" href="#">Careers</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link text-light" href="#">Contact</a>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </nav>
        </div>

      <div>
        <img class="w-100 pic1" src="D:\Download\Pic1.jpg">
        <h1 class="centered1 text-white">Ideas</h1>
        <h4 class="centered2 text-white">Where all our great things begin</h4>
      </div>  

      <div class="container mt-5">
        <div class="row">
          <div class="col-4">
            <p class="fw-semibold mt-1">
              Showing 1-10 of 100
            </p>
          </div>
          <div class="col-5 text-end">
            <p class="fw-semibold me-0 pe-0 mt-1">Show per page:</p>
          </div>
          <div class="col-1 ms-0 ps-0 dropdown">
            <button class="btn border border-secondary rounded-pill dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">
                10
            </button>
            <ul class="dropdown-menu dropdown-menu-dark">
              <li><a class="dropdown-item active" href="#">10</a></li>
              <li><a class="dropdown-item" href="#">50</a></li>
              <li><a class="dropdown-item" href="#">100</a></li>
            </ul>
          </div>
          <div class="col-1 mt-1 fw-semibold text-end">
            <p>Sort by:</p>
          </div>
          <div class="col-1 ms-0 ps-0 dropdown">
            <button class="btn border border-secondary rounded-pill dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">
                Newest
            </button>
            <ul class="dropdown-menu dropdown-menu-dark">
              <li><a class="dropdown-item active" href="#">Newest</a></li>
              <li><a class="dropdown-item" href="#">Latest</a></li>
            </ul>
          </div>
        </div>
      </div>
    </body>

  </html>
</template>

<style>

.logo{
  max-width: 17%;
  padding: 0;
  margin: 0;
}

/*Warna Background Navbar*/
.bg-navbar{
  background-color: rgb(255, 140, 0);
}

/*Warna Active Link*/
.topnav a:hover {
  border-bottom: 3px solid white;
}
.topnav a.active {
  border-bottom: 3px solid White;
}

/*Brightness Gambar*/
.pic1{
  filter: brightness(50%);
}

/*Posisi Teks 1*/
.centered1 {
  position: absolute;
  top: 40%;
  left: 50%;
  transform: translate(-50%, -50%);
}
/*Posisi Teks 2*/
.centered2 {
  position: absolute;
  top: 45%;
  left: 50%;
  transform: translate(-50%, -50%);
}


</style>