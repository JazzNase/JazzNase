<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jazz Michael G. Nase - Profile</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f4f8;
            color: #333;
            margin: 0;
            padding: 20px;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h1, h2 {
            color: #2c3e50;
            text-align: center;
        }

        header {
            text-align: center;
            margin-bottom: 40px;
        }

        header p {
            font-size: 1.1em;
            line-height: 1.6;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        ul li {
            background: #2ecc71;
            color: #fff;
            margin: 5px 0;
            padding: 10px;
            border-radius: 4px;
        }

        a {
            color: #3498db;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        .project-item {
            background-color: #ecf0f1;
            padding: 15px;
            margin-bottom: 20px;
            border-left: 5px solid #3498db;
        }

        .fun-fact {
            background-color: #f39c12;
            color: white;
            padding: 15px;
            text-align: center;
            border-radius: 8px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Jazz Michael G. Nase</h1>
            <p>👋 Hi there! I'm Jazz Michael G. Nase, a passionate Bachelor of Science in Computer Science student at Cavite State University - Bacoor City Campus.</p>
        </header>

        <section class="interests">
            <h2>👀 Interests</h2>
            <ul id="interests-list">
                <li>Software Development</li>
                <li>Game Development</li>
                <li>Web Development</li>
                <li>Blockchain and Cryptocurrency Technologies</li>
                <li>Non-Fungible Tokens (NFTs)</li>
                <li>Artificial Intelligence (AI)</li>
            </ul>
        </section>

        <section class="currently-learning">
            <h2>🌱 Currently Learning</h2>
            <ul>
                <li>Advanced JavaScript and TypeScript</li>
                <li>Blockchain Development</li>
                <li>Machine Learning and AI integration</li>
            </ul>
        </section>

        <section class="projects">
            <h2>💼 Projects</h2>
            <div class="project-item">
                <h3>Marianne Hotel System</h3>
                <p><strong>Role:</strong> Project Leader</p>
                <p><strong>Technologies:</strong> PHP, PHPMailer, CSS, JavaScript</p>
                <p><strong>Description:</strong> Developed a comprehensive hotel management system for Marianne Hotel.</p>
            </div>
            <div class="project-item">
                <h3>RITSO (2D Top-Down Game)</h3>
                <p><strong>Role:</strong> Assistant Project Leader</p>
                <p><strong>Technologies:</strong> Unity, C#, Libresprite</p>
                <p><strong>Description:</strong> Contributed to the development of a 2D top-down game, focusing on game mechanics and sprite design.</p>
            </div>
            <!-- Add more projects here -->
        </section>

        <section class="contact">
            <h2>📫 Contact Me</h2>
            <p><strong>Email:</strong> jazzmichaelnase@gmail.com</p>
            <p><strong>Phone:</strong> 09612-148-397</p>
            <p><strong>Portfolio:</strong> <a href="https://jazznase.vercel.app/">jazznase.vercel.app</a></p>
            <p><strong>GitHub:</strong> <a href="https://github.com/JazzNase">@JazzNase</a></p>
        </section>

        <section class="fun-fact">
            <h2>⚡ Fun Fact</h2>
            <p>I enjoy exploring the creative world of digital art and NFTs, blending creativity with technical skills to drive innovation.</p>
        </section>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const interests = document.getElementById('interests-list');
            
            const newInterest = document.createElement('li');
            newInterest.textContent = "Emerging Technologies";
            interests.appendChild(newInterest);
        });
    </script>
</body>
</html>
