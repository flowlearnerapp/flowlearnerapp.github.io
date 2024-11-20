<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Pages Site</title>
    <style>
        /* Full page black container */
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            background-color: black;
            font-family: Arial, sans-serif;
        }

        /* Stack widget: A simple flex container */
        .stack-widget {
            position: absolute;
            top: 10px;
            left: 10px;
            padding: 10px;
            background-color: rgba(255, 255, 255, 0.2);
            border-radius: 5px;
            color: white;
            font-size: 16px;
        }

        /* Background image covering entire page */
        .background-image {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: url('https://via.placeholder.com/1920x1080'); /* Change URL to your image */
            background-size: cover;
            background-position: center;
            z-index: -1;
        }

        /* Scrollable container */
        .scrollable-column {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100%;
            overflow-y: auto;
            padding: 20px;
        }

        /* Centered content inside scrollable container */
        .content {
            text-align: center;
            color: white;
            max-width: 800px;
            width: 100%;
        }

        /* Free containers inside the scrollable column */
        .container {
            background-color: rgba(255, 255, 255, 0.2);
            border-radius: 10px;
            margin: 10px;
            padding: 20px;
            color: white;
        }

    </style>
</head>
<body>

    <!-- Stack widget -->
    <div class="stack-widget">
        Stack Widget Example
    </div>

    <!-- Background image covering entire page -->
    <div class="background-image"></div>

    <!-- Scrollable column -->
    <div class="scrollable-column">
        <div class="content">

            <!-- Containers with border-radius -->
            <div class="container">
                <h2>Container 1</h2>
                <p>This is a free container with a border-radius of 10px and slight transparency.</p>
            </div>

            <div class="container">
                <h2>Container 2</h2>
                <p>This is another free container in the scrollable area.</p>
            </div>

            <div class="container">
                <h2>Container 3</h2>
                <p>Yet another container with similar styles.</p>
            </div>

        </div>
    </div>

</body>
</html>
