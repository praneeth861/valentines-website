<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Valentine's Day</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            background-color: #ffcccb;
            color: #d10056;
            margin: 0;
            padding: 0;
        }
        .container {
            padding: 50px;
        }
        h1 {
            font-size: 3em;
        }
        p {
            font-size: 1.5em;
        }
        .heart {
            font-size: 5em;
            color: red;
            animation: heartbeat 1.5s infinite;
        }
        @keyframes heartbeat {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
        .animation {
            position: relative;
            width: 100%;
            height: 500px;
            background: url('https://upload.wikimedia.org/wikipedia/commons/a/a8/Paris_Night.jpg') no-repeat center center;
            background-size: cover;
        }
        .boy {
            position: absolute;
            left: -100px;
            bottom: 50px;
            width: 150px;
            animation: boy-move 5s ease-in-out forwards;
        }
        .girl {
            position: absolute;
            right: 100px;
            bottom: 50px;
            width: 150px;
        }
        @keyframes boy-move {
            0% { left: -100px; }
            100% { left: 40%; }
        }
    </style>
</head>
<body>
    <div class="animation">
        <img src="https://www.pngall.com/wp-content/uploads/4/Boy-Giving-Flower-PNG.png" class="boy" alt="Boy giving tulips">
        <img src="https://www.pngall.com/wp-content/uploads/4/Girl-PNG-Pic.png" class="girl" alt="Girl receiving tulips">
    </div>
    
    <div class="container">
        <h1>Happy Valentine's Day, My Love! ❤️</h1>
        <p>You are my everything, and I love you more than words can say.</p>
        <p class="heart">❤</p>
    </div>
</body>
</html>
