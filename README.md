# Portfolio
Personal Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VENNAPU YASWANTH</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }

        header {
            background: #333;
            color: white;
            padding: 1em 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 16px;
        }

        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 2em 0;
        }

        section {
            background: white;
            padding: 2em;
            margin-bottom: 1em;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .section-title {
            border-bottom: 2px solid #333;
            padding-bottom: 0.5em;
            margin-bottom: 1em;
            font-size: 24px;
        }

        .project, .education-item {
            margin-bottom: 1em;
        }

        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border-radius: 4px;
            border: 1px solid #ccc;
        }

        .contact-form button {
            padding: 10px 20px;
            background-color: #333;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>VENNAPU YASWANTH</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <div class="container">
        <section id="home">
            <h2 class="section-title">Welcome</h2>
            <p>Hello! I'm vennapu yaswanthS, a developer with a passion for creating innovative solutions. Explore my work and feel free to get in touch!</p>
        </section>

        <section id="projects">
            <h2 class="section-title">Projects</h2>
            <div class="project">
                <h3>Prediction of App Rating</h3>
                <p>Created a machine learning model to predict app ratings using Python, Pandas, Scikit-learn, and XGBoost. The project involved data preprocessing, model training, and performance evaluation.</p>
            </div>
            <div class="project">
                <h3>AUTOMATIC TICKET GENERATION</h3>
                <p>Developed a web-based application with HTML, CSS, PHP, and MySQL to manage library operations. Features include book tracking, user management, and handling of book issues and returns.</p>
            </div>
        </section>

        

        <section id="contact">
            <h2 class="section-title">Contact Me</h2>
            <form class="contact-form" action="mailto:your-email@example.com" method="POST" enctype="text/plain">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 [Your Name]. All rights reserved.</p>
    </footer>
</body>
</html>
