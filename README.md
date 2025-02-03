<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Language Selection</title>
    <style>
        /* General body styling */
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
            background-color: hsl(209, 11.40%, 63.70%);
            margin: 0; /* Remove default margin */
        }

        /* Container for centering content */
        .container {
            text-align: center;
            position: relative; /* For absolute positioning of child elements */
        }

        /* Styling for the "WELCOME" text */
        .welcome {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        /* Styling for the "Choose a language" text */
        .choose-language {
            font-size: 1.5em;
            margin-bottom: 20px;
        }

        /* Container for the buttons */
        .language-buttons {
            display: flex;
            gap: 20px;
            position: absolute; /* Position buttons absolutely */
            left: -200px; /* Move buttons to the left */
            top: 50%; /* Center vertically */
            transform: translateY(-50%); /* Adjust vertical centering */
        }

        /* Styling for the buttons */
        .language-button {
            padding: 10px 20px;
            font-size: 1em;
            color: black;
            background-color: rgb(231, 222, 95);
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
        }

        /* Hover effect for the buttons */
        .language-button:hover {
            background-color: rgba(202, 191, 34, 0.7);
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
