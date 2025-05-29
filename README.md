# Project Responsive Web Design using Bootstrap
## Date:

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
    <title>vamsi's Clothing Store</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">vamsi's Clothing Store</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#products">Products</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Content Sections -->
    <div id="home" class="container text-center my-5">
        <h1>Welcome to Our Clothing Store</h1>
        <p class="lead">Explore our exclusive collection of clothing and accessories.</p>
    </div>

    <div id="products" class="container my-5">
        <h2 class="text-center">Our Products</h2>
        <div class="row mt-4">
            <div class="col-md-4">
                <a href="product1.html" class="text-decoration-none">
                    <div class="card">
                        <img src="c:\Users\admin\Downloads\download.jpg" class="card-img-top" style="height: 400px; object-fit: cover;" alt="Shirt">
                        <div class="card-body">
                            <h5 class="card-title">Shirt</h5>
                            <p class="card-text">Stylish and comfortable shirts for all occasions.</p>
                        </div>
                    </div>
                </a>
            </div>
            <div class="col-md-4">
                <a href="product2.html" class="text-decoration-none">
                    <div class="card">
                        <img src="c:\Users\admin\Downloads\OIP.jpg" class="card-img-top" style="height: 400px; object-fit: cover;" alt="Jeans">
                        <div class="card-body">
                            <h5 class="card-title">Jeans</h5>
                            <p class="card-text">High-quality jeans in various styles and fits.</p>
                        </div>
                    </div>
                </a>
            </div>
            <div class="col-md-4">
                <a href="product3.html" class="text-decoration-none">
                    <div class="card">
                        <img src="c:\Users\admin\Downloads\download (1).jpg" class="card-img-top" style="height: 400px; object-fit: cover;"alt="Jacket">
                        <div class="card-body">
                            <h5 class="card-title">Jacket</h5>
                            <p class="card-text">Keep warm with our trendy jackets.</p>
                        </div>
                    </div>
                </a>
            </div>
        </div>
    </div>

    <!-- Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

<!-- Product Pages -->

<!-- product1.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shirt Details</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <div class="container text-center my-5">
        <h1>Shirt</h1>
        <img src="c:\Users\admin\Downloads\download.jpg" class="img-fluid my-3" alt="Shirt">
        <p class="lead">Stylish and comfortable shirts for all occasions. Available in multiple sizes and colors.</p>
        <button class="btn btn-primary" onclick="history.back()">Go Back</button>
    </div>
</body>
</html>

<!-- product2.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jeans Details</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <div class="container text-center my-5">
        <h1>Jeans</h1>
        <img src="c:\Users\admin\Downloads\OIP.jpg" class="img-fluid my-3" alt="Jeans">
        <p class="lead">High-quality jeans in various styles and fits. Perfect for casual and formal wear.</p>
        <button class="btn btn-primary" onclick="history.back()">Go Back</button>
    </div>
</body>
</html>

<!-- product3.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jacket Details</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <div class="container text-center my-5">
        <h1>Jacket</h1>
        <img src="c:\Users\admin\Downloads\download (1).jpg" class="img-fluid my-3" alt="Jacket">
        <p class="lead">Keep warm with our trendy jackets. Perfect for winter and outdoor adventures.</p>
        <button class="btn btn-primary" onclick="history.back()">Go Back</button>
    </div>
    <div id="contact" class="container my-5">
        <h2 class="text-center">Contact Us</h2>
        <form class="mt-4">
            <div class="mb-3">
                <label for="name" class="form-label">Name</label>
                <input type="text" class="form-control" id="name" placeholder="Your Name">
            </div>
            <div class="mb-3">
                <label for="email" class="form-label">Email</label>
                <input type="email" class="form-control" id="email" placeholder="Your Email">
            </div>
            <div class="mb-3">
                <label for="message" class="form-label">Message</label>
                <textarea class="form-control" id="message" rows="3" placeholder="Your Message"></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Submit</button>
        </form>
    </div>
    <!-- Footer -->
    <footer class="bg-primary text-white text-center py-3">
        &copy; 2024 Clothing Store. All Rights Reserved.
    </footer>
</body>
</html>
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/4e3f3ecc-50d0-483f-8f5d-fb676ae579bc)
![image](https://github.com/user-attachments/assets/11298d53-c44d-421e-ad0f-7447ce016dd5)
![image](https://github.com/user-attachments/assets/3040f639-7559-4714-9400-4b28c911f130)
![image](https://github.com/user-attachments/assets/1993682f-2c56-48c2-8f20-f9c53ea819fe)
![image](https://github.com/user-attachments/assets/a8ddc76a-64a1-4efb-959b-929a7bd397fb)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
