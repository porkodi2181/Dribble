# Project Responsive Web Design using Bootstrap
## Date:23.05.2025
## Name: PORKODI B
## Reg no:212224240114

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
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="dribble.css">
    <style>
        body {
            margin: 0;
            padding: 0;
            background-image: url('your-image-url.jpg'); 
            background-size: cover; 
            background-position: center; 
            background-repeat: no-repeat; 
            color: #2c3e50; 
        }
        .gallery-item {
            transition: transform 0.4s ease-in-out, box-shadow 0.3s ease;
        }
        .gallery-item:hover {
            transform: scale(1.05);
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }
        .gallery-img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
    </style>
    
    
</head>
<body>
    
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand" href="#"><h2>Dribbble</h2></a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
               <h2> <li class="nav-item"><a class="nav-link" href="#">Shots</a></li></h2>
               <h2> <li class="nav-item"><a class="nav-link" href="#">Designers</a></li></h2>
               <h2> <li class="nav-item"><a class="nav-link" href="#">Teams</a></li></h2>
               <h2> <li class="nav-item"><a class="nav-link" href="#">Community</a></li></h2>
               <h2> <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li></h2>
               <h2> <li class="nav-item"><a class="btn btn-primary" href="#">Sign Up</a></li></h2>
            </ul>
        </div>
    </nav>

    
    <div class="container mt-4">
        <div class="text-center mb-4 header-section">
            <h2>What are you working on?</h2>
            <p class="lead"><h2>Dribbble is show and tell for designers.</h2></p>
        </div>

        
        <div class="row gallery-section">
            
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="pro 1.jpg" class="card-img-top gallery-img">
                    <div class="card-body text-center">
                        <p class="card-title">BRIDAL</p>
                        <small class="text-muted">MYNTRA</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="pro 2.jpg" class="card-img-top gallery-img">
                    <div class="card-body text-center">
                        <p class="card-title">GHARARA PANT</p>
                        <small class="text-muted">NYKAA FASHION</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="pro 3.jpg" class="card-img-top gallery-img">
                    <div class="card-body text-center">
                        <p class="card-title">PANNEL LOND DRESS</p>
                        <small class="text-muted">SHOPSY</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="pro 4.jpg" class="card-img-top gallery-img">
                    <div class="card-body text-center">
                        <p class="card-title">JEANS WITH KURTIS</p>
                        <small class="text-muted">ZARA</small>
                    </div>
                </div>
            </div>
            
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="pro 5.jpg" class="card-img-top gallery-img">
                    <div class="card-body text-center">
                        <p class="card-title">LEHENGA</p>
                        <small class="text-muted">AJIO</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="pro 6.jpg" class="card-img-top gallery-img">
                    <div class="card-body text-center">
                        <p class="card-title">MALO DESIGN</p>
                        <small class="text-muted">PANTALOONS</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="pro 7.jpg" class="card-img-top gallery-img">
                    <div class="card-body text-center">
                        <p class="card-title">WESTERN</p>
                        <small class="text-muted">BERRYLUSH</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="dre 1.jpg" class="card-img-top gallery-img">
                    <div class="card-body text-center">
                        <p class="card-title">POONAM KASNIA</p>
                        <small class="text-muted">PUMA</small>
                    </div>
                </div>
            </div>
        </div>
    </div>

    
    <footer class="bg-dark text-white text-center py-3">
        <p><h2>© Dribbble. All rights reserved.</h2></p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.bundle.min.js"></script>
</body>
</html>




css
@import url('https://fonts.googleapis.com/css2?family=Pacifico&display=swap');

body {
    font-family: 'Pacifico', cursive;
    margin: 0;
    padding: 0;
    background-color: #bcd4d4; 
    color: #2c3e50; 
}


.navbar {
    background-color: #00695c; 
    box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1); 
}

.navbar-brand, .navbar-nav .nav-link {
    color: #ffffff !important;
}

.navbar-nav {
    flex-direction: row;
}

.navbar-nav .nav-link {
    padding: 0 15px;
}

.nav-item .btn-primary {
    background-color: #ff7043;
    border-color: #ff7043;
}

.nav-item .btn-primary:hover {
    background-color: #d84315; 
    border-color: #d84315;
}


.header-section h3 {
    font-weight: bold;
    color: #00695c; 
}

.header-section p {
    font-size: 1.2em;
    color: #37474f; 
}


.gallery-container {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 20px;
    padding: 20px;
}


.card {
    background-color: #ffffff;
    border: 1px solid #cfd8dc;
    border-radius: 10px;
    box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.08); /* Light shadow */
    overflow: hidden;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 0; 
    margin-bottom: 20px;
}

.card:hover {
    transform: translateY(-5px); 
    box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.15); 
}


.gallery-img {
    width: 100%;
    height: 180px;
    object-fit: cover;
    border-radius: 10px 10px 0 0; 
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    margin-bottom: 0; 
}

.card:hover .gallery-img {
    transform: scale(1.05); 
    box-shadow: 0px 8px 15px rgba(0, 0, 0, 0.25); 
}


.card-title {
    font-weight: bold;
    font-size: 1.1rem;
    color: #00695c; 
    text-align: center;
    margin-top: 15px;
}

.card-body {
    padding: 20px;
    text-align: center;
    flex-grow: 1;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}


footer {
    background-color: #00695c;
    color: #ffffff;
    text-align: center;
    padding: 25px;
    font-size: 0.9em;
    margin-top: 40px;
    box-shadow: 0px -2px 5px rgba(0, 0, 0, 0.1);
}


@media (max-width: 768px) {
    .navbar-nav {
        flex-direction: column;
        text-align: center;
        padding: 10px 0;
    }

    .gallery-section {
        margin-top: 20px;
    }

    .card-body {
        padding: 10px;
    }
}

@media (max-width: 480px) {
    .header-section h3 {
        font-size: 1.5em;
    }

    .header-section p {
        font-size: 1em;
    }
}
```


## OUTPUT:
![Screenshot 2025-05-23 104902](https://github.com/user-attachments/assets/c60399b8-c906-4fa2-aa36-d3467896f9d2)



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
