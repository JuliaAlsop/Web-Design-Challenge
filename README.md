<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>Web Visualization Homework</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" class="row justify-content-end" 
    <div class="col-md-2" 
    <div class="col-md-3"
    href="index.html">Latitude </a></div>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" class="row justify-content-end" id="navbarSupportedContent">
      <div class="col-md-9"></div>
      <ul class="navbar-nav mr-auto">
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            Plots
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="figurea.html">Max Temperature</a>
            <div class="dropdown-divider"></div>
            <a class="dropdown-item" href="figureb.html">Humidity</a>
            <div class="dropdown-divider"></div>
            <a class="dropdown-item" href="figurec.html">Cloudiness</a>
            <div class="dropdown-divider"></div>
            <a class="dropdown-item" href="figured.html">Wind Speed</a>
          </div>
        </li>
        <li class="nav-item active">
            <a class="nav-link" href="comparison.html">Comparison <span class="sr-only">(current)</span></a>
          </li>
        <li class="nav-item active">
            <a class="nav-link" href="data.html">Data <span class="sr-only">(current)</span></a>
          </li>
        </nav>

  <div class="container">
    <div class="jumbotron">
      <h1 class="display-4">Max Temperature</h1>
      <div class="dropdown-divider"></div>
      <hr class="md-">
      <section id="figure">
        <h2 id="Figure 1">Latitude Vs. Temperature</h2>
        <a href="figurea.html">
        <img id="Figure 1" src="Resources\assets\images\Fig1.png" alt="Figure 1: Latitude vs. Temperature"
        width="600" height="500">
        </a>
      </section>
      <div class="dropdown-divider"></div>
      <p>This homework involves the use of Bootstrap, HTML, and CSS to create a multi web page layout 
          that links each image to a respective page. This enables the viewer easy access to any 
          visualizations needed in order to better analyze the given weather data.  </p>
      <p>There are a total of seven seperate pages available for the viewer including:</p>
      <p> 1. Home page </p>
      <p> 2. Comparison page</p>
      <p> 3. Data table page</p>
      <p> 4.-7. Analysis pages where a specific graph is the focal point of analysis</p>
      <p>
        
      </p>
    </div>
  </nav>

  <aside>
  <div class="container">
    <div class="jumbotron">
      <h1 class="display-9">Visualizations</h1>
      <div class="dropdown-divider"></div>
      <section id="figure">
        <h2 id="Figure 1">Latitude Vs. Temperature</h2>
        <a href="figurea.html">
        <img id="Figure 1" src="Resources\assets\images\Fig1.png" alt="Figure 1: Latitude vs. Temperature"
        width="100" height="100">
        </a>
    <section id="figure">
      <h2 id="Figure 2">City Latitude Vs. Humidity</h2>
      <a href="figureb.html">
      <img id="Figure 2" src="Resources\assets\images\Fig2.png" alt="Figure 2: City Latitude vs. Humidity"
      width="100" height="100">
        </a>
    <section id="figure">
    <h2 id="Figure 3">City Latitude Vs. Cloudiness</h2>
    <a href="figurec.html">
    <img id="Figure 3" src="Resources\assets\images\Fig3.png" alt="Figure 3: City Latitude vs. Cloudiness"
    width="100" height="100">
    </a>
    <section id="figure">
      <h2 id="Figure 4">City Latitude Vs. Wind Speed</h2>
      <a href="figured.html">
      <img id="Figure 4" src="Resources\assets\images\Fig4.png" alt="Figure 4: City Latitude vs. Wind Speed"
      width="100" height="100">
      </a>
    </section>
    </div><
  </aside>
</div>

<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>

</body>

</html>
