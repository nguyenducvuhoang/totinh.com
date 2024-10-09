<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tỏ Tình Với Crush</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #ff4d79, #ff9966);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
            position: relative;
        }

        .container {
            background: rgba(255, 255, 255, 0.8);
            padding: 50px;
            border-radius: 20px;
            box-shadow: 0px 4px 30px rgba(0, 0, 0, 0.1);
            text-align: center;
            position: relative;
            animation: fadeIn 2s ease;
        }

        h1 {
            font-size: 3em;
            color: #ff3366;
            margin-bottom: 20px;
            animation: bounceIn 2s ease;
        }

        p {
            font-size: 1.2em;
            color: #333;
            margin-bottom: 20px;
        }

        .button {
            background-color: #ff66b2;
            border: none;
            color: white;
            padding: 15px 40px;
            text-align: center;
            font-size: 1.2em;
            margin-top: 20px;
            cursor: pointer;
            border-radius: 50px;
            transition: background-color 0.3s, transform 0.3s;
        }

        .button:hover {
            background-color: #ff3399;
            transform: scale(1.1);
        }

        .heart {
            font-size: 120px;
            color: #ff6699;
            animation: pulse 1.5s infinite;
        }

        @keyframes fadeIn {
            0% {
                opacity: 0;
                transform: translateY(-50px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes bounceIn {
            0%, 20%, 50%, 80%, 100% {
                transform: translateY(0);
            }
            40% {
                transform: translateY(-30px);
            }
            60% {
                transform: translateY(-15px);
            }
        }

        @keyframes pulse {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.1);
            }
            100% {
                transform: scale(1);
            }
        }

        .floating-heart {
            position: absolute;
            animation: floatUp 10s infinite ease-in-out;
        }

        @keyframes floatUp {
            0% {
                bottom: -10%;
                left: 50%;
                opacity: 0;
            }
            50% {
                opacity: 1;
            }
            100% {
                bottom: 110%;
                left: 20%;
                opacity: 0;
            }
        }

        .heart1 {
            font-size: 50px;
            color: rgba(255, 102, 153, 0.5);
            left: 10%;
            bottom: -10%;
            animation-duration: 8s;
        }

        .heart2 {
            font-size: 70px;
            color: rgba(255, 204, 204, 0.4);
            left: 70%;
            bottom: -10%;
            animation-duration: 12s;
        }

        .admin {
            font-size: 1em;
            color: #555;
            position: absolute;
            bottom: 20px;
            right: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Tớ Thích Cậu Nhiều Lắm!</h1>
        <p>Cậu có biết không? Tớ đã thầm thích cậu từ rất lâu rồi. Trái tim tớ luôn đập rộn ràng khi gặp cậu.</p>
        <div class="heart">❤️</div>
        <p>Nếu cậu cũng thích tớ, hãy nhấn nút dưới đây nhé!</p>
        <button class="button" onclick="alert('Tớ rất vui vì cậu cũng thích tớ! ^^')">Tớ Cũng Thích Cậu</button>
    </div>

    <div class="floating-heart heart1">❤️</div>
    <div class="floating-heart heart2">💖</div>

    <!-- Thêm tên admin -->
    <div class="admin">
     ADMIN   NGUYỄN ĐỨC VŨ HOÀNG
    </div>
</body>
</html>
