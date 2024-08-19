<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Card Game Shop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            text-align: center;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
        }
        header h1 {
            margin: 0;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            overflow: auto;
        }
        .card {
            background: #fff;
            border: 1px solid #ccc;
            padding: 20px;
            margin: 10px;
            float: left;
            width: 30%;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
            transition: box-shadow 0.3s;
        }
        .card:hover {
            box-shadow: 2px 2px 20px rgba(0, 0, 0, 0.2);
        }
        .card img {
            max-width: 100%;
        }
        .card h2 {
            margin: 0;
        }
        .card p {
            color: #777;
        }
        .card button {
            background: #333;
            color: #fff;
            padding: 10px;
            border: none;
            cursor: pointer;
            width: 100%;
        }
        .card button:hover {
            background: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Card Game Shop</h1>
    </header>
    <div class="container">
        <div class="card">
            <img src="card1.jpg" alt="Card Game 1">
            <h2>Card Game 1</h2>
            <p>$10.00</p>
            <button>Add to Cart</button>
        </div>
        <div class="card">
            <img src="card2.jpg" alt="Card Game 2">
            <h2>Card Game 2</h2>
            <p>$15.00</p>
            <button>Add to Cart</button>
        </div>
        <div class="card">
            <img src="card3.jpg" alt="Card Game 3">
            <h2>Card Game 3</h2>
            <p>$20.00</p>
            <button>Add to Cart</button>
        </div>
    </div>
</body>
</html>
