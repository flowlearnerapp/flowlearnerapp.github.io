<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to FlowLearner</title>
    <style>
        body {
            background-color: #000000;
            color: #fff;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            height: 100vh;
            background-image: url('https://source.unsplash.com/1600x900/?colorful,blur,bokeh');
            background-size: cover;
            background-position: center;
            position: relative;
        }

        ::after {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-image: inherit;
            filter: blur(5px);
            z-index: -1;
        }

        .container {
            position: relative;
            z-index: 1;
            background: rgba(255, 255, 255, 0.6);
            padding: 30px;
            border-radius: 15px;
            max-width: 800px;
            margin: 0 auto;
            text-align: center;
            backdrop-filter: blur(10px);
        }

        h1 {
            font-size: 2.5em;
            font-weight: bold;
            color: #fff;
            margin-bottom: 20px;
            text-align: center;
        }

        .cta p {
            font-size: 1.5em;
            color: #fff;
        }

        .cta a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
            font-weight: bold;
            padding: 10px 20px;
            border-radius: 50px;
            background-color: #333;
            transition: background-color 0.3s ease;
        }

        .cta a:hover {
            background-color: #555;
        }

        .social-media {
            margin-top: 20px;
            display: flex;
            justify-content: space-around;
            align-items: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .social-media a {
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: #ccc;
            padding: 20px;
            border-radius: 50px;
            color: #333;
            text-decoration: none;
            font-weight: bold;
            width: 200px;
            height: 80px;
            text-align: center;
            transition: background-color 0.3s ease;
        }

        .social-media a:hover {
            background-color: #bbb;
        }

        .social-media img {
            width: 40px;
            vertical-align: middle;
            margin-right: 10px;
        }

        footer {
            font-size: 1em;
            text-align: center;
            color: #fff;
            margin-top: 50px;
            padding-bottom: 20px;
            position: fixed;
            bottom: 0;
            width: 100%;
            left: 50%;
            transform: translateX(-50%);
        }

        .embed-container {
            position: relative;
            padding-bottom: 56.25%;
            height: 0;
            overflow: hidden;
            max-width: 100%;
            margin-top: 20px;
        }

        .embed-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2em;
                margin-bottom: 15px;
            }

            .cta p {
                font-size: 1.2em;
            }

            .cta a {
                padding: 8px 16px;
                font-size: 1em;
            }

            .social-media a {
                font-size: 1em;
                padding: 8px 16px;
                width: 180px;
            }

            .social-media img {
                width: 35px;
            }

            footer {
                font-size: 0.9em;
            }
        }

        @media (max-width: 480px) {
            .container {
                padding: 15px;
                max-width: 100%;
                background: rgba(255, 255, 255, 0.9);
            }

            h1 {
                font-size: 1.8em;
                margin-bottom: 10px;
            }

            .cta p {
                font-size: 1.1em;
            }

            .cta a {
                font-size: 0.9em;
                padding: 6px 12px;
            }

            .social-media a {
                font-size: 0.9em;
                padding: 6px 12px;
                width: 160px;
            }

            footer {
                font-size: 0.8em;
                padding-bottom: 10px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hi Future Flowlearner, and Welcome to the Official FlowLearnerApp Website</h1>
        
        <div class="cta">
            <p>Our app will be launching soon! Follow us on social media to be one of the first Flowlearners.</p>
            <p>Or at least one of the first ;) </p>
        </div>

        <!-- Embed YouTube Video -->
        <div class="embed-container">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/your_video_id" frameborder="0" allowfullscreen></iframe>
        </div>
        
        <div class="social-media">
            <p>Follow us for updates:</p>
            <a href="https://www.instagram.com/flowlearnerapp/profilecard/?igsh=ZTZuZGxmeDh4NHk5" target="_blank">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Instagram_logo_2022.svg/1200px-Instagram_logo_2022.svg.png" alt="Instagram"> 
                Instagram
            </a>
            <a href="https://www.tiktok.com/@flowlearnerapp?_t=8rHsPTZSn1k&_r=1" target="_blank">
                <img src="https://upload.wikimedia.org/wikipedia/commons/6/67/TikTok_logo_2018.svg" alt="TikTok"> 
                TikTok
            </a>
            <a href="https://x.com/flowlearnerapp?s=09" target="_blank">
                <img src="https://upload.wikimedia.org/wikipedia/commons/e/e8/X_logo_%282023%29.svg" alt="X"> 
                X (formerly Twitter)
            </a>
            <a href="https://youtube.com/@flowlearnerapp?si=Twh5d4r_0XDF2ahq" target="_blank">
                <img src="https://upload.wikimedia.org/wikipedia/commons/4/42/YouTube_icon_%282013-2017%29.png" alt="YouTube"> 
                YouTube
            </a>
        </div>
    </div>
    
    <footer>
        <p>© 2024 FlowLearner. All rights reserved.</p>
    </footer>
</body>
</html>
