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
            background: #000000;
            height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            font-family: Arial, sans-serif;
            overflow: hidden;
        }

        h1 {
            font-size: 4rem;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 6px;
            color: #00ff9d;
            text-shadow: 
                0 0 10px #00ff9d,
                0 0 20px #00ff9d,
                0 0 40px #00ff9d;
            margin-bottom: 90px;
        }

        .btn {
            display: block;
            width: 520px;
            padding: 24px 40px;
            margin: 16px 0;
            background: #111111;
            border: 3px solid;
            border-radius: 12px;
            font-size: 1.65rem;
            font-weight: 600;
            text-decoration: none;
            text-align: center;
            transition: all 0.4s ease;
        }

        .btn-htb {
            color: #00ff9d;
            border-color: #00ff9d;
        }

        .btn-htb:hover {
            background: #00ff9d;
            color: #000000;
            box-shadow: 0 0 30px #00ff9d;
        }

        .btn-thm {
            color: #ff2e63;
            border-color: #ff2e63;
        }

        .btn-thm:hover {
            background: #ff2e63;
            color: #000000;
            box-shadow: 0 0 30px #ff2e63;
        }

        .btn-others {
            color: #00ff9d;
            border-color: #00ff9d;
        }

        .btn-others:hover {
            background: #00ff9d;
            color: #000000;
            box-shadow: 0 0 30px #00ff9d;
        }
    </style>
</head>
<body>
    <h1>MY WRITE-UPS</h1>
    
    <a href="/hackthebox/" class="btn btn-htb">HackTheBox</a>
    <a href="/tryhackme/" class="btn btn-thm">TryHackMe</a>
    <a href="/others/" class="btn btn-others">Others</a>
</body>
</html>
