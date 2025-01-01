<!DOCTYPE html>
<html lang="mk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>За Тебе</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #ffe6e6, #f8b8d0);
            color: #333;
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
            font-size: 4rem;
            margin-bottom: 1.5rem;
            font-weight: bold;
            letter-spacing: 2px;
            text-shadow: 3px 3px 6px rgba(255, 255, 255, 0.6);
            animation: fadeIn 2s ease-in-out;
        }

        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        p {
            font-size: 1.4rem;
            margin-bottom: 2rem;
            max-width: 700px;
            color: #4a4a4a;
            line-height: 1.8;
            font-style: italic;
            text-shadow: 1px 1px 3px rgba(255, 255, 255, 0.8);
            animation: fadeIn 3s ease-in-out;
        }

        .button {
            display: inline-block;
            margin-top: 20px;
            padding: 14px 35px;
            background-color: #d6336c;
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-size: 1.2rem;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
            transition: background-color 0.3s, transform 0.3s;
        }

        .button:hover {
            background-color: #b82d58;
            transform: translateY(-5px);
        }

        .button:active {
            transform: translateY(0);
        }

        /* Subtle Glow Effect */
        .button {
            background-image: linear-gradient(45deg, #f06, #d6336c);
            background-size: 200% 200%;
            animation: glowing 3s ease-in-out infinite;
        }

        @keyframes glowing {
            0% { background-position: 200% 200%; }
            50% { background-position: -200% -200%; }
            100% { background-position: 200% 200%; }
        }
    </style>
</head>
<body>
    <h1>Специјална Порака за Ирина</h1>
    <p>
        Even if the night sky was filled with stars, I would
        rather see them through the reflection in your eyes.
    </p>
    <a href="#" class="button">ТЕ САКАМ - од Игор</a>
</body>
</html>
