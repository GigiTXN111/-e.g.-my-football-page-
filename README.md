# -e.g.-my-football-page-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Football Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #fff;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #b30000;
            padding: 10px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            color: #fff;
        }
        nav {
            margin: 15px;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        section {
            padding: 20px;
        }
        .bio, .gallery, .contact-form, .news, .videos {
            margin-bottom: 40px;
        }
        .gallery img, .videos iframe {
            width: 100%;
            max-width: 300px;
            margin: 10px;
            border: 3px solid #b30000;
        }
        .social-media a {
            color: #fff;
            margin: 0 10px;
            text-decoration: none;
            font-size: 20px;
        }
        footer {
            background-color: #111;
            text-align: center;
            padding: 20px;
            color: #fff;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #b30000;
            border-radius: 5px;
            background-color: #111;
            color: #fff;
        }
        button {
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            background-color: #b30000;
            color: #fff;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Football Webpage</h1>
        <nav>
            <a href="#bio">About Me</a>
            <a href="#news">Football News</a>
            <a href="#gallery">Photo Gallery</a>
            <a href="#videos">Videos</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="bio" class="bio">
        <h2>About Me</h2>
        <p>Welcome to my personal football page! I'm a passionate football fan, always staying up-to-date with the latest news, watching matches, and analyzing plays. This site is where I share my love for the game.</p>
    </section>

    <section id="news" class="news">
        <h2>Latest Football News</h2>
        <p>Stay tuned for the latest football news and updates!</p>
        <!-- Embed a football news feed or link to your favorite news sources -->
    </section>

    <section id="gallery" class="gallery">
        <h2>Photo Gallery</h2>
        <img src="https://via.placeholder.com/300x200?text=Football+Image+1" alt="Football Image 1">
        <img src="https://via.placeholder.com/300x200?text=Football+Image+2" alt="Football Image 2">
        <img src="https://via.placeholder.com/300x200?text=Football+Image+3" alt="Football Image 3">
    </section>

    <section id="videos" class="videos">
        <h2>Football Videos</h2>
        <iframe width="300" height="200" src="https://www.youtube.com/embed/your_video_id" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
        <iframe width="300" height="200" src="https://www.youtube.com/embed/your_video_id" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
    </section>

    <section id="contact" class="contact-form">
        <h2>Contact Me</h2>
        <form action="#" method="post">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <section class="social-media">
        <h2>Follow Me</h2>
        <a href="https://twitter.com/yourprofile" target="_blank">Twitter</a>
        <a href="https://instagram.com/yourprofile" target="_blank">Instagram</a>
        <a href="https://facebook.com/yourprofile" target="_blank">Facebook</a>
    </section>

    <footer>
        <p>&copy; 2024 Your Name. All Rights Reserved.</p>
    </footer>
</body>
</html>
