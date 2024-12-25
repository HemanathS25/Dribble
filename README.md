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
    <link
        href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=Playfair+Display:wght@700&display=swap"
        rel="stylesheet">

    <link rel="stylesheet"
        href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200&icon_names=search" />
    <!-- Custom CSS -->
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8f9fa;
            margin: 0;
        }

        /* Navbar */
        .navbar-brand {
            font-weight: bold;
            font-size: 1.5rem;
            color: #000;
        }

        .btn-primary {
            background-color: #ea4c89;
            border: none;
            border-radius: 20px;
            padding: 8px 20px;
        }

        .btn-primary:hover {
            background-color: #d44077;
        }

        /* Hero Section */
        .hero-section {
            padding: 60px 20px;
            text-align: center;
        }

        .hero-section h1 {
            font-family: 'Playfair Display', serif;
            font-size: 3rem;
            color: #333;
        }

        .hero-section p {
            font-size: 1.1rem;
            color: #666;
        }

        .search-bar {
            max-width: 500px;
            margin: 20px auto;
            position: relative;
        }

        .search-bar input {
            width: 100%;
            padding: 12px 20px;
            border: 1px solid #ddd;
            border-radius: 30px;
        }

        .search-bar .btn {
            position: absolute;
            right: 10px;
            top: 50%;
            transform: translateY(-50%);
            border-radius: 50%;
            background-color: #ea4c89;
            color: #fff;
        }

        /* Trending Section */
        .trending-buttons .btn {
            background-color: #f1f1f1;
            border: none;
            border-radius: 20px;
            margin: 5px;
            color: #333;
            padding: 6px 12px;
            font-size: 0.9rem;
        }

        .trending-buttons .btn:hover {
            background-color: #eaeaea;
        }

        /* Gallery Section */
        .gallery-section {
            padding: 40px 0;
        }

        .gallery img {
            width: 100%;
            border-radius: 15px;
            transition: transform 0.3s;
        }

        .gallery img:hover {
            transform: scale(1.05);
        }

        .card-title {
            font-size: 0.9rem;
            font-weight: 600;
            margin: 10px 0 0;
        }
    </style>
</head>

<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg bg-white shadow-sm">
        <div class="container">
            <a class="navbar-brand" href="#">Dribbble</a>
            <div class="ms-auto">
                <a href="#" class="btn btn-outline-dark me-2">Sign Up</a>
                <a href="#" class="btn btn-primary">Log In</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-section">
        <h1>I Planet</h1>
        <p>Explore more products with affordable price.</p>
        <div class="search-bar">
            <input type="text" placeholder="What are you looking for?" class="form-control">
            <button class="btn"><span class="material-symbols-outlined">
                    search
                </span>
            </button>
        </div>
        <!-- Trending Searches -->
        <div class="trending-buttons">
            <button class="btn">All</button>
            <button class="btn">Mobile</button>
            <button class="btn">Mac</button>
            <button class="btn">I watch</button>
            <button class="btn">Apple care</button>
            <button class="btn">Pision pro</button>
        </div>
    </section>

    <!-- Gallery Section -->
    <section class="gallery-section">
        <div class="container">
            <div class="row g-4">
                <!-- Card 1 -->
                <div class="col-md-4">
                    <div class="card border-0">
                        <img src="16 pro max.avif"
                            alt="Design" class="card-img-top">
                        <div class="card-body p-2">
                            <p class="card-title">Apple 16 pro max</p>
                        </div>
                    </div>
                </div>
                <!-- Card 2 -->
                <div class="col-md-4">
                    <div class="card border-0">
                        <img src="16.webp"
                            alt="Design" class="card-img-top">
                        <div class="card-body p-2">
                            <p class="card-title">Apple 16</p>
                        </div>
                    </div>
                </div>
                <!-- Card 3 -->
                <div class="col-md-4">
                    <div class="card border-0">
                        <img src="apple care.jpeg"
                            alt="Design" class="card-img-top">
                        <div class="card-body p-2">
                            <p class="card-title">Mac pro</p>
                        </div>
                    </div>
                </div>
                <!-- Card 4 -->
                <div class="col-md-4">
                    <div class="card border-0">
                        <img src="i watch.jpeg"
                            alt="Design" class="card-img-top">
                        <div class="card-body p-2">
                            <p class="card-title">I watch</p>
                        </div>
                    </div>
                </div>
                <!-- Card 5 -->
                <div class="col-md-4">
                    <div class="card border-0">
                        <img src="mac pro.jpeg"
                            alt="Design" class="card-img-top">
                        <div class="card-body p-2">
                            <p class="card-title">Apple care</p>
                        </div>
                    </div>
                </div>
                <!-- Card 6 -->
                <div class="col-md-4">
                    <div class="card border-0">
                        <img src="vission pro.jpeg"
                            alt="Design" class="card-img-top">
                        <div class="card-body p-2">
                            <p class="card-title">Vission pro</p>
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
![alt text](<Screenshot 2024-12-25 214122.png>)
![alt text](<Screenshot (33).png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
