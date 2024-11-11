<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flowlearner</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: url('https://source.unsplash.com/1600x900/?sunset') no-repeat center center fixed;
            background-size: cover;
            height: 100vh;
            color: white;
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: flex-start;
            padding: 20px;
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
            padding: 20px;
            margin: 10px 0;
            width: 80%;
            max-width: 600px;
        }

        h1 {
            font-size: 2rem;
        }

        .social-links a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
        }

        .footer {
            position: absolute;
            bottom: 10px;
            width: 100%;
            text-align: center;
        }

        .launch-text {
            font-size: 1.5rem; /* Increase text size */
        }

        @media (max-width: 600px) {
            .box {
                width: 90%;
            }
            .launch-text {
                font-size: 1.2rem; /* Adjust launch text size on smaller screens */
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
