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
            background: black url('https://raw.githubusercontent.com/flowlearnerapp/flowlearnerapp.github.io/refs/heads/main/Flowlearnerapp%20background.jpg') no-repeat center center fixed;
            background-size: cover;
            color: white;
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            padding: 10px;
            box-sizing: border-box;
            height: 100vh;
            min-height: 100vh;
            overflow-x: hidden; /* Prevent horizontal scrolling */
            max-width: 100vw; /* Ensure no element overflows horizontally */
        }

        .content {
            flex-grow: 1;
            width: 100%;
            max-width: 700px;
            box-sizing: border-box;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            height: 110vh; /* Ensure full viewport height */
            padding: 30px;
            padding-bottom: 90px; /* Add padding at the bottom */
            overflow-x: hidden; /* Prevent horizontal overflow */
        }

        .box {
            background: rgba(0, 0, 0, 0.5); 
            border-radius: 30px;
            padding: 10px 10px 10px 10px;
            margin: 10px 0;
            width: 100%;
            box-sizing: border-box;
            overflow-x: hidden; /* Prevent content overflow */
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            color: white; 
        }

        .launch-text {
            font-size: 1.4rem;
            margin-bottom: 20px;
            font-family: 'Verdana', sans-serif; 
            line-height: 1.6; 
        }

        .social-links {
            display: flex;
            justify-content: center;
            flex-wrap: wrap; 
            gap: 15px;
        }

        .social-links a {
            color: white;
            text-align: center;
            text-decoration: none;
            font-size: 1.2rem;
            padding: 10px;
            border-radius: 30px;
            background-color: rgba(255, 255, 255, 0.2);
            transition: background-color 0.3s ease;
        }

        .social-links a:hover {
            background-color: rgba(255, 255, 255, 0.4);
        }

        .website-link {
            font-size: 1.4rem;
            margin-top: 90px;
            color: #3E6240;
            text-decoration: none;
        }

        .website-link:hover {
            text-decoration: underline;
        }

        .footer {
            width: 100%;
            text-align: center;
            font-size: 1rem;
            color: rgba(255, 255, 255, 0.7);
            padding: 10px 0;
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
                padding: 8px;
            }
        }
    </style>
</head>
<body>
    <div class="content">
        <div class="box">
            <h1>Hi Flowlearner!</h1>
            <p class="launch-text">Unlock Your Inner Flowlearner! If you love learning, you’re already a Flowlearner.</p>
        </div>

        <div class="box">
            <h2>🌅 Wake Up to Learning</h2>
            <p class="launch-text">Imagine waking up in the morning and starting your day with a quick, brain-boosting learning exercise...</p>
        </div>

        <div class="box">
            <h2>🚌 Learning on the Go</h2>
            <p class="launch-text">Whether you're on the bus, waiting in line, or taking a short break, every moment becomes an opportunity to learn...</p>
        </div>

        <!-- Add other boxes as per the original structure -->

        <div class="box">
            <h2>📱 Follow Us</h2>
            <p class="launch-text">Follow us on social media to get exclusive updates on the Flowlearner app...</p>
            <div class="social-links">
                <a href="https://www.instagram.com/flowlearnerapp/profilecard/?igsh=ZTZuZGxmeDh4NHk5" target="_blank">Instagram</a>
                <a href="https://www.tiktok.com/@flowlearnerapp?_t=8rYAgm2WqqO&_r=1" target="_blank">TikTok</a>
                <a href="https://youtube.com/@flowlearnerapp?si=Twh5d4r_0XDF2ahq" target="_blank">YouTube</a>
                <!-- Add other social links as needed -->
            </div>
        </div>
    </div>

    <div class="footer">
        <div class="email-container">
            <a href="mailto:support@flowlearner.com" style="color: white">support@flowlearner.com</a>
            <a href="mailto:bugs@flowlearner.com" style="color: white">bugs@flowlearner.com</a>
            <a href="mailto:legal@flowlearner.com" style="color: white">legal@flowlearner.com</a>
            <a href="mailto:security@flowlearner.com" style="color: white">security@flowlearner.com</a>
        </div>
        <p>&copy; 2024 Flowlearner, All rights reserved.</p>
    </div>
</body>
</html>
