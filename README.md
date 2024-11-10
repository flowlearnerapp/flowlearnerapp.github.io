<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to FlowLearner</title>
    <style>
        /* Dark Mode Styles */
        body {
            background-color: #000000;  /* Pitch black background */
            color: #fff;  /* White text color for contrast */
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            height: 100vh;
            background-image: url('https://source.unsplash.com/1600x900/?colorful,blur,bokeh'); /* Random colorful background with blur effect */
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
            background: rgba(255, 255, 255, 0.6); /* Semi-transparent white background */
            padding: 30px;
            border-radius: 15px;  /* Rounded corners */
            max-width: 800px;
            margin: 0 auto;
            text-align: center;
            backdrop-filter: blur(10px); /* Background blur effect */
        }

        h1 {
            font-size: 2.5em;
            font-weight: bold;
            color: #fff;  /* White text */
            margin-bottom: 20px;
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
            border-radius: 50px;  /* Bubbles effect */
            background-color: #333;  /* Dark bubble background */
            transition: background-color 0.3s ease;
        }

        .cta a:hover {
            background-color: #555;  /* Lighter bubble on hover */
        }

        .social-media {
            margin-top: 20px;
        }

        .social-media a {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            background-color: #ccc;  /* Grey background for rounded box */
            padding: 10px 20px;
            border-radius: 50px;
            color: #333;
            text-decoration: none;
            font-weight: bold;
        }

        .social-media a:hover {
            background-color: #bbb;  /* Lighter grey on hover */
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
            transform: translateX(-50%);  /* Centering the footer text */
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
        </div>
    </div>
    
    <footer>
        <p>© 2024 FlowLearner. All rights reserved.</p>
    </footer>
</body>
</html>
