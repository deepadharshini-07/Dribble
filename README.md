# Project Responsive Web Design using Bootstrap
## Date:25-12-2024

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lights Camera Action</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        html, body {
            height: 100%;
        }
        .wrapper {
            display: flex;
            flex-direction: column;
            min-height: 100%;
        }
        .content {
            flex: 1;
        }
    </style>
</head>
<body>
    <div class="wrapper">
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <div class="container">
                <a class="navbar-brand" href="#">Cinema Showcase</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav me-auto">
                        <li class="nav-item">
                            <a class="nav-link" href="#">Movies</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Showtimes</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Trailers</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Contact</a>
                        </li>
                    </ul>
                    <div>
                        <a href="#" class="btn btn-outline-light me-2">Login</a>
                        <a href="#" class="btn btn-primary">Sign Up</a>
                    </div>
                </div>
            </div>
        </nav>

        <div class="container text-center my-5 content">
            <h1>Experience the Magic of Cinema</h1>
            <p>Cinema – where dreams flicker to life, frame by frame 🎬✨.</p>
            <a href="#" class="btn btn-primary btn-lg">Get Tickets</a>
        </div>

        <div class="container my-5">
            <div class="row">
                <div class="col-md-4">
                    <div class="card">
                        <img src="amaran.png" class="card-img-top" alt="Movie 1">
                        <div class="card-body">
                            <h5 class="card-title">LATEST RELEASE</h5>
                            <p class="card-text">Don't miss out the latest images in the big screen.</p>
                            <a href="#" class="btn btn-outline-primary">Explore Showtimes</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="vidamuyarchi.png" class="card-img-top" alt="Movie 2">
                        <div class="card-body">
                            <h5 class="card-title">Upcoming Releases</h5>
                            <p class="card-text">Explore the trailers of the upcoming blockbuster films.</p>
                            <a href="#" class="btn btn-outline-primary">Explore Trailers</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="ghilli.png" class="card-img-top" alt="Movie 3">
                        <div class="card-body">
                            <h5 class="card-title">Blockbuster hits</h5>
                            <p class="card-text">Explore the movies that got the box-office hits.</p>
                            <a href="#" class="btn btn-outline-primary">Rediscover Classics</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <footer class="bg-dark text-center text-white py-3">
            <p>&copy; Designed and Developed by DEEPADHARSHINI T</p>
        </footer>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


```

## OUTPUT:
![alt text](<Screenshot 2024-12-28 134604.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
