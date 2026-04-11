<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MY WRITE-UPS</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background: #0a0a0a;
            font-family: 'Segoe UI', Arial, sans-serif;
            color: #00ff9d;
            text-align: center;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }

        h1 {
            font-size: 3.5rem;
            font-weight: bold;
            letter-spacing: 4px;
            margin-bottom: 80px;
            text-transform: uppercase;
            text-shadow: 0 0 20px #00ff9d;
        }

        .buttons {
            width: 100%;
            max-width: 600px;
        }

        .btn {
            display: block;
            width: 90%;
            max-width: 520px;
            margin: 18px auto;
            padding: 22px 30px;
            background: #1a1a1a;
            color: #00ff9d;
            font-size: 1.55rem;
            font-weight: 600;
            text-decoration: none;
            border: 2px solid #00ff9d;
            border-radius: 12px;
            transition: all 0.4s ease;
            box-shadow: 0 0 15px rgba(0, 255, 157, 0.3);
        }

        .btn:hover {
            background: #00ff9d;
            color: #0a0a0a;
            transform: translateY(-5px);
            box-shadow: 0 0 30px #00ff9d;
        }

        .subtitle {
            margin-top: 60px;
            font-size: 1.1rem;
            color: #666;
        }
    </style>
</head>
<body>
    <h1>MY WRITE-UPS</h1>
    
    <div class="buttons">
        <a href="/hackthebox/" class="btn">HackTheBox</a>
        <a href="/tryhackme/" class="btn">TryHackMe</a>
        <a href="/others/" class="btn">Others</a>
    </div>

    <p class="subtitle">Chọn một nền tảng để xem write-ups</p>
</body>
</html>
