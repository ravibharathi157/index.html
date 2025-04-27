<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <img src="myphoto.jpg" alt="Ravi's Photo" class="profile-photo">    <style>
        .profile-photo {
            width: 150px; /* Adjust size */
            height: 150px;
            border-radius: 50%; /* Makes it circular */
            margin-top: 20px;
        }
    </style>
    <title>Ravi's Professional Profile</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            margin: 0;
            padding: 0;
            background: #F1F1F1; /* Light Gray Background */
            color: #333; /* Dark text color for contrast */
        }
        nav {
            background: #D50032; /* CISD Red for Navigation */
            padding: 1em;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        header {
            background: #D50032; /* CISD Red for Header */
            color: white;
            text-align: center;
            padding: 80px 20px;
        }
        header h1 {
            margin: 0;
            font-size: 3em;
        }
        .section {
            padding: 60px 20px;
            max-width: 900px;
            margin: auto;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        .gallery img {
            width: 100%;
            max-width: 400px;
            height: auto;
            border-radius: 10px;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        input, textarea {
            margin-bottom: 15px;
            padding: 10px;
            font-size: 16px;
            border: 1px solid #ccc; /* Gray border for inputs */
        }
        button {
            background: #D50032; /* CISD Red for Buttons */
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
        }
        button:hover {
            background: #9C0017; /* Darker Red on Hover */
        }
    </style>
</head>
<body>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Me</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </nav>

    <header id="home">
        <h1>Welcome to Ravi's Professional Profile</h1>
        <p>Discover more about me, my work, and how to connect!</p>
    </header>

    <section class="section" id="about">
        <h2>About Me</h2>
        <p>Hello! I’m Ravi, a highly motivated and passionate professional with a deep commitment to creating meaningful impact through innovative projects. Throughout my journey, I’ve honed a unique blend of technical expertise and creative problem-solving skills, enabling me to bring ambitious ideas to life. My passion for technology fuels my drive to explore new possibilities, and my creativity allows me to develop solutions that bridge the gap between the abstract and the real world. I am constantly looking for opportunities to learn, grow, and contribute, with the ultimate goal of turning concepts into actionable, transformative solutions that leave a lasting impression.</p>
    </section>

    <section class="section" id="projects">
        <h2>My Projects</h2>
        <p>Here are some of the projects I've worked on:</p>
        
        <!-- First Project: Dragster Design -->
        <div class="project">
            <img src="DRAGSTER DESIGN.jpg" alt="Dragster Design" class="project-image">
            <p>Dragster Design - A dragster model for a competition.</p>
        </div>
        
        <!-- Second Project: Spark AI -->
        <div class="project">
            <img src="Spark AI.jpg" alt="Spark AI" class="project-image">
            <p>Spark AI - An AI project using Spark technology to analyze large datasets.</p>
        </div>
        
        <!-- Third Project: RC Car -->
        <div class="project">
            <img src="rc_car.jpg" alt="RC Car" class="project-image">
            <p>RC Car - A remote-controlled car built using Arduino and sensors for autonomous driving.</p>
        </div>
    </section>
    <section class="section" id="contact">
        <h2>Contact Me</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>
</body>
</html>
