# Birthday-Wish-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday!</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #ff9a9e, #fad0c4);
        }
        .message {
            display: none;
            font-size: 24px;
            color: white;
            background: linear-gradient(to right, #ff758c, #ff7eb3);
            padding: 20px;
            border-radius: 10px;
            margin: 20px auto;
            width: fit-content;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }
        .btn {
            font-size: 18px;
            padding: 10px 20px;
            background: linear-gradient(to right, #ff9966, #ff5e62);
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            transition: 0.3s;
        }
        .btn:hover {
            background: linear-gradient(to right, #ff5e62, #ff9966);
        }
    </style>
</head>
<body>
    <h1 style="color: white; text-shadow: 2px 2px 4px rgba(0,0,0,0.2);">Happy Birthday My Love! 🎂❤️</h1>
    <button class="btn" onclick="showMessage()">Click for Surprise</button>
    <div class="message" id="birthdayMessage">You are the most wonderful person in my life! Love you forever! 💖</div>
    <br>
    <a href="./gallery.html" class="btn">View Memories</a>
    <a href="./letter.html" class="btn">Read My Letter</a>
    <script>
        function showMessage() {
            document.getElementById('birthdayMessage').style.display = 'block';
        }
    </script>
</body>
</html>

<!-- gallery.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Memories</title>
    <style>
        body { background: linear-gradient(to right, #ff9a9e, #fad0c4); text-align: center; }
        .btn { font-size: 18px; padding: 10px 20px; background: #ff5e62; color: white; border: none; cursor: pointer; border-radius: 5px; }
    </style>
</head>
<body>
    <h1>Our Beautiful Memories 💕</h1>
    <p>I see you in the streets at school time, wearing your black and golden gown. That moment is forever in my heart. 💖</p>
    <a href="./index.html" class="btn">Back to Home</a>
</body>
</html>

<!-- letter.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Love Letter</title>
    <style>
        body { background: linear-gradient(to right, #ff9a9e, #fad0c4); text-align: center; }
        .btn { font-size: 18px; padding: 10px 20px; background: #ff5e62; color: white; border: none; cursor: pointer; border-radius: 5px; }
    </style>
</head>
<body>
    <h1>My Love Letter to You 💌</h1>
    <p>Dear Love,</p>
    <p>You make my world brighter every day. I cherish every moment with you and look forward to many more. Happy Birthday! 🎉💖</p>
    <p>I love you, Aiya. ❤️</p>
    <a href="index.html" class="btn">Back to Home</a>
</body>
</html>
