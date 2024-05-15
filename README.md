<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>One-Page Website</title>
    <style>
        /* Add your CSS styles here */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header, footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }
        section {
            padding: 50px 0;
            text-align: center;
        }
        img {
            max-width: 100%;
            height: auto;
        }
        iframe {
            width: 100%;
            height: 400px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Our One-Page Website</h1>
    </header>
    
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#pictures">Pictures</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a href="#video">Video</a></li>
        </ul>
    </nav>
    
    <section id="home">
        <h2>Home</h2>
        <p>This is the home section of our website. Welcome!</p>
    </section>
    
    <section id="pictures">
        <h2>Pictures</h2>
        <img src="picture1.jpg" alt="Picture 1">
        <img src="picture2.jpg" alt="Picture 2">
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <form action="submit_form.php" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br><br>
            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" required></textarea><br><br>
            <input type="submit" value="Submit">
        </form>
    </section>
    
    <section id="video">
        <h2>Watch Our Video</h2>
        <iframe src="https://www.youtube.com/embed/yourvideoid" frameborder="0" allowfullscreen></iframe>
    </section>
    
    <footer>
        <p>&copy; 2024 One-Page Website. All rights reserved.</p>
    </footer>
</body>
</html>
