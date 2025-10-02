<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blancat's BIO</title>
    <style>
        body {
            background: url('https://i.pinimg.com/originals/a9/c2/cd/a9c2cd6f9d5a954604a9f5ca7cdaa75a.gif') no-repeat center center fixed;
            background-size: cover;
            font-family: Arial, sans-serif;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            flex-direction: column;
            text-align: center;
        }

        .profile-container {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            margin-bottom: 40px;
        }

        .profile-image {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 5px solid white;
            background-image: url('https://i.ytimg.com/vi/k485z6Eeufo/maxresdefault.jpg');
            background-size: cover;
            background-position: center;
        }

        .profile-text {
            margin-top: 20px;
        }

        .profile-text h2 {
            font-size: 2em;
            margin: 0;
        }

        .profile-text p {
            font-size: 1.1em;
            color: white;  /* Set text color to white */
            text-shadow: 0 0 10px white;  /* Add white glow effect */
        }

        .discord-btn {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            border: 3px solid purple;
            background-image: url('https://static.vecteezy.com/system/resources/previews/023/986/880/non_2x/discord-logo-discord-logo-transparent-discord-icon-transparent-free-free-png.png');
            background-size: cover;
            background-position: center;
            margin-top: 40px;
            cursor: pointer;
            transition: transform 0.2s ease, box-shadow 0.2s ease;
        }

        .discord-btn:hover {
            transform: translateY(-5px);
            box-shadow: 0 0 10px 5px purple;
        }

        .play-stop-btns {
            position: absolute;
            bottom: 20px;
            display: flex;
            justify-content: space-between;
            width: 100%;
            padding: 0 20px;
        }

        .play-btn, .stop-btn {
            padding: 15px 25px;
            font-size: 1.2em;
            background-color: purple;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .stop-btn {
            display: none;
        }

        .play-btn:hover, .stop-btn:hover {
            background-color: #5a1b8d;
        }
    </style>
</head>
<body>

    <div class="profile-container">
        <div class="profile-image"></div>
        <div class="profile-text">
            <h2>astrokittygaming</h2>
            <p>Hello! I Am Blancat aka astrokittygaming On Discord. I Am A Discord Server Owner And I Love My Supporters!</p>
            <p>I Love Kitty Cat's :3</p>
        </div>
        <div class="discord-btn" onclick="window.open('https://discord.gg/rKC5F4YFEu', '_blank');"></div>
    </div>

    <div class="play-stop-btns">
        <button class="stop-btn" onclick="stopRickroll()">STOP</button>
    </div>

</body>
</html>
