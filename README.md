<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Jeu</title>
    <style>
        body {
            margin: 0;
            width: 100vw;
            height: 100vh;
            background-color: #D8BFD8;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: "Comic Sans MS", cursive;
        }

        button {
            font-size: 24px;
            padding: 20px 40px;
            border: none;
            border-radius: 12px;
            background-color: #8b5cf6;
            color: white;
            cursor: pointer;
        }

        button:hover {
            background-color: #7c3aed;
        }
    </style>
</head>
<body>

    <button onclick="startGame()">Commencer le jeu</button>

    <script>
        function startGame() {
            // Ouvre ton jeu (HTML)
            window.location.href = "snake.html";
        }
    </script>

</body>
</html>
