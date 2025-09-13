<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clawstruck - README</title>
    <style>
        body {
            background-color: #31293e;
            color: #dcdcdc;
            font-family: 'Courier New', Courier, monospace;
            line-height: 1.6;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            padding: 20px;
            box-sizing: border-box;
        }

        .readme-container {
            background-color: #160d13;
            border: 4px solid #5f575e;
            padding: 20px 40px;
            max-width: 800px;
            width: 100%;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.5);
        }

        h1, h2 {
            border-bottom: 2px solid #5f575e;
            padding-bottom: 10px;
            color: #ffffff;
        }

        h1 {
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        h2 {
            font-size: 1.8em;
            margin-top: 30px;
            margin-bottom: 15px;
        }

        p {
            margin-bottom: 15px;
        }

        strong {
            color: #a2999e;
            font-weight: bold;
        }
        
        code {
            background-color: #2d1b27;
            padding: 2px 5px;
            border-radius: 4px;
            font-family: 'Courier New', Courier, monospace;
        }

        .banner {
            width: 100%;
            height: 150px;
            background: url('imagenonassets/ClawstruckHeader.png');
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: #5f575e;
            font-size: 1.2em;
            margin-bottom: 30px;
        }
    </style>
</head>
<body>

    <div class="readme-container">
        <h1>Clawstruck</h1>

        <div class="banner">
            
        </div>

        <h2>About The Game</h2>
        <p>
            Clawstruck is a fast-paced arcade game where your goal is to survive as long as possible by dodging the relentless attacks of a evil cat's paw. Test your reflexes as the attacks get faster and more unpredictable over time.
        </p>

        <h2>How to Play</h2>
        <p>
            Use the <strong>Arrow Keys</strong> or <strong>W, A, S, D</strong> to move your character around the grid and avoid the incoming paw strikes.
        </p>

        <h2>Extra Note</h2>
        <p>
            The main game logic is contained within the <code>index.html</code> file. Please be aware that the JavaScript code inside this file has been minified to reduce its size to fit into the rules, making it difficult to read directly.
        </p>
        <p>
            If you wish to view, understand, or modify the source code, please refer to the <strong><code>nonminified.html</code></strong> file, which contains the original and more readable version of the code.
        </p>
    </div>

</body>
</html>
