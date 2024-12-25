<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>My GitHub Pages Website</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&display=swap" rel="stylesheet">
</head>

<body>

    <header>
        <div class="container">
            <div class="logo">
                <h1><a href="#">MySite</a></h1>
            </div>
            <nav class="navbar">
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="section home">
        <div class="container">
            <h2>Welcome to My Website</h2>
            <p>This is a simple, responsive GitHub Pages template.</p>
        </div>
    </section>

    <section id="about" class="section about">
        <div class="container">
            <h2>About Us</h2>
            <p>This is the About section. You can talk about yourself or your project here.</p>
        </div>
    </section>

    <section id="services" class="section services">
        <div class="container">
            <h2>Our Services</h2>
            <p>Describe the services you offer or the features of your project here.</p>
        </div>
    </section>

    <section id="contact" class="section contact">
        <div class="container">
            <h2>Contact Us</h2>
            <p>Here you can add your contact details or a contact form.</p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 My GitHub Pages Website. All Rights Reserved.</p>
        </div>
    </footer>

    <!-- Optional: Add JavaScript for mobile menu toggle -->
    <script>
        const menu = document.querySelector('.navbar');
        const menuButton = document.querySelector('.menu-toggle');

        menuButton.addEventListener('click', () => {
            menu.classList.toggle('active');
        });
    </script>

</body>

</html>
