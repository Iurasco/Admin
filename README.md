<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cafeneaua Noastră</title>
    <!-- Include Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">Cafeneaua Noastră</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Acasă</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Despre Noi</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Produse</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Contact</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Jumbotron -->
    <div class="jumbotron text-center">
        <h1 class="display-4">Bine ați venit la Cafeneaua Noastră!</h1>
        <p class="lead">Cea mai bună cafea din oraș, preparată cu dragoste.</p>
        <a class="btn btn-primary btn-lg" href="#" role="button">Aflați mai multe</a>
    </div>

    <!-- Secțiune Produse -->
    <div class="container">
        <h2 class="text-center">Produsele Noastre</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card mb-4 shadow-sm">
                    <img src="https://via.placeholder.com/150" class="card-img-top" alt="Cafea Espresso">
                    <div class="card-body">
                        <h5 class="card-title">Cafea Espresso</h5>
                        <p class="card-text">Cafeaua noastră espresso este intensă și aromată.</p>
                        <a href="#" class="btn btn-primary">Vezi mai mult</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card mb-4 shadow-sm">
                    <img src="https://via.placeholder.com/150" class="card-img-top" alt="Cafea Latte">
                    <div class="card-body">
                        <h5 class="card-title">Cafea Latte</h5>
                        <p class="card-text">Un amestec perfect de cafea și lapte cremos.</p>
                        <a href="#" class="btn btn-primary">Vezi mai mult</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card mb-4 shadow-sm">
                    <img src="https://via.placeholder.com/150" class="card-img-top" alt="Cafea Mocha">
                    <div class="card-body">
                        <h5 class="card-title">Cafea Mocha</h5>
                        <p class="card-text">Cafea cu ciocolată, o delicatesă pentru iubitorii de dulciuri.</p>
                        <a href="#" class="btn btn-primary">Vezi mai mult</a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-light text-center py-4">
        <p>&copy; 2024 Cafeneaua Noastră. Toate drepturile rezervate.</p>
    </footer>

    <!-- Include jQuery and Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.0.7/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
