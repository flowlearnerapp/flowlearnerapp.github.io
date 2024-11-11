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
            background: url('https://pixabay.com/photos/clouds-sunset-cloudy-storm-7397802/') no-repeat center center fixed;
            background-size: cover;
            height: 100vh;
            color: white;
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: center; /* Center content vertically */
            align-items: center; /* Center content horizontally */
            padding: 0 20px; /* Add padding to avoid text touching the sides */
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
            margin: 15px 0;
            width: 80%;
            max-width: 600px;
            box-sizing: border-box;
            text-align: center;
        }

        h1 {
            font-size: 2.5rem;
            margin: 0;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7); /* Improve text visibility */
        }

        .launch-text {
            font-size: 1.5rem;
            margin: 10px 0;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.7); /* Subtle shadow for text readability */
        }

        .social-links a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2rem;
            transition: transform 0.3s ease;
        }

        .social-links a:hover {
            transform: scale(1.1); /* Slight zoom effect on hover */
        }

        .footer {
            position: fixed;
            bottom: 20px;
            width: 100%;
            text-align: center;
            font-size: 1rem;
        }

        .footer p {
            margin: 0;
        }

        @media (max-width: 600px) {
            .box {
                width: 90%;
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
