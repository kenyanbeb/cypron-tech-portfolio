# cypron-tech-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cypron Tech Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <script src="script.js" defer></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background: linear-gradient(to right, #141E30, #243B55);
            color: white;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }
        h1 {
            font-size: 2.5em;
            margin-top: 50px;
            animation: fadeIn 2s ease-in-out;
        }
        p {
            font-size: 18px;
            animation: slideUp 1.5s ease-in-out;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        li {
            font-size: 20px;
            margin: 10px 0;
            opacity: 0;
            transform: translateY(20px);
            animation: fadeInUp 1s ease-in-out forwards;
        }
        a {
            color: #FFD700;
            text-decoration: none;
            font-weight: bold;
        }
        footer {
            margin-top: 20px;
            font-size: 14px;
            color: #ccc;
            animation: fadeIn 2s ease-in-out;
        }
        .music-player {
            margin-top: 30px;
            padding: 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            display: inline-block;
        }
        iframe {
            width: 560px;
            height: 315px;
            border: none;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <h1>Cypron Tech Portfolio — Edited and credited to Supreme Lord Cypron</h1>
    <p>Welcome to my portfolio showcasing my tech projects.</p>
    <ul>
        <li>Project One</li>
        <li>Project Two</li>
        <li>Project Three</li>
        <li>Project Four</li>
        <li>Project Five</li>
        <li>Project Six</li>
    </ul>
    
    <div class="music-player">
        <h2>Listen to Don Williams</h2>
        <iframe src="https://www.youtube.com/embed/lC5-cNm7HFw" allowfullscreen></iframe>
    </div>

    <p>Join my <a href="#">WhatsApp Channel</a></p>
    <footer>© 2025 Cypron Tech Portfolio — Thank you!</footer>
</body>
</html>
