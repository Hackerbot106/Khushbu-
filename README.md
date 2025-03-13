# Khushbu-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Holi Invite - JD Splash</title>
    <style>
        body {
            background: linear-gradient(45deg, #ff4b2b, #ff416c, #ffcc00, #33cc33, #3399ff);
            background-size: 400% 400%;
            animation: gradientBG 6s ease infinite;
            text-align: center;
            font-family: 'Arial', sans-serif;
            color: white;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
        }

        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        h1 {
            font-size: 50px;
            font-weight: bold;
            background: -webkit-linear-gradient(45deg, #ffcc00, #ff4b2b, #33cc33, #3399ff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: splashEffect 2s infinite alternate;
        }

        @keyframes splashEffect {
            0% { transform: scale(1); }
            100% { transform: scale(1.1); }
        }

        p {
            font-size: 24px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>Welcome to JD Splash</h1>
    <p>Let’s celebrate the festival of colors with joy and happiness!</p>
</body>
</html>
