<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Alexander Shilenkov | Game & EdTech Developer</title>
    <meta name="google-site-verification" content="yV01X6f97eyTss5iVzCcbqJ65IF8-hliFAHyDw1xLNw" />
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #000000, #203a43, #4CAF50);
            color: #ffffff;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
            animation: fadeIn 1.5s ease-in;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }

            to {
                opacity: 1;
            }
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 40px auto;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }

        .image-block {
            width: 100%;
            text-align: center;
            margin-bottom: 30px;
        }

        .image-block img {
            max-width: 100%;
            height: auto;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
            transition: transform 0.5s ease-in-out;
        }

        .image-block img:hover {
            transform: scale(1.05);
        }

        .block {
            width: calc(50% - 20px);
            background-color: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 12px;
            padding: 25px;
            margin: 10px;
            box-sizing: border-box;
            backdrop-filter: blur(10px);
            transition: transform 0.3s ease, background-color 0.3s ease;
        }

        .block:hover {
            transform: translateY(-5px);
            background-color: rgba(255, 255, 255, 0.1);
        }

        .big-font {
            font-size: 28px;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .social-links {
            margin-top: 20px;
            animation: fadeInUp 1.5s ease-out;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }

            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .social-link {
            margin: 0 10px;
            font-size: 20px;
            color: #4CAF50;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        .social-link:hover {
            color: #7fc980;
        }

        .games-section {
            width: 90%;
            max-width: 1200px;
            text-align: center;
        }

        .game {
            display: inline-block;
            width: calc(25% - 20px);
            margin: 10px;
            background-color: rgba(255, 255, 255, 0.05);
            border-radius: 12px;
            padding: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease;
        }

        .game:hover {
            transform: scale(1.05);
        }

        .game img {
            width: 100%;
            border-radius: 10px;
        }

        @media (max-width: 768px) {

            .block,
            .game {
                width: 100%;
            }
        }
    </style>
</head>

<body>
    <div class="container">

        <!-- Image -->
        <div class="image-block">
            <img src="https://raw.githubusercontent.com/Alex-esc1/Alex-esc1.github.io/refs/heads/main/job.png"
                alt="Game Dev Image">
        </div>
        <!-- Name and Title -->
        <div class="block">
            <div class="big-font">Alex Shilenkov</div>
            <p>Mobile Developer</p>
        </div>

        <!-- Contact -->
        <div class="block">
            <div class="big-font">Connect</div>
            <div class="social-links">
                <button onclick="window.location.href='mailto:alex.pochta2015@gmail.com'"
                    style="margin-top: 10px; padding: 10px 15px; border: none; border-radius: 8px; background-color: #4CAF50; color: white; font-weight: bold; cursor: pointer;">
                    Send Email
                </button>
            </div>
        </div>

    </div>

    <!-- Games Section -->
    <div class="games-section">
        <div class="big-font">Mobile App</div>
        <div class="game">
            <a href="https://play.google.com/store/apps/details?id=com.shilenkov.periodic_table_atom_guide"
                target="_blank">
                <img src="https://raw.githubusercontent.com/Alex-esc1/Alex-esc1.github.io/refs/heads/main/pt.png"
                    alt="Periodic Table">
            </a>
            <p>Periodic Table - Atom Guide</p>
        </div>
        <div class="game">
            <a href="https://play.google.com/store/apps/details?id=com.shilenkov.prank_smash" target="_blank">
                <img src="https://raw.githubusercontent.com/Alex-esc1/Alex-esc1.github.io/refs/heads/main/prank.png"
                    alt="Prank Smash">
            </a>
            <p>Prank Smash</p>
        </div>
        <div class="game">
            <a href="https://play.google.com/store/apps/details?id=com.shilenkov.pop_bubbles" target="_blank">
                <img src="https://raw.githubusercontent.com/Alex-esc1/Alex-esc1.github.io/refs/heads/main/pop.png"
                    alt="Pop Bubbles">
            </a>
            <p>Pop Bubbles</p>
        </div>
        <div class="game">
            <a href="https://play.google.com/store/apps/details?id=com.shilenkov.pink_calculator" target="_blank">
                <img src="https://raw.githubusercontent.com/Alex-esc1/Alex-esc1.github.io/refs/heads/main/calc.png"
                    alt="Pink Calculator">
            </a>
            <p>Pink Calculator</p>
        </div>
    </div>
</body>

</html>