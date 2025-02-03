<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Language Selection</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
            background-color: hsl(209, 11.40%, 63.70%);
            margin: 0;
            padding: 0;
        }

        .container {
            text-align: center;
            width: 90%;
            max-width: 400px;
        }

        .welcome {
            font-size: 2em;
            margin-bottom: 15px;
        }

        .choose-language {
            font-size: 1.2em;
            margin-bottom: 20px;
        }

        .language-buttons {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .language-button {
            padding: 12px 24px;
            font-size: 1em;
            color: black;
            background-color: rgb(231, 222, 95);
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
            width: 100%;
            text-align: center;
        }

        .language-button:hover {
            background-color: rgba(202, 191, 34, 0.7);
        }

        @media (max-width: 600px) {
            .welcome {
                font-size: 1.8em;
            }

            .choose-language {
                font-size: 1em;
            }

            .language-button {
                padding: 10px 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="welcome">WELCOME</div>
        <div class="choose-language">Choose a language</div>
        <div class="language-buttons">
            <a href="https://tally.so/r/wo5DR1" class="language-button">Arabic</a>
            <a href="https://tally.so/r/w7adg6" class="language-button">Français</a>
        </div>
    </div>
</body>
</html>
