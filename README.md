<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sanyam Suyal | Portfolio</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: white;
            color: #000;
            text-align: center;
            position: relative;
            overflow-y: scroll;
            scrollbar-width: thin;
            scrollbar-color: #ff8a00 #f0f0f0;
        }

        ::-webkit-scrollbar {
            width: 10px;
        }

        ::-webkit-scrollbar-track {
            background: #f0f0f0;
            border-radius: 10px;
        }

        ::-webkit-scrollbar-thumb {
            background: linear-gradient(90deg, #ff8a00, #ffcc00);
            border-radius: 10px;
        }
        
        header {
            padding: 50px;
            background: linear-gradient(135deg, #1e3c72, #2a5298);
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }
        
        .name {
            font-size: 5rem;
            font-weight: bold;
            color: orange;
            margin: 20px 0;
            padding: 20px;
            border: 5px solid orange;
            display: inline-block;
            background-color: white;
            border-radius: 15px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.5);
            transition: transform 0.3s ease, background 0.3s ease, color 0.3s ease, box-shadow 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 4px;
            position: relative;
        }
        
        .name::after {
            content: "\"Code is like humor. When you have to explain it, it’s bad.\"";
            display: block;
            font-size: 1rem;
            color: black;
            font-style: italic;
            margin-top: 10px;
        }
        
        .name:hover {
            transform: scale(1.2);
            background: linear-gradient(45deg, white, #f0f0f0);
            color: orange;
            border-color: orange;
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.6);
        }
        
        .flowchart {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
            justify-content: center;
            padding: 50px;
        }
        
        .block {
            padding: 30px;
            background: #e0e0e0;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease, background 0.3s ease;
            cursor: pointer;
            color: #333;
        }
        
        .block:hover {
            transform: scale(1.1);
            background: darkgreen;
            color: white;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.5);
        }
        
        h1, h2 {
            color: #ff8a00;
        }
        
        .skills-project {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
        }
        
        .contact-buttons {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        
        .btn {
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            background: linear-gradient(90deg, #ff8a00, #ffcc00);
            color: black;
            font-size: 1rem;
            font-weight: bold;
            cursor: pointer;
            transition: transform 0.2s ease;
        }
        
        .btn:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <header>
        <div class="name">SANYAM SUYAL</div>
    </header>
    
    <div class="flowchart">
        <div class="block">
            <h2>Introduction</h2>
            <p>I'm <strong>Sanyam Suyal</strong>, a passionate developer with expertise in Game Development, Web Development, and Bot Creation. I have worked extensively in designing and developing interactive gaming experiences, crafting automation tools, and building modern web applications. My goal is to combine creativity with technology to develop engaging and efficient digital solutions.</p>
        </div>
        
        <div class="skills-project">
            <div class="block">
                <h2>Skills</h2>
                <p>✔ Game Development (Roblox, Minecraft, Unity) <br>✔ Web Development (HTML, CSS, JS, React, Node.js) <br>✔ Automation & Bots (Discord.js, Python) <br>✔ Programming Languages (Java, C++, Python)</p>
            </div>
            
            <div class="block">
                <h2>Projects</h2>
                <p>🎮 Hero Havoc (100M+ visits, 10M+ Robux) <br>🤖 Discord Bots for 50K+ servers <br>🌍 Portfolio Website (this one!)</p>
            </div>
        </div>
        
        <div class="block">
            <h2>Contact Me</h2>
            <p>Feel free to reach out!</p>
            <div class="contact-buttons">
                <button class="btn" onclick="location.href='mailto:your-email@example.com'">Email Me</button>
                <button class="btn" onclick="location.href='tel:+1234567890'">Call Me</button>
            </div>
        </div>
    </div>
</body>
</html>
