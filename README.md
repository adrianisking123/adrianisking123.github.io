<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>EduGames - Learn and Play</title>
    <link rel="stylesheet" type="text/css" href="style.css">
    <script src="script.js"></script>
</head>
<body>
    <header>
        <h1>Welcome to EduGames!</h1>
        <p>Where learning meets fun!</p>
    </header>

    <section id="learning-content">
        <h2>Learn Something New</h2>
        <p>Did you know that the speed of light is approximately 299,792,458 meters per second? Here at EduGames, we make learning science, math, and other subjects fun!</p>
    </section>

    <section id="quiz-section">
        <h2>Quick Quiz</h2>
        <p>Test your knowledge with our quick quiz!</p>
        <button id="start-quiz">Start Quiz</button>
    </section>

    <section id="quiz-content" style="display: none;">
        <p>Question 1: What is the chemical symbol for gold?</p>
        <button onclick="checkAnswer('Au')">Au</button>
        <button onclick="checkAnswer('Ag')">Ag</button>
        <button onclick="checkAnswer('Fe')">Fe</button>
        <div id="quiz-result"></div>
    </section>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    padding: 20px;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 10px;
    text-align: center;
}

section {
    margin: 20px 0;
}

button {
    background-color: #4CAF50;
    color: white;
    border: none;
    padding: 10px;
    cursor: pointer;
}

button:hover {
    background-color: #45a049;
}

#quiz-result {
    margin-top: 10px;
}
