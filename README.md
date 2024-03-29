# EX01 Developing a Simple Webserver
## Date: 
29.03.2024

## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title><br>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        .num {
            background-color: #f3f3f3;
            display: flex;
            justify-content: space-around;
            padding: 20px;
        }
        .num .col-5,
        .num .col-4 {
            flex: 1;
            text-align: center;
        }
        h3 {
            margin: 0;
            color:darkblue
        }
        a{
            text-decoration: none;
            color:brown ;
            padding: 10px;
            font-family: Arial;
        }
        i{
            color: brown;
            padding: 5px;
        }
        i:hover{
            color: blueviolet;
        }
    </style>
</head>

<body style="background-color: grey;">
    <div class="row" style="background-color: #f3f3f3">
        <div class="col-4">
            <a href=""><i class="bi bi-twitter"></i></a>
            <a href="https://www.youtube.com/"><i class="bi bi-youtube"></i></a>
            <a href="https://web.whatsapp.com/"><i class="bi bi-whatsapp"></i></a>
            <a href="https://www.linkedin.com/feed/"><i class="bi bi-linkedin"></i></a>
            <a href="https://www.facebook.com/"><i class="bi bi-facebook"></i></a>
            <a href="https://www.instagram.com/"><i class="bi bi-instagram"></i></a>
        </div>
        <div class="col-5">
            <a href="login.html">LOGIN</a><i class="bi bi-grip-vertical"></i>
            <a href="">SK PORTAL</a><i class="bi bi-grip-vertical"></i>
            <a href="admission.html">ADMISSIONS</a>
        </div>
        <div class="col-3">
           <div style="border: solid black 3px; border-radius: 40px;">
            <i class="bi bi-search"></i>
            <input type="text"  name="search" placeholder="Search" style="background-color: #f3f3f3;border: 0px;outline: none;">
           </div>
        </div>
    </div>
    <center><div style="display: flex;"><img src="SK.jpg" alt="" width="1200px" height="250px" style="padding-left:250px;"> </div></center>
    <center><h2>SK ENGINEERING COLLEGE</h2></center>
    <div class="sk" style="display: flex;padding: 10px;background-color: #f3f3f3">
        <div class="col-6">
            <a href="home2.html">HOME</a>
            <a href="about.html">ABOUT</a>
            <a href="dept.html">DEPARTMENTS</a>
            <a href="course.html">COURSES</a>
            <a href="placement.html">PLACEMENTS</a>
        </div>
        <div class="col-6"></div>
    </div>
    <div id="carouselExampleIndicators" class="carousel slide">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="s1.jpg" class="d-block w-100" alt="">
            </div>
            <div class="carousel-item">
                <img src="s2.jpg" class="d-block w-100" alt="">
            </div>
            <div class="carousel-item">
                <img src="s3.jpeg" class="d-block w-100" alt="">
            </div>
            </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
    <div class="pad">
        <br>
    </div>
    <div class="num"  style="background-color: #f3f3f3;display: flex;">
        <div class="col-5">
            <h3>Principal</h3>
            <h3>6303868717</h3>
        </div>
        <div class="col-4">
            <h3>Vice Principal</h3>
            <h3>8179069945</h3>
        </div>
        <div class="col-4"> 
            <h3>Admission</h3>
            <h3>1800 098 6969</h3>
        </div>
    </div>

</body>

</html>

## OUTPUT:

![alt text](s1.png)

![alt text](s2.png)

## RESULT:
The program for implementing simple webserver is executed successfully.
