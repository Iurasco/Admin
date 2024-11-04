<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <title>Formular Utilizator</title>
</head>
<body>
    <form method="post" action="">
        Nume: <input type="text" name="nume" required><br>
        Vârstă: <input type="number" name="varsta" required><br>
        <input type="submit" value="Trimite">
    </form>

    <?php
    if ($_SERVER["REQUEST_METHOD"] == "POST") {
        $nume = htmlspecialchars($_POST['nume']);
        $varsta = htmlspecialchars($_POST['varsta']);
        echo "Salut, $nume! Ai $varsta ani.";
    }
    ?>
</body>
</html>
