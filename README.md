<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Senior Capstone</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 20px;
            border-radius: 5px 5px 0 0;
        }
        nav {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        nav ul li a {
            text-decoration: none;
            color: #fff;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            border-radius: 0 0 5px 5px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Welcome to Capstone Website</h1>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="container">
        <section>
            <h2>About the Project</h2>
            <p>This is a simple website created using HTML with HTTPS enabled.</p>
            <p>You can replace this content with your own.</p>
        </section>

        <section>
            <h2>Our Services</h2>
            <p>We offer a variety of services to meet your needs.</p>
            <ul>
                <li>Service 1</li>
                <li>Service 2</li>
                <li>Service 3</li>
            </ul>
        </section>

        <section>
            <h2>Contact Us</h2>
            <form action="#" method="post">
                <label for="name">Alexander Khong:</label><br>
                <input type="text" id="name" name="name"><br>
                <label for="email">aokhong@dons.usfca.edu:</label><br>
                <input type="email" id="email" name="email"><br>
                <label for="message">Hello There:</label><br>
                <textarea id="message" name="message" rows="4"></textarea><br>
                <input type="submit" value="Submit">
            </form>
        </section>
        
        <section>
            <h2>Our Location</h2>
            <img src="https://via.placeholder.com/400" alt="Location Map">
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Basic HTTPS Website. All rights reserved.</p>
    </footer>
</body>
</html>
