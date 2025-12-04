<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Flowlearner</title>
    <style>
        html, body {
            height: 100%;
            margin: 0;
            padding: 0;
        }
        .background {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://raw.githubusercontent.com/flowlearnerapp/flowlearnerapp.github.io/refs/heads/main/Flowlearner%20background.png') no-repeat center center / cover;
            z-index: 0;
        }
        body {
            color: black;
            font-family: sans-serif;
            line-height: 1.5;
            padding-top: env(safe-area-inset-top);
            padding-bottom: env(safe-area-inset-bottom);
            padding-left: env(safe-area-inset-left);
            padding-right: env(safe-area-inset-right);
        }
        .container {
            position: relative;
            z-index: 1;
            width: 100%;
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            box-sizing: border-box;
        }
        .rounded-container {
            background: rgba(255, 255, 255, 0.5);
            border-radius: 20px;
            padding: 20px;
            margin-bottom: 40px;
            overflow-wrap: break-word;
        }
        .header {
            position: relative;
            text-align: center;
        }
        .logo {
            width: 64px;
            height: 64px;
            border-radius: 50%;
            display: block;
            margin: 0 auto 10px;
        }
        .title {
            font-size: 32px;
            margin: 0;
        }
        .subtitle {
            font-size: 18px;
            margin: 10px 0;
            overflow-wrap: break-word;
        }
        .fact {
            font-size: 16px;
            margin: 10px 0;
            overflow-wrap: break-word;
        }
        .coming-soon {
            font-size: 14px;
            color: orange;
            margin: 10px 0;
        }
        .section-header {
            display: flex;
            align-items: center;
            margin-bottom: 10px;
        }
        .icon {
            font-size: 24px;
            margin-right: 10px;
        }
        .section-title {
            font-size: 24px;
            margin: 0;
        }
        .section-text {
            font-size: 16px;
            margin: 0;
            overflow-wrap: break-word;
        }
        .yellow-icon {
            color: yellow;
        }
        .blue-icon {
            color: #3b82f6;
        }
        .purple-icon {
            color: #7c3aed;
        }
        .social-buttons {
            display: flex;
            flex-wrap: wrap;
            justify-content: flex-start;
            margin: 20px 0;
        }
        .social-button {
            background-color: #ddd;
            color: black;
            border: none;
            border-radius: 20px;
            padding: 8px 16px;
            margin: 5px;
            font-size: 14px;
            cursor: pointer;
        }
        .support {
            font-size: 12px;
            margin: 10px 0;
            text-align: center;
        }
        .copyright {
            font-size: 12px;
            text-align: center;
        }
        @media (min-width: 768px) {
            .container {
                max-width: 900px;
            }
            .social-buttons {
                justify-content: center;
            }
        }
        @media (prefers-color-scheme: dark) {
            body {
                color: white;
            }
            .rounded-container {
                background: rgba(0, 0, 0, 0.5);
            }
            .social-button {
                background-color: #333;
                color: white;
            }
            .yellow-icon {
                color: yellow;
            }
        }
        @media (max-width: 480px) {
            .container {
                padding: 10px;
            }
            .title {
                font-size: 28px;
            }
            .subtitle {
                font-size: 16px;
            }
            .fact {
                font-size: 14px;
            }
            .section-title {
                font-size: 20px;
            }
            .section-text {
                font-size: 14px;
            }
        }
    </style>
</head>
<body>
    <div class="background"></div>
    <div class="container">
        <div class="rounded-container header">
            <img src="https://raw.githubusercontent.com/flowlearnerapp/flowlearnerapp.github.io/refs/heads/main/Flowlearner_Logo.png" alt="Flowlearner Logo" class="logo">
            <h1 class="title">Flowlearner</h1>
            <p class="subtitle">Welcome to the Future of Fun Interactive Learning!</p>
            <p class="fact">Did You Know? Otters hold hands while sleeping to prevent drifting apart!</p>
            <p class="coming-soon">Coming Soon /</p>
        </div>
        <div class="rounded-container">
            <div class="section-header">
                <span class="icon yellow-icon">☀️</span>
                <h2 class="section-title">Wake Up To Learning</h2>
            </div>
            <p class="section-text">Imagine waking up in the morning and starting your day with a quick, brain-boosting learning exercise. Rather than feeling sluggish, why not energize yourself with a fun challenge that sparks your curiosity and focus?</p>
        </div>
        <div class="rounded-container">
            <div class="section-header">
                <span class="icon yellow-icon">🚀</span>
                <h2 class="section-title">Learning on the Go</h2>
            </div>
            <p class="section-text">Whether you're on the bus, waiting in line, or taking a short break, every moment becomes an opportunity to learn. With Flowlearner, you can engage your mind, even without headphones, making every minute count.</p>
        </div>
        <div class="rounded-container">
            <div class="section-header">
                <span class="icon yellow-icon">💡</span>
                <h2 class="section-title">Challenge Your Mind</h2>
            </div>
            <p class="section-text">Flowlearner is designed to fuel your brain power with interactive games that are both fun and educational. Improve your skills and knowledge while enjoying the process!</p>
        </div>
        <div class="rounded-container">
            <div class="section-header">
                <span class="icon yellow-icon">👥</span>
                <h2 class="section-title">Learn With Friends</h2>
            </div>
            <p class="section-text">Learning is more enjoyable when you can challenge friends and track your progress together. Flowlearner makes it easy to connect with others, turning your learning journey into a dynamic, social experience.</p>
        </div>
        <div class="rounded-container">
            <div class="section-header">
                <span class="icon blue-icon">📈</span>
                <h2 class="section-title">Track Your Growth</h2>
            </div>
            <p class="section-text">With Flowlearner, you can easily track your learning journey. Monitor your progress, set goals, and celebrate your achievements as you level up your skills and knowledge.</p>
        </div>
        <div class="rounded-container">
            <div class="section-header">
                <span class="icon blue-icon">🌐</span>
                <h2 class="section-title">Join The Flowlearner Community</h2>
            </div>
            <p class="section-text">Learning is a lifelong journey, and at Flowlearner, we believe in evolving together. Join a vibrant community of learners who are passionate about growth, exploration, and fun.</p>
        </div>
        <div class="rounded-container">
            <div class="section-header">
                <span class="icon yellow-icon">⭐</span>
                <h2 class="section-title">Unlock Your Best Self</h2>
            </div>
            <p class="section-text">Everyone has an ideal version of themselves—someone who is constantly growing, learning, and evolving. Flowlearner helps you take actionable steps towards becoming that person every day, with bite-sized learning opportunities that fit your lifestyle.</p>
        </div>
        <div class="rounded-container">
            <div class="section-header">
                <span class="icon purple-icon">🎮</span>
                <h2 class="section-title">Learning Through Fun Games</h2>
            </div>
            <p class="section-text">Say goodbye to boring textbooks and hello to interactive educational games that make learning feel like play! Flowlearner's gamified approach turns every challenge into an opportunity to grow while having fun.</p>
        </div>
        <div class="rounded-container">
            <div class="section-header">
                <span class="icon yellow-icon">🧘</span>
                <h2 class="section-title">Relax and Recharge Your Mind</h2>
            </div>
            <p class="section-text">Learning isn't just about work; it's about growth and well-being. Flowlearner's exercises help clear your mind, reduce stress, and improve focus—perfect for winding down or recharging during the day.</p>
        </div>
        <div class="rounded-container">
            <div class="section-header">
                <span class="icon blue-icon">📱</span>
                <h2 class="section-title">Follow Us</h2>
            </div>
            <p class="section-text">Follow us on social media to get exclusive updates on the Flowlearner app, sneak peeks at new features, and behind-the-scenes content. Be part of the journey from day one and get the latest news as we build something amazing!</p>
            <div class="social-buttons">
                <button class="social-button">Instagram</button>
                <button class="social-button">TikTok</button>
                <button class="social-button">YouTube</button>
                <button class="social-button">Bluesky</button>
                <button class="social-button">Snapchat</button>
                <button class="social-button">Reddit</button>
                <button class="social-button">Mastodon</button>
                <button class="social-button">Clubhouse</button>
                <button class="social-button">Twitch</button>
                <button class="social-button">Quora</button>
                <button class="social-button">Pinterest</button>
                <button class="social-button">Discord</button>
                <button class="social-button">Medium</button>
                <button class="social-button">X</button>
                <button class="social-button">Telegram</button>
                <button class="social-button">Threads</button>
            </div>
        </div>
        <div class="support">
            bug@flowlearner.app support@flowlearner.app legal@flowlearner.app
        </div>
        <div class="copyright">
            © 2025 Flowlearner. All rights reserved.
        </div>
    </div>
</body>
</html>
