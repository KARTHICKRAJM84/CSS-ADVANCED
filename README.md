# CSS-ADVANCED
## home.html
```


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribble Clone</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #24292e;
            padding: 10px 20px;
            color: #fff;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header h1 {
            font-size: 24px;
            margin: 0;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-left: 20px;
        }
        .hero {
            background-image: url('BG.jpg');
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: #fff;
        }
        .hero h2 {
            font-size: 36px;
            margin: 0;
            padding: 10px;
        }
        .hero p {
            font-size: 18px;
            margin: 0;
            padding: 10px;
        }
        .button {
            display: inline-block;
            background-color: #3a02e0;
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            border-radius: 5px;
            margin-top: 20px;
            transition: background-color 0.3s ease;
        }
        .button:hover {
            background-color: #f7f9fa;
        }
        .featured-designs {
            padding: 20px;
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
        }
        .featured-design {
            background-color: #f0f0f0;
            padding: 10px;
            border-radius: 5px;
        }
        .featured-design img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Dribble Clone</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="explore.html">Explore</a></li>
                <li><a href="signup.html">Sign Up</a></li>
                <li><a href="login.html">Log In</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero">
        <h2>Discover the world's top designers & creatives.</h2>
        <p>Dribble is the leading destination to find & showcase creative work and home to the world's best design professionals.</p>
        <a href="#" class="button">Explore Designs</a>
    </section>
    <section class="featured-designs">
        <div class="featured-design">
            <img src="burger.jpg" alt="BURGER Design 1">
            <h3>BURGER</h3>
            <p>by Mary Maka</p>
        </div>
        <div class="featured-design">
            <img src="ghost.png" alt="GHOST Design 2">
            <h3>Art Station</h3>
            <p>by Manuel Cetina</p>
        </div>
        <div class="featured-design">
            <img src="pigeon.jpg" alt="PIGEON Design 2">
            <h3>PIGEON  Design</h3>
            <p>by Lisa McCormick</p>
        </div>
        <div class="featured-design">
            <img src="sport.jpg" alt="SHORT Design 2">
            <h3>SHORT Design</h3>
            <p>by Jetpacks and Rollerskates</p>
        </div>
        <div class="featured-design">
            <img src="lunch.jpg" alt="LUNCH Design 2">
            <h3>LUNCH  Design</h3>
            <p>by Lisa McCormick</p>
        </div>
        <div class="featured-design">
            <img src="Samurai.jpg" alt="SAMURAI Design 2">
            <h3>SAMURAI Design</h3>
            <p>by Lisa McCormick</p>
        </div>
        <!-- Repeat for more featured designs -->
    </section>
    <footer>
        <p>&copy; 2024 Dribble Clone. All rights reserved.</p>
        <nav>
            <ul>
                <li><a href="#">About</a></li>
                <li><a href="#">Careers</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </footer>
</body>
</html>
```
## output
![image](https://github.com/user-attachments/assets/ea79b594-9ba5-4b1a-927a-436ea8da4762)

