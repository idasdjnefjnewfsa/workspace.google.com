<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Game Hub</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #121212;
            color: #fff;
        }

        header {
            background: #1e1e1e;
            padding: 20px;
            text-align: center;
        }

        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }

        .container {
            padding: 20px;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .game-card {
            background: #2a2a2a;
            border-radius: 10px;
            padding: 15px;
            width: 250px;
            text-align: center;
        }

        .game-card img {
            width: 100%;
            border-radius: 10px;
        }

        .game-card h3 {
            margin: 10px 0;
        }

        footer {
            background: #1e1e1e;
            text-align: center;
            padding: 15px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        button {
            background: #007bff;
            color: #fff;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background: #0056b3;
        }
    </style>
</head>
<body>

<header>
    <h1>My Game Hub</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#">Games</a>
        <a href="#">Contact</a>
    </nav>
</header>

<div class="container">
    <div class="game-card">
        <img src="https://via.placeholder.com/250x140" alt="Game Image">
        <h3>Game Title 1</h3>
        <p>Short description of the game.</p>
        <button onclick="alert('Launching Game 1...')">Play</button>
    </div>

    <div class="game-card">
        <img src="https://via.placeholder.com/250x140" alt="Game Image">
        <h3>Game Title 2</h3>
        <p>Short description of the game.</p>
        <button onclick="alert('Launching Game 2...')">Play</button>
    </div>

    <!-- Add more game cards as needed -->
</div>

<footer>
    <p>&copy; 2025 My Game Hub. All rights reserved.</p>
</footer>

</body>
</html>
