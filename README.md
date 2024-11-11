<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flowlearner</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: url('https://raw.githubusercontent.com/flowlearnerapp/flowlearnerapp.github.io/f06b264cee5b4a9a3dac696005391db791a6c220/signal-2024-11-11-003122_002.png') no-repeat center center fixed;
            background-size: cover;
            height: 100vh;
            color: white;
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            padding: 20px;
            box-sizing: border-box;
        }

        /* Apply a blur effect to the background */
        ::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: inherit;
            filter: blur(8px);
            z-index: -1;
        }

        .box {
            background: rgba(0, 0, 0, 0.6);
            border-radius: 15px;
            padding: 30px;
            margin: 20px 0;
            width: 80%;
            max-width: 600px;
            box-sizing: border-box;
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        .launch-text {
            font-size: 1.4rem;
            margin-bottom: 20px;
        }

        .social-links a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2rem;
            padding: 12px 20px;
            border-radius: 30px;  /* Increased border-radius */
            background-color: rgba(255, 255, 255, 0.2);
            transition: background-color 0.3s ease;
        }

        .social-links a:hover {
            background-color: rgba(255, 255, 255, 0.4);
        }

        .footer {
            position: absolute;
            bottom: 10px;
            width: 100%;
            text-align: center;
            font-size: 1rem;
        }

        @media (max-width: 600px) {
            .box {
                width: 90%;
                padding: 20px;
            }
            h1 {
                font-size: 2rem;
            }
            .launch-text {
                font-size: 1.2rem;
            }
            .social-links a {
                font-size: 1rem;
                margin: 0 8px;
            }
        }
    </style>
</head>
<body>
    <div class="box">
        <h1>Hi Future Flowlearner</h1>
    </div>
    <div class="box">
        <p class="launch-text">Our app will be launching soon. Follow us on social media to be one of the first Flowlearners.</p>
        <div class="social-links">
            <a href="https://www.tiktok.com/@flowlearnerapp?_t=8rHsPTZSn1k&_r=1" target="_blank">TikTok</a>
            <a href="https://x.com/flowlearnerapp?s=09" target="_blank">X (Twitter)</a>
            <a href="https://youtube.com/@flowlearnerapp?si=Twh5d4r_0XDF2ahq" target="_blank">YouTube</a>
        </div>
    </div>
    <div class="footer">
        <p>© 2024 Flow Learner, All rights reserved.</p>
    </div>
</body>
</html>
