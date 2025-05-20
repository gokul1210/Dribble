# Project Responsive Web Design using Bootstrap
## Date:20/05/2025

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
    <title>Dribbble Clone</title>
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Dribbble Clone</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item active">
                        <a class="nav-link" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Shots</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Explore</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Sign Up</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Sign In</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="bg-info text-white text-center py-5">
        <div class="container">
            <h1 class="display-4">Welcome to Dribbble Clone</h1>
            <p class="lead">Showcasing stunning designs, illustrations, and digital art from talented creators.</p>
            <a href="#" class="btn btn-light btn-lg">Explore Shots</a>
        </div>
    </section>

    <!-- Featured Shots Section -->
    <section class="py-5 bg-light">
        <div class="container text-center">
            <h2 class="mb-4 text-dark">Featured Shots</h2>
            <p class="lead mb-4 text-muted">Discover some of the best creative shots uploaded by our community.</p>
            <div class="row">
                <!-- Shot 1 -->
                <div class="col-md-4 mb-4">
                    <div class="card shadow-sm border-light">
                        <img src="hoodie.1.jpeg" class="card-img-top" alt="Shot 1">
                        <div class="card-body">
                            <h5 class="card-title text-primary">Shot Title 1</h5>
                            <p class="card-text text-muted">A short description of the design.</p>
                        </div>
                    </div>
                </div>
                <!-- Shot 2 -->
                <div class="col-md-4 mb-4">
                    <div class="card shadow-sm border-light">
                        <img src="pants.2.jpeg" class="card-img-top" alt="Shot 2">
                        <div class="card-body">
                            <h5 class="card-title text-primary">Shot Title 2</h5>
                            <p class="card-text text-muted">A short description of the design.</p>
                        </div>
                    </div>
                </div>
                <!-- Shot 3 -->
                <div class="col-md-4 mb-4">
                    <div class="card shadow-sm border-light">
                        <img src="watch.3.jpeg" class="card-img-top" alt="Shot 3">
                        <div class="card-body">
                            <h5 class="card-title text-primary">Shot Title 3</h5>
                            <p class="card-text text-muted">A short description of the design.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="bg-dark text-white py-4 text-center">
        <p class="mb-0">&copy;Developed by GOKUL S</p>
    </footer>

    <!-- Bootstrap JS and dependencies -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>


```

## OUTPUT:
![alt text](<Screenshot 2025-05-20 214318.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
