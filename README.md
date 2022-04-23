# Lab 6 Web

![gambar hasil](lab6_css_framework/Screenshot%20(111).png)

itu merupakan hasil layout dengan menggunakan framework boostrap

## source code

``` html
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>
    <div class="container-md shadow-lg p-3 mb-5 bg-body rounded">
        <div class="card-body">
            <h1 class="text-muted pb-3">Layout Sederhana</h1>
          </div>

          <nav class="navbar navbar-dark" style="background-color: red;">
            <ul class="nav">
                <li class="nav-item">
                  <a class="nav-link active text-light" aria-current="page" href="#">Home</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link text-light" href="#">Article</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link text-light" href="#">About</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link disabled text-light" href="#" tabindex="-1" aria-disabled="true">Contact</a>
                </li>
              </ul>
          </nav>

          <div class="card" style="border: 0px; background-color: #e4e4e5;">
            <div class="card-body">
              <h5 class="card-title"><h2 style="color: #5a5a5a;">Hello World</h2></h5>
              <p class="card-text py-2">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quas, consectetur eaque nostrum, possimus ad saepe illum aliquid natus impedit delectus dolorem quae deserunt doloribus? Accusantium saepe natus, optio fugit odio sit at! Ex neque facilis assumenda corporis dicta quos quae porro odit deleniti accusamus ab, cupiditate, alias reiciendis. Explicabo, minima!</p>
              <a href="#" class="btn btn-primary">Learn More!</a>
            </div>
          </div>

          <div class="container">
            <div class="row row-cols-4">
              <div class="col mt-4">
                <div class="card" style="width: 18rem; border: 0px;">
                    <img src="facebook-black-block.jpg" class="card-img-top rounded-circle" alt="..." style="width: 200px;">
                    <div class="card-body">
                      <h5 class="card-title">Facebook</h5>
                      <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde, reiciendis.</p>
                      <a href="#" class="btn btn-primary">Go somewhere</a>
                    </div>
                  </div>
              </div>
              <div class="col mt-4">
                <div class="card" style="width: 18rem; border: 0px;">
                    <img src="github-logo.jpg" class="card-img-top rounded-circle" alt="..." style="width: 200px;">
                    <div class="card-body">
                      <h5 class="card-title">Git Hub</h5>
                      <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde, reiciendis.</p>
                      <a href="#" class="btn btn-primary">Go somewhere</a>
                    </div>
                  </div>
              </div>
              <div class="col mt-4">
                <div class="card" style="width: 18rem; border: 0px;">
                    <img src="ig-logo-black.jpg" class="card-img-top rounded-circle" alt="..." style="width: 200px;">
                    <div class="card-body">
                      <h5 class="card-title">Instagram</h5>
                      <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde, reiciendis.</p>
                      <a href="#" class="btn btn-primary">Go somewhere</a>
                    </div>
                  </div>
              </div>
              <div class="col">
                <div class="list-group mt-4">
                    <a href="#" class="list-group-item list-group-item-action active" aria-current="true">
                      Widget Header
                    </a>
                    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                  </div>
                  <div class="list-group mt-4">
                    <a href="#" class="list-group-item list-group-item-action active" aria-current="true">
                      Widget Text
                    </a>
                    <a href="#" class="list-group-item list-group-item-action"><p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aspernatur porro fuga quae veniam eos dolores autem quia pariatur rem ipsa, nulla, ea accusantium non obcaecati nam. Nostrum veritatis ut est!</p></a>
                  </div>
              </div>
            </div>
          </div>

          <div class="row">
              <div class="col-8-md">
                <div class="card mb-3" style="max-width: 540px; border: 0px; margin-top: -100px;">
                    <div class="row g-0">
                      <div class="col-md-4">
                        <img src="hinata.jpg" class="img-fluid rounded-start" alt="..." style="border: 1px solid black;">
                      </div>
                      <div class="col-md-8">
                        <div class="card-body">
                          <h5 class="card-title">Card title</h5>
                          <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                          <p class="card-text"><small class="text-muted">Last updated 7 mins ago</small></p>
                        </div>
                      </div>
                    </div>
                  </div>
              </div>
          </div>

          <div class="card-footer" style="background-color: #1d1d1d;">
              <p class="text-light pt-2">&copy; 2022 - Universitas Pelita Bangsa</p>
          </div>
      </div>
      
    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
    -->
  </body>
</html>
```