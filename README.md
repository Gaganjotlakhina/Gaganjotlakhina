<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gaganjot's World</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(45deg, #f5f7fa, #c8e0f4);
            color: #333;
        }
        header {
            text-align: center;
            padding: 50px;
            background: linear-gradient(135deg, #0078d7, #00a4ff);
            color: white;
        }
        h1 {
            margin: 0;
            font-size: 3em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        section {
            padding: 20px;
            max-width: 800px;
            margin: auto;
            background: white;
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
        }
        section img {
            width: 100%;
            max-height: 500px;
            object-fit: cover;
            border-radius: 10px;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        ul li {
            background: #f0f0f0;
            margin: 10px 0;
            padding: 10px;
            border-radius: 5px;
            transition: background 0.3s ease;
        }
        ul li:hover {
            background: #dceeff;
        }
        .fun-section button {
            padding: 10px 20px;
            background: #0078d7;
            color: white;
            border: none;
            cursor: pointer;
            margin-top: 10px;
            border-radius: 5px;
            font-size: 16px;
            transition: background 0.3s ease;
        }
        .fun-section button:hover {
            background: #005bb5;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #0078d7;
            color: white;
        }
        footer a {
            color: #fff;
            text-decoration: underline;
        }
        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
            font-size: 16px;
        }
        form input[type="submit"] {
            background: #0078d7;
            color: white;
            cursor: pointer;
            border: none;
            font-size: 16px;
        }
        form input[type="submit"]:hover {
            background: #005bb5;
        }
    </style>
</head>
<body>

<header>
    <h1>Gaganjot's World</h1>
    <p>A little corner of the web, just for you.</p>
</header>

<section>
    <h2>A Little About Me</h2>
    <p>Born and raised in the vibrant streets of Sri Ganganagar, I took a leap of faith and landed in Canada. I juggle between tech and finance, but my favorite balance is between good company and a great conversation.</p>
    <!-- Replace the image URL below with the direct link to your photo -->
    <img src="YOUR_IMAGE_URL_1" alt="Gaganjot's Image">
</section>

<section>
    <h2>What Makes Me Tick</h2>
    <ul>
        <li>Travel: Always down for exploring new places, whether it’s the streets of Toronto or somewhere more remote.</li>
        <li>Music: Music is the soul of life. I’ve got a playlist for every vibe—let me know what you’re into!</li>
        <li>Fitness: Staying active keeps me balanced. Whether it's at the gym or a morning run, health is key.</li>
        <li>Tech Enthusiast: I love keeping up with the fast-paced world of innovation.</li>
    </ul>
    <!-- Replace the image URL below with the direct link to your photo -->
    <img src="YOUR_IMAGE_URL_2" alt="Gaganjot's World Image">
</section>

<section class="fun-section">
    <h2>Two Truths and a Lie</h2>
    <p>Let's make this a little more interactive. Can you spot the lie?</p>
    <ul>
        <li>I’ve been skydiving, and I would do it again tomorrow.</li>
        <li>I can cook a full-course meal, but you’d have to guess which dish is my specialty.</li>
        <li>I’m secretly a pro at dancing but only under the right circumstances.</li>
    </ul>
    <button onclick="revealLie()">Reveal the Lie</button>
    <p id="reveal-text" style="display:none;">The lie is... I've never gone skydiving! But it's on my bucket list.</p>
</section>

<section>
    <h2>Curious About You</h2>
    <p>What are your passions, favorite places to explore, or the craziest thing you've ever done?</p>
    <form>
        <label for="name">Your Name:</label><br>
        <input type="text" id="name" name="name" required><br>
        <label for="message">Your Message:</label><br>
        <textarea id="message" name="message" rows="5" required></textarea><br>
        <input type="submit" value="Send Message">
    </form>
</section>

<footer>
    <p>Whether this page was a hit or miss, I’m glad you stopped by! Catch me on <a href="#">Instagram</a> or drop me a message above.</p>
</footer>

<script>
    function revealLie() {
        document.getElementById('reveal-text').style.display = 'block';
    }
</script>

</body>
</html>
