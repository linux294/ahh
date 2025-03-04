<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tifa Ngecrot Zone 💦</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600&display=swap" rel="stylesheet">
    <style>
        body {
            background: #111;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: 'Poppins', sans-serif;
            text-align: center;
            color: white;
        }
        .btn {
            background: pink;
            padding: 20px 40px;
            border: none;
            border-radius: 20px;
            font-size: 20px;
            cursor: pointer;
            box-shadow: 0 0 20px pink;
            transition: 0.3s;
        }
        .btn:hover {
            background: hotpink;
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <div>
        <button class="btn" onclick="ngecrot()">Pencet Aku Sayang 😚</button>
    </div>

    <audio id="ahh" src="anime-ahh.mp3"></audio>

    <script>
        function ngecrot() {
            let ahh = document.getElementById("ahh");
            ahh.play();
            if (navigator.vibrate) {
                navigator.vibrate([500, 300, 500]); // Getaran ngeras masuk keluar 😏🍌💦
            }
        }
    </script>
</body>
</html>
