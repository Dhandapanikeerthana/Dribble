# Project Responsive Web Design using Bootstrap
## Date:23.12.2024

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
index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribbble Website</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

  </head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="#">Dribbble Website</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="index.html">index</a></li>
          <li class="nav-item"><a class="nav-link" href="shots.html">shots</a></li>
          <li class="nav-item"><a class="nav-link" href="sign up.html">sign up</a></li>
          <li class="nav-item"><a class="nav-link" href="profile.html">profile</a></li>
          <button type="button" class="btn btn-success btn-sm"> sign up </button>
          <br>
        </ul>
      </div>
    </div>
  </nav>

  <div class="profile-banner text-center text-grey">
    <div>Welcome to Designer's Portfolio</div>
  </div>
  <div class="text-center mt-3">
    <img src="img.png" alt="Profile" class="profile-img">
    <div class="alert-primary"><b>Dan Cederholm and Rich Thornett</b></div> 
    <div class="alert alert-black"><b>Founder of Dribble</b></div>   
  </div>
 <div class="container mt-5">
    <h4>Recent Shots</h4>
    <div id="shots-gallery" class="row g-7">
  </div>
  </div>
  <div class="modal fade" id="shotModal" tabindex="-1" aria-labelledby="shotModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-lg">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="shotModalLabel">Shot Title</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <img id="modal-shot-img" src="" alt="Shot" class="img-fluid">
          <p id="modal-shot-desc" class="mt-3"></p>
        </div>
      </div>
    </div>
  </div>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.s0/dist/js/bootstrap.bundle.min.j"></script>
  <img src="img1.png" class="img-fluid rounded" > 
  <img src="img2.png"  class="img-fluid rounded"> 
  <img src="img3 (2).png"  class="img-fluid rounded" height="350px"width="350px">
  <img src="img4.png"  class="img-fluid rounded">
  <img src="img5.png"  class="img-fluid rounded"> 
  <img src="img6.png"  class="img-fluid rounded"> 
  <img src="img7.png"  class="img-fluid rounded"> 
  <img src="img8.png"  class="img-fluid rounded">
  <img src="img9.png"  class="img-fluid rounded">
  <img src="img10.png"  class="img-fluid rounded">
 <img src="img11.png" class="img-fluid rounded"> 
 <img src="img12.png"  class="img-fluid rounded"> 
 <img src="img13.png"  class="img-fluid rounded"> 
 <img src="img14.png"  class="img-fluid rounded"> 
 <img src="img15.png"  class="img-fluid rounded">
    <footer class="bg-light text-center py-3 mt-4">
    <p>&copy; Dribbble Website | Designed by KEERTHANA D</p>
  </footer>
</body>
</html>

profile.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Profile - Dribbble Website</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" />
  
</head>
<body>
  
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Dribbble Website</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link active" href="index.html">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="sign up.html">Upload</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="profile.html">Profile</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  
  <div class="container my-5">
    <div class="row">
      <div class="col-md-4">
        <img src="img.png" class="img-fluid rounded-circle" alt="Profile Picture">
        <h3 align="center">Dan Cederholm</h3>
      </div>
      <div class="col-md-8">
        <div class="row">
          <div class="col-md-6">
            <div class="card">
              <img src="img18.png" class="card-img-top" alt="Shot 2">
              <h4 align="center">My Logo</h4>
            </div>
          </div>
        
        </div>
      </div>
    </div>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

shots.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Upload Shot - Dribbble Website</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" />
  
</head>
<body>
 
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Dribbble Website</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="index.html">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="sign up.html">Upload</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="profile.html">Profile</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

 
  <div class="container my-4">
    <h3>Upload Your Shot</h3>
    <form id="uploadForm">
      <div class="mb-3">
        <label for="shotTitle" class="form-label">Title</label>
        <input type="text" class="form-control" id="shotTitle" required>
      </div>
      <div class="mb-3">
        <label for="shotDescription" class="form-label">Description</label>
        <textarea class="form-control" id="shotDescription" rows="3" required></textarea>
      </div>
      <div class="mb-3">
        <label for="shotImage" class="form-label">Upload Image</label>
        <input class="form-control" type="file" id="shotImage" required>
      </div>
      <button type="submit" class="btn btn-primary">Upload</button>
    </form>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
  <script src="scripts/main.js"></script>
</body>
</html>

sign up.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Find Jobs - Dribbble Website</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" />
  
</head>
<body>
  
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="index.html">Dribbble Website</a>
    </div>
  </nav>

  
  <div class="container my-4">
    <h1 class="text-center">Find Jobs</h1>
    <div class="card my-3">
      <div class="card-body">
        <h5 class="card-title">UI/UX Designer</h5>
        <p class="card-text">Location: Remote | Full-time</p>
        <a href="#" class="btn btn-primary">Apply Now</a>
      </div>
    </div>
    <div class="card my-3">
      <div class="card-body">
        <h5 class="card-title">Graphic Designer</h5>
        <p class="card-text">Location: New York | Part-time</p>
        <a href="#" class="btn btn-primary">Apply Now</a>
      </div>
    </div>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
## OUTPUT:

![alt text](<Screenshot (118).png>)
![alt text](<Screenshot (119).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
