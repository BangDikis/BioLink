# BioLink
Sterimer Kecil
[index (1).html](https://github.com/user-attachments/files/25128669/index.1.html)
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Bioprofil BangDik</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- FONT AWESOME -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            min-height: 100vh;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #fff;
            background: #000;
        }

        /* BACKGROUND FIX (ANTI CLICK BUG) */
        .bg {
            position: fixed;
            inset: 0;
            background:
                linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
                url("https://image2url.com/r2/default/images/1770379967765-9368b48b-ea94-47e4-b961-fea60ab16a41.png");
            background-size: cover;
            background-position: center;
            filter: blur(6px);
            transform: scale(1.05);
            z-index: -1;
            pointer-events: none;
        }

        /* CARD */
        .card {
            width: 100%;
            max-width: 360px;
            padding: 24px;
            background: #2b2b2b;
            border-radius: 18px;
            text-align: center;
            border: 2px solid #9b59ff;
            box-shadow: 0 0 25px rgba(155, 89, 255, 0.9);
            animation: fadeIn 0.8s ease forwards, glow 2s infinite alternate;
        }

        @keyframes glow {
            from { box-shadow: 0 0 12px rgba(155, 89, 255, 0.6); }
            to   { box-shadow: 0 0 35px rgba(155, 89, 255, 1); }
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to   { opacity: 1; transform: translateY(0); }
        }

        /* PROFILE IMAGE */
        .card img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 14px;
            border: 3px solid #9b59ff;
            box-shadow:
                0 0 15px rgba(155, 89, 255, 0.8),
                0 0 30px rgba(155, 89, 255, 0.6);
        }

        h1 {
            margin: 8px 0 4px;
            font-size: 24px;
        }

        .title {
            font-size: 14px;
            color: #bbb;
            margin-bottom: 12px;
        }

        .desc {
            font-size: 14px;
            line-height: 1.5;
            margin-bottom: 22px;
        }

        /* SOCIAL BUTTON */
        .social a {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            width: 100%;
            padding: 14px;
            margin-bottom: 12px;
            border-radius: 12px;
            font-weight: bold;
            text-decoration: none;
            color: #fff;
            transition: transform 0.2s, opacity 0.2s;
        }

        .social a:hover {
            transform: scale(1.04);
            opacity: 0.9;
        }

        .social i {
            font-size: 18px;
        }

        .tiktok  { background: #000; }
        .youtube { background: #ff0000; }
        .discord { background: #5865F2; }
        .saweria { background: #fcb900; color: #000; }

        @media (max-width: 400px) {
            .card {
                min-height: 100vh;
                border-radius: 0;
                display: flex;
                flex-direction: column;
                justify-content: center;
            }
        }
    </style>
</head>

<body>

<div class="bg"></div>

<div class="card">
    <img src="https://image2url.com/r2/default/images/1770381265711-4af3479c-e89b-49b2-a848-511bc49980f5.jpg" alt="Foto BangDik">

    <h1>BangDik</h1>
    <div class="title">Streamer Kecil</div>

    <p class="desc">
        Streamer kecil tapi niat 🔥<br>
        Hobi main game & ngobrol.<br>
        Mampir dan support ya!
    </p>

    <div class="social">
        <a class="tiktok" href="https://www.tiktok.com/@bangdik_20" target="_blank">
            <i class="fab fa-tiktok"></i> TikTok
        </a>

        <a class="youtube" href="https://www.youtube.com/@Siddiq20" target="_blank">
            <i class="fab fa-youtube"></i> YouTube
        </a>

        <a class="discord" href="https://discord.gg/YbqcUTnzgX" target="_blank">
            <i class="fab fa-discord"></i> Discord
        </a>

        <a class="saweria" href="https://saweria.co/Siddiq20" target="_blank">
            <i class="fas fa-money-bill-wave"></i> Saweria
        </a>
    </div>
</div>

</body>
</html>
