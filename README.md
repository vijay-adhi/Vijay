<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
            background: #f4f4f4;
        }

        header {
            background: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background: #444;
        }

        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
        }

        nav a:hover {
            background: #555;
        }

        section {
            padding: 40px;
            max-width: 1000px;
            margin: auto;
        }

        .home {
            text-align: center;
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .project-card {
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: #fff;
        }

        button {
            padding: 10px 20px;
            background: #333;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }

        button:hover {
            background: #555;
        }
    </style>
</head>
<body>

<header>
    <h1>Vijay</h1>
    <p>Web Developer | ML Enthusiast | IoT Learner</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
</nav>

<section id="home" class="home">
    <h2>Welcome 👋</h2>
    <p>I build web apps, machine learning models, and IoT solutions.</p>
</section>

<section id="about">
    <h2>About Me</h2>
    <p>
        I am a passionate developer interested in Machine Learning, IoT, and Web Development.
        I love building real-world applications like medical imaging systems and customer segmentation tools.
    </p>
</section>

<section id="projects">
    <h2>Projects</h2>

    <div class="projects">
        <div class="project-card">
            <h3>Medical Imaging QA</h3>
            <p>Deep learning system to detect pneumonia from X-rays.</p>
        </div>

        <div class="project-card">
            <h3>Customer Segmentation</h3>
            <p>ML model using clustering for customer analysis.</p>
        </div>

        <div class="project-card">
            <h3>IoT Smart System</h3>
            <p>Connected devices using MQTT and sensors.</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Contact Me</h2>
    <p>Email: vijayhsn123456@gmail.com</p>
    <br>
    <button onclick="alert('Thanks for visiting!')">Say Hello</button>
</section>

<footer>
    <p>© Vijay</p>
</footer>

</body>
</html>
