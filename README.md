<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="投資学習コミュニティでプロの情報と戦略を学び、資産を増やそう！">
    <title>投資学習コミュニティ - 今すぐ参加</title>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Noto Sans JP', sans-serif;
        }
        body {
            background-color: #f5f6f5;
            color: #333;
            line-height: 1.6;
        }
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
            text-align: center;
        }
        header {
            background: linear-gradient(135deg, #1e3a8a, #3b82f6);
            color: white;
            padding: 50px 20px;
            border-radius: 8px;
            margin-bottom: 30px;
        }
        header h1 {
            font-size: 2.2em;
            margin-bottom: 15px;
        }
        header p {
            font-size: 1.1em;
            max-width: 600px;
            margin: 0 auto 20px;
        }
        .countdown {
            font-size: 1em;
            font-weight: bold;
            color: #fef08a;
        }
        .cta-button {
            display: inline-block;
            background-color: #22c55e;
            color: white;
            padding: 14px 30px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1.1em;
            margin: 20px 0;
            transition: background-color 0.3s;
        }
        .cta-button:hover {
            background-color: #16a34a;
        }
        .hero-image {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            margin: 20px 0;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        .testimonials {
            margin: 30px 0;
        }
        .testimonials h3 {
            font-size: 1.4em;
            margin-bottom: 20px;
        }
        .testimonial {
            background: white;
            padding: 20px;
            border-radius: 8px;
            max-width: 500px;
            margin: 10px auto;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .trust {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin: 30px 0;
        }
        .trust img {
            height: 35px;
            filter: grayscale(100%);
            opacity: 0.7;
        }
        footer {
            background: #1e3a8a;
            color: white;
            padding: 15px;
            text-align: center;
            font-size: 0.9em;
        }
        footer a {
            color: #ddd;
            text-decoration: none;
        }
        @media (max-width: 768px) {
            header h1 {
                font-size: 1.7em;
            }
            header p {
                font-size: 1em;
            }
            .cta-button {
                padding: 12px 24px;
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>投資の未来を切り開く</h1>
            <p>プロの投資情報と学習コミュニティで、資産成長を実現しましょう！</p>
            <p class="countdown" id="countdown">特別オファー：残り <span id="timer">24時間</span></p>
            <a href="https://your-community-link.com" target="_blank" class="cta-button">今すぐ参加する</a>
        </div>
    </header>

    <section class="container">
        <img src="https://via.placeholder.com/600x400?text=Investment+Community" alt="投資コミュニティのスクリーンショット" class="hero-image">
    </section>

<section class="testimonials container">
        <h3>参加者の声</h3>
        <div class="testimonial">
            <p>「このコミュニティのおかげで、投資の知識が飛躍的に向上しました！」</p>
            <p><strong>- 山田太郎様、株式投資家</strong></p>
        </div>
        <div class="testimonial">
            <p>「専門家のアドバイスで、自信を持って投資判断ができるようになりました。」</p>
            <p><strong>- 佐藤花子様、投資初心者</strong></p>
        </div>
    </section>

    <section class="container">
        <a href="https://your-community-link.com" target="_blank" class="cta-button">今すぐコミュニティに参加</a>
    </section>

    <section class="container trust">
        <img src="https://via.placeholder.com/100x35?text=Expert1" alt="専門家1">
        <img src="https://via.placeholder.com/100x35?text=Partner2" alt="パートナー2">
        <img src="https://via.placeholder.com/100x35?text=Award3" alt="受賞歴3">
    </section>

    <footer>
        <p>© 2025 投資学習コミュニティ | <a href="#">プライバシーポリシー</a></p>
    </footer>

    <script>
        function startCountdown() {
            const timerElement = document.getElementById('timer');
            let timeLeft = 24 * 60 * 60;
            setInterval(() => {
                const hours = Math.floor(timeLeft / 3600);
                const minutes = Math.floor((timeLeft % 3600) / 60);
                const seconds = timeLeft % 60;
                timerElement.textContent = ${hours}時間 ${minutes}分 ${seconds}秒;
                timeLeft--;
                if (timeLeft < 0) timeLeft = 24 * 60 * 60;
            }, 1000);
        }
        startCountdown();
    </script>
</body>
</html>
