<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Vibrant Car World</title>

<!-- Google Font -->
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap" rel="stylesheet">

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: 'Orbitron', sans-serif;
    }

    body {
        background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
        color: white;
        overflow-x: hidden;
    }

    header {
        background: linear-gradient(90deg, #ff512f, #dd2476);
        padding: 20px;
        text-align: center;
        font-size: 2rem;
        letter-spacing: 3px;
        text-transform: uppercase;
        box-shadow: 0 0 20px #ff00ff;
    }

    nav {
        display: flex;
        justify-content: center;
        background: #111;
        padding: 10px;
    }

    nav a {
        color: #00f7ff;
        margin: 0 15px;
        text-decoration: none;
        font-weight: bold;
        transition: 0.3s;
    }

    nav a:hover {
        color: #ff00ff;
        text-shadow: 0 0 10px #ff00ff;
    }

    .hero {
        height: 90vh;
        background: url('https://images.unsplash.com/photo-1502877338535-766e1452684a') no-repeat center center/cover;
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
    }

    .hero h1 {
        font-size: 4rem;
        background: linear-gradient(90deg, #00f7ff, #ff00ff);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        text-shadow: 0 0 20px #ff00ff;
    }

    .cars {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        padding: 50px 20px;
        gap: 30px;
    }

    .card {
        background: linear-gradient(145deg, #1f1c2c, #928dab);
        width: 300px;
        border-radius: 15px;
        overflow: hidden;
        box-shadow: 0 0 20px #00f7ff;
        transition: transform 0.4s, box-shadow 0.4s;
    }

    .card:hover {
        transform: scale(1.05);
        box-shadow: 0 0 30px #ff00ff;
    }

    .card img {
        width: 100%;
        height: 200px;
        object-fit: cover;
    }

    .card-content {
        padding: 20px;
        text-align: center;
    }

    .card-content h3 {
        margin-bottom: 10px;
        color: #00f7ff;
    }

    .btn {
        display: inline-block;
        margin-top: 15px;
        padding: 10px 20px;
        background: linear-gradient(90deg, #ff512f, #dd2476);
        border: none;
        border-radius: 25px;
        color: white;
        cursor: pointer;
        transition: 0.3s;
    }

    .btn:hover {
        box-shadow: 0 0 15px #ff00ff;
        transform: scale(1.1);
    }

    footer {
        text-align: center;
        padding: 20px;
        background: #111;
        margin-top: 40px;
        color: #888;
    }

</style>
</head>

<body>

<header>
    🚗 Vibrant Car World 🚗
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Supercars</a>
    <a href="#">Sports Cars</a>
    <a href="#">Contact</a>
</nav>

<section class="hero">
    <h1>Feel The Speed</h1>
</section>

<section class="cars">

    <div class="card">
        <img src="https://images.unsplash.com/photo-1549924231-f129b911e442" alt="Car 1">
        <div class="card-content">
            <h3>Supercar X</h3>
            <p>Experience unmatched speed and power with cutting-edge design.</p>
            <button class="btn">Explore</button>
        </div>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70" alt="Car 2">
        <div class="card-content">
            <h3>Turbo GT</h3>
            <p>Built for adrenaline lovers who crave performance and style.</p>
            <button class="btn">Explore</button>
        </div>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/
