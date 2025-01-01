<!DOCTYPE html>
<html lang="mk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>За Тебе</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(120deg, #f4c9d1, #f8e3e0);
            color: #4a4a4a;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            text-align: center;
            background-size: 400% 400%;
            animation: gradientAnimation 15s ease infinite;
        }

        @keyframes gradientAnimation {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        h1 {
            color: #d6336c;
            font-size: 4.2rem;
            margin-bottom: 2rem;
            font-weight: 700;
            letter-spacing: 2px;
            text-transform: uppercase;
            text-shadow: 3px 3px 6px rgba(255, 255, 255, 0.7);
            animation: fadeIn 2s ease-in-out;
        }

        @keyframes fadeIn {
            0% { opacity: 0; transform: translateY(-30px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        p {
            font-size: 1.6rem;
            margin-bottom: 2.5rem;
            max-width: 750px;
            color: #4a4a4a;
            line-height: 1.6;
            font-style: italic;
            font-weight: 400;
            text-shadow: 1px 1px 4px rgba(255, 255, 255, 0.7);
            animation: fadeIn 3s ease-in-out;
        }

        .button {
            display: inline-block;
            padding: 15px 35px;
            background-color: #d6336c;
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-size: 1.3rem;
            font-weight: 600;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s, background-color 0.3s;
            border: 2px solid transparent;
            position: relative;
            overflow: hidden;
        }

        .button:hover {
            background-color: #b82d58;
            transform: translateY(-5px);
        }

        .button:active {
            transform: translateY(0);
        }

        .button:before {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            width: 300%;
            height: 300%;
            background-color: rgba(255, 255, 255, 0.3);
            border-radius: 50%;
            transform: translate(-50%, -50%) scale(0);
            animation: pulseEffect 0.6s ease-out;
        }

        @keyframes pulseEffect {
            100% { transform: translate(-50%, -50%) scale(1); }
        }

        /* Subtle Background Blur */
        .blur-background {
            position: absolute;
            top: 50%;
            left: 50%;
            width: 100%;
            height: 100%;
            background-image: url('https://source.unsplash.com/1600x900/?romantic,flowers');
            background-size: cover;
            background-position: center;
            filter: blur(8px);
            z-index: -1;
            animation: fadeInBackground 3s ease-out;
        }

        @keyframes fadeInBackground {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
    </style>
</head>
<body>
    <div class="blur-background"></div>
    <h1>Специјална Порака за Ирина</h1>
    <p>
        Even if the night sky was filled with stars, I would
        rather see them through the reflection in your eyes.
    </p>
    <a href="#" class="button">ТЕ САКАМ - од Игор</a>
</body>
</html>
