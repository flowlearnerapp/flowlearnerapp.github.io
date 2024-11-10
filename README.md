<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to FlowLearner</title>
    <style>
        /* Dark Mode Styles */
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

        /* Add blur effect only to the background */
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
        }

        .social-media a {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            background-color: #ccc;
            padding: 10px 20px;
            border-radius: 50px;
            color: #333;
            text-decoration: none;
            font-weight: bold;
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

        /* Media Query for Smaller Screens */
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
            }

            .social-media img {
                width: 35px;
            }

            footer {
                font-size: 0.9em;
            }
        }

        /* Media Query for Extra Small Screens */
        @media (max-width: 480px) {
            .container {
                padding: 15px;
                max-width: 100%;
                background: rgba(255, 255, 255, 0.9); /* More opaque background */
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
