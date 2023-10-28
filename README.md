
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background: linear-gradient(45deg, #4b6cb7, #182848);
            background-size: 400% 400%;
            animation: gradient 10s ease infinite;
        }

        @keyframes gradient {
            0% {
                background-position: 0% 50%;
            }
            50% {
                background-position: 100% 50%;
            }
            100% {
                background-position: 0% 50%;
            }
        }

        .content {
            text-align: center;
            color: white;
        }

        .code-container {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
            margin: 20px;
        }

        .code {
            background: rgba(0, 0, 0, 0.8);
            border-radius: 8px;
            padding: 20px;
            overflow: auto;
        }

        .code pre {
            color: #00ff80;
            font-size: 18px;
        }

        .code pre code {
            display: block;
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }

        .skill {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .skill img {
            width: 50px;
            height: 50px;
        }

        .skill p {
            color: #00ff80;
        }

        .animated-text {
            display: inline-block;
        }

        .animated-text span {
            opacity: 0;
            display: inline-block;
            transform: translateY(1em);
            animation: fadeIn 1s forwards;
            animation-delay: 0.5s;
        }

        @keyframes fadeIn {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <div class="content">
        <h1>Hi there! I'm Your Name</h1>
        <p class="animated-text">🚀 Full Stack Developer | 🌍 Open Source Enthusiast | ✨ Passionate About Code</p>
        <div class="skills">
            <div class="skill">
                <img src="machine-learning.svg" alt="Machine Learning" />
                <p class="animated-text"><span>I am a Machine Learning enthusiast</span></p>
            </div>
            <div class="skill">
                <img src="c-plus-plus.svg" alt="C++" />
                <p class="animated-text"><span>Proficient in C++</span></p>
            </div>
            <div class="skill">
                <img src="python.svg" alt="Python" />
                <p class="animated-text"><span>Skilled in Python</span></p>
            </div>
            <div class="skill">
                <img src="rust.svg" alt="Rust" />
                <p class="animated-text"><span>Familiar with Rust</span></p>
            </div>
            <div class="skill">
                <img src="typescript.svg" alt="TypeScript" />
                <p class="animated-text"><span>Experienced in TypeScript</span></p>
            </div>
        </div>
        <div class="code-container">
            <h2>My Awesome Code</h2>
            <div class="code">
                <pre><code>// Welcome to my GitHub profile!
console.log("Hello, World!");

const aboutMe = "I love coding and building cool things.";
const languages = ["JavaScript", "Python", "HTML", "CSS"];
const frameworks = ["React", "Node.js", "Express"];
const tools = ["VS Code", "Git", "GitHub"];

console.log(`About Me: ${aboutMe}`);
console.log("My Skills:");
console.log(`Languages: ${languages.join(", ")}`);
console.log(`Frameworks: ${frameworks.join(", ")}`);
console.log(`Tools: ${tools.join(", ")}`);
                </code></pre>
            </div>
        </div>
        <p>Let's connect: <a href="https://github.com/yourusername">GitHub</a> | <a href="https://linkedin.com/in/yourusername">LinkedIn</a></p>
    </div>
</body>
</html>
