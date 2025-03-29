# my-website
Short description of me!
<!DOCTYPE html>
<html lang="en">
<head>
    <head>
        <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    </head> 
    <meta name="description" content="Your description here">
<meta name="keywords" content="your, keywords, here">
   
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>BYESIGWA - Portfolio</title>
    <style>
        .loader {
    border: 16px solid #f3f3f3;
    border-top: 16px solid #3498db;
    border-radius: 50%;
    width: 60px;
    height: 60px;
    animation: spin 2s linear infinite;
}

@keyframes spin {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
}
        body {
    background-image: url('your-image.jpg');
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
}
body.dark-mode {
    background-color: #121212;
    color: white;
}
<button onclick="toggleDarkMode()">Toggle Dark Mode</button>
<script>
    function toggleDarkMode() {
        document.body.classList.toggle("dark-mode");
    }
</script>
        .content {
    animation: fadeIn 1.5s ease-in;
}

@keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}
.button:hover {
    background-color: #f39c12;
    transform: scale(1.1);
    transition: all 0.3s ease;
}
@media (max-width: 600px) {
    .content {
        padding: 20px;
    }

    .header h1 {
        font-size: 24px;
    }
}
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #f3f4f6, #e2e8f0);
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #4A90E2;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            font-size: 40px;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 15px 20px;
            transition: background-color 0.3s ease;
        }

        nav a:hover {
            background-color: #555;
        }

        section {
            padding: 40px 20px;
            text-align: center;
        }

        h2 {
            font-size: 30px;
            color: #4A90E2;
        }

        .skills, .projects {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            padding: 20px;
        }

        .skill, .project {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        .skill:hover, .project:hover {
            transform: translateY(-10px);
        }

        footer {
            background-color: #333;
            color: white;
            padding: 15px 0;
            text-align: center;
            font-size: 14px;
        }

        footer a {
            color: #4A90E2;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <header>
        <h1>FIDON</h1>
        <p>Welcome to My Professional Portfolio</p>
    </header>

    <nav>
        <a href="#about">About Me</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I'm a passionate developer, continuously learning and building cool things. With a solid foundation in multiple technical areas, I strive to create impactful projects.</p>
    </section>

    <section id="skills" class="skills">
        <h2>Skills & Expertise</h2>
        <div class="skill">
            <h3>Machine Learning</h3>
            <p>Skilled in ML frameworks like TensorFlow, Scikit-learn, and Keras.</p>
        </div>
        <div class="skill">
            <h3>Web Development</h3>
            <p>Proficient in HTML, CSS, JavaScript, and modern frameworks like React and Node.js.</p>
        </div>
        <div class="skill">
            <h3>AI & Automation</h3>
            <p>Experience in building AI-based automation systems and applications.</p>
        </div>
    </section>

    <section id="projects" class="projects">
        <h2>My Projects</h2>
        <div class="project">
            <h3>Betting Prediction AI</h3>
            <p>Developed a prediction model for betting using machine learning algorithms.</p>
        </div>
        <div class="project">
            <h3>Personal Finance Calculator</h3>
            <p>Created a tool to help users manage their finances effectively.</p>
        </div>
        <div class="project">
            <h3>Whatsapp Bot</h3>
            <p>Built a WhatsApp bot to automate various tasks and notifications.</p>
        </div>
    </section>

    <footer>
        <form action="mailto:youremail@example.com" method="post" enctype="text/plain">
            <label for="name">Your Name:</label><br>
            <input type="text" id="name" name="name"><br>
            <label for="email">Your Email:</label><br>
            <input type="email" id="email" name="email"><br>
            <label for="message">Message:</label><br>
            <textarea id="message" name="message"></textarea><br>
            <input type="submit" value="Send">
        </form>
        
        <p>Contact me via <a href="mailto:your.email@example.com">ifyouprocrastinatenowayout@gmail.com</a>.</p>
        <p>&copy; 2025 Byesigwa</p>
    </footer>

</body>
</html>
