<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Syeda Ambreen Abid</title>

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;700&family=Fleur+De+Leah&display=swap" rel="stylesheet">

<style>
    body {
        background-color: #0f0f0f;
        font-family: 'Dancing Script', cursive;
        margin: 0;
        padding: 0;
        text-align: center;
        color: white;
    }

    /* Venom Header */
    .venom-header {
        font-size: 80px;
        font-weight: bold;
        animation: glow 2s infinite alternate;
        margin-top: 20px;
    }

    @keyframes glow {
        0% { text-shadow: 0 0 10px #df73b5, 0 0 20px #f795ea, 0 0 30px #c784a9, 0 0 40px #e0a3d3; }
        50% { text-shadow: 0 0 20px #b05e93, 0 0 40px #8a1f68, 0 0 60px #a01c81, 0 0 80px #df8ad9; }
        100% { text-shadow: 0 0 10px #ef7388, 0 0 20px #cf6aa3, 0 0 30px #e04f9a, 0 0 40px #f933de; }
    }

    /* Skills Section */
    .skills-section img {
        margin: 10px;
        width: 80px;
        opacity: 0;
        transform: scale(0.8);
        animation: fadeIn 1s forwards;
        display: inline-block;
        transition: transform 0.3s;
    }

    .skills-section img:hover {
        transform: scale(1.2) rotate(5deg);
    }

    .skills-section img:nth-child(1) { animation-delay: 0s; }
    .skills-section img:nth-child(2) { animation-delay: 0.3s; }
    .skills-section img:nth-child(3) { animation-delay: 0.6s; }
    .skills-section img:nth-child(4) { animation-delay: 0.9s; }
    .skills-section img:nth-child(5) { animation-delay: 1.2s; }
    .skills-section img:nth-child(6) { animation-delay: 1.5s; }

    @keyframes fadeIn {
        to { opacity: 1; transform: scale(1) rotate(0deg); }
    }

    /* Footer Animation */
    .footer-bg {
        position: relative;
        height: 120px;
        overflow: hidden;
    }

    .footer-bg div {
        position: absolute;
        width: 200%;
        height: 120px;
        background: linear-gradient(90deg, #00f, #0ff, #0f0, #ff0, #f00);
        animation: moveBG 8s linear infinite;
    }

    @keyframes moveBG {
        0% { transform: translateX(0%); }
        100% { transform: translateX(-50%); }
    }
</style>
</head>

<body>

<h1 class="venom-header">Syeda Ambreen Abid</h1>

<!-- Typing SVG -->
<p>
    <a href="https://github.com/Syeda-Ambreen-Abid">
        <img src="https://readme-typing-svg.herokuapp.com?font=Roboto+Slab&weight=700&size=31&pause=600&color=014D4E&center=true&vCenter=true&width=700&lines=Biomedical+Engineer+%7C+Python+Developer;AI+Enthusiast+%7C+Agentic+AI+Learner;Generative+AI+%26+Deep+Learning+Explorer;Aspiring Data Analyst | Power BI Enthusiast" alt="Typing Animation">
    </a>
</p>

<!-- Skills Section -->
<div class="skills-section">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg">
    <img src="https://cdn.educba.com/academy/wp-content/uploads/2020/01/Deep-Learning.jpg">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQreBNASZVyRbrzKbBF75VPZeSAm3KS8_tp2A&s">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRdz6YodKm5f6f3uOVf69tUpuYOt7_94HUAfg&s">
    <img src="https://pub-e93d5c9fdf134c89830082377f6df465.r2.dev/2025/01/Generative-AI-edited.webp">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRzjfBrmgqGx1J5e7OZDHtuJ4PNNUXwgIFugw&s">
</div>

<!-- Footer Animation -->
<div class="footer-bg">
    <div></div>
</div>

</body>
</html>
