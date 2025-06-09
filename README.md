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

.projects {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 15px;
    margin-top: 20px;
}

.project-card {
    background: rgba(255, 255, 255, 0.1);
    padding: 15px;
    border-radius: 8px;
    cursor: pointer;
    transition: transform 0.3s ease-in-out;
}

.project-card:hover {
    transform: scale(1.1);
}

.hidden {
    display: none;
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
