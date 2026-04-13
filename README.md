<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anime News</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        nav {
            background-color: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 15px;
            text-decoration: none;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }
        .card {
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 15px;
            padding: 10px;
            width: 300px;
            box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.1);
        }
        .card img {
            max-width: 100%;
            border-radius: 5px;
        }
        @media (max-width: 600px) {
            .card {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <nav>
        <a href="#home">Home</a>
        <a href="#news">News</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <div class="card">
            <img src="anime1.jpg" alt="Anime News 1">
            <h2>Anime Title 1</h2>
            <p>Latest updates about Anime Title 1.</p>
        </div>
        <div class="card">
            <img src="anime2.jpg" alt="Anime News 2">
            <h2>Anime Title 2</h2>
            <p>Latest updates about Anime Title 2.</p>
        </div>
        <div class="card">
            <img src="anime3.jpg" alt="Anime News 3">
            <h2>Anime Title 3</h2>
            <p>Latest updates about Anime Title 3.</p>
        </div>
    </div>
</body>
</html>
