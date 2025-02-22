<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional Video Editor - Aashish</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
    <style>
        body {
            background-color: #131313;
            color: white;
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
        }
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            padding: 20px;
            background-color: #000;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        #home {
            text-align: center;
            padding: 50px 20px;
        }
        .hero-content h1 {
            font-size: 3rem;
            font-weight: bold;
            color: #fff;
        }
        .hero-content p {
            font-size: 1.2rem;
            color: #aaa;
        }
        button {
            background-color: #8A2BE2;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            font-size: 1rem;
            margin-top: 10px;
        }
        .video-gallery {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }
        .video-item img {
            width: 200px;
            border-radius: 10px;
        }
        .testimonial {
            background-color: #8A2BE2;
            padding: 20px;
            margin: 20px;
            border-radius: 10px;
            text-align: center;
            font-weight: bold;
        }
        form {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 10px;
        }
        input, textarea {
            width: 80%;
            padding: 10px;
            border: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#testimonials">Testimonials</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <div class="hero-content">
            <h1>PROFESSIONAL VIDEO EDITOR</h1>
            <p>Making Your Videos Look More Cool.</p>
            <button>Let's Talk</button>
        </div>
        <img src="your-image.png" alt="Aashish" class="hero-image">
    </section>

    <section id="about">
        <h2>ABOUT ME</h2>
        <p>Welcome to the cinematic realm of Aashish, where creativity meets precision...</p>
    </section>

    <section id="portfolio">
        <h2>MY BEST EDITS</h2>
        <div class="video-gallery">
            <div class="video-item">
                <img src="cashcow-thumbnail.jpg" alt="Cash Cow">
                <p>Cash Cow</p>
            </div>
            <div class="video-item">
                <img src="reel-thumbnail.jpg" alt="Reel">
                <p>Reel</p>
            </div>
            <div class="video-item">
                <img src="vlog-thumbnail.jpg" alt="Vlog">
                <p>Vlog</p>
            </div>
        </div>
    </section>

    <section id="testimonials">
        <h2>TESTIMONIALS</h2>
        <div class="testimonial">
            <p>"Perfect Communication and Exceptional Skills. This guy is king!" - Marcus</p>
        </div>
        <div class="testimonial">
            <p>"Did a great job. Understood all the requirements." - Peter</p>
        </div>
        <div class="testimonial">
            <p>"Jimmy was wonderful to work with. Will definitely hire him again!" - Jane</p>
        </div>
    </section>

    <section id="contact">
        <h2>CONTACT ME</h2>
        <form>
            <input type="text" placeholder="Your Name">
            <input type="email" placeholder="Your Email">
            <textarea placeholder="Message"></textarea>
            <button type="submit">Send</button>
        </form>
    </section>
</body>
</html>
