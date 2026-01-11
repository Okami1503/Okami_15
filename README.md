<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jeu de Snake</title>
<style>
    body {
        background-color: #D8BFD8;
        font-family: "Comic Sans MS", sans-serif;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        height: 100vh;
        margin: 0;
    }

    h1 {
        font-size: 60px;
        margin-bottom: 50px;
    }

    .button {
        padding: 20px 40px;
        font-size: 20px;
        cursor: pointer;
        border: none;
        border-radius: 10px;
        background-color: #32CD32;
        color: white;
        transition: transform 0.2s;
    }

    .button:hover {
        transform: scale(1.1);
    }
</style>
</head>
<body>

<h1>Jeu de Snake</h1>

<button class="button" onclick="openSnake()">Commencer le jeu</button>

<script>
    function openSnake() {
        // Ouvre le jeu dans un nouvel onglet
        window.open("https://www.google.com", "_blank");
    }
</script>

</body>
</html>
