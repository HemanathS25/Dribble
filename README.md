# Project Responsive Web Design using Bootstrap
## Date:25-12-24

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

    <!-- Bootstrap 5 CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200&icon_names=search" />
</head>

<body class="bg-light">

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-white shadow-sm">
        <div class="container">
            <a class="navbar-brand fs-3 fw-bold" href="#">Dribbble</a>
            <div class="ms-auto">
                <a href="#" class="btn btn-outline-dark me-2">Sign Up</a>
                <a href="#" class="btn btn-danger">Log In</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="text-center py-5">
        <h1 class="display-4 fw-bold">I Planet</h1>
        <p class="lead text-muted">Explore more products with affordable price.</p>

        <!-- Search Bar -->
        <div class="d-flex justify-content-center">
            <div class="position-relative w-100 w-md-50">
                <input type="text" class="form-control rounded-pill ps-4 py-2" placeholder="What are you looking for?">
                <button class="btn btn-danger position-absolute top-50 end-0 translate-middle-y rounded-circle shadow-sm">
                    <span class="material-symbols-outlined">search</span>
                </button>
            </div>
        </div>

        <!-- Trending Searches -->
        <div class="mt-4">
            <button class="btn btn-light me-2 rounded-pill">All</button>
            <button class="btn btn-light me-2 rounded-pill">Mobile</button>
            <button class="btn btn-light me-2 rounded-pill">Mac</button>
            <button class="btn btn-light me-2 rounded-pill">I watch</button>
            <button class="btn btn-light me-2 rounded-pill">Apple care</button>
            <button class="btn btn-light me-2 rounded-pill">Vision pro</button>
        </div>
    </section>

    <!-- Gallery Section -->
    <section class="py-5">
        <div class="container">
            <div class="row g-4">
                <!-- Card 1 -->
                <div class="col-md-4">
                    <div class="card border-0 shadow-sm">
                        <img src="16 pro max.avif" alt="Design" class="card-img-top rounded-3">
                        <div class="card-body p-2">
                            <p class="card-title fs-6 fw-semibold text-center">Apple 16 pro max</p>
                        </div>
                    </div>
                </div>
                <!-- Card 2 -->
                <div class="col-md-4">
                    <div class="card border-0 shadow-sm">
                        <img src="16.webp" alt="Design" class="card-img-top rounded-3">
                        <div class="card-body p-2">
                            <p class="card-title fs-6 fw-semibold text-center">Apple 16</p>
                        </div>
                    </div>
                </div>
                <!-- Card 3 -->
                <div class="col-md-4">
                    <div class="card border-0 shadow-sm">
                        <img src="apple care.jpeg" alt="Design" class="card-img-top rounded-3">
                        <div class="card-body p-2">
                            <p class="card-title fs-6 fw-semibold text-center">Mac pro</p>
                        </div>
                    </div>
                </div>
                <!-- Card 4 -->
                <div class="col-md-4">
                    <div class="card border-0 shadow-sm">
                        <img src="i watch.jpeg" alt="Design" class="card-img-top rounded-3">
                        <div class="card-body p-2">
                            <p class="card-title fs-6 fw-semibold text-center">I watch</p>
                        </div>
                    </div>
                </div>
                <!-- Card 5 -->
                <div class="col-md-4">
                    <div class="card border-0 shadow-sm">
                        <img src="mac pro.jpeg" alt="Design" class="card-img-top rounded-3">
                        <div class="card-body p-2">
                            <p class="card-title fs-6 fw-semibold text-center">Apple care</p>
                        </div>
                    </div>
                </div>
                <!-- Card 6 -->
                <div class="col-md-4">
                    <div class="card border-0 shadow-sm">
                        <img src="vission pro.jpeg" alt="Design" class="card-img-top rounded-3">
                        <div class="card-body p-2">
                            <p class="card-title fs-6 fw-semibold text-center">Vission pro</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Bootstrap Bundle JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>


```


## OUTPUT:


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
