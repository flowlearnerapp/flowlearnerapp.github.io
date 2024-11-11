/* Global styles */
body, html {
    margin: 0;
    padding: 0;
    height: 100%;
    font-family: Arial, sans-serif;
}

a {
    color: #1e90ff;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

/* Full-screen background */
.background {
    position: relative;
    width: 100%;
    height: 100%;
}

.background-image {
    object-fit: cover;
    width: 100%;
    height: 100%;
    opacity: 0.8; /* Slight opacity for the background image */
    position: absolute;
    top: 0;
    left: 0;
}

/* Flexible content container */
.content-container {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: rgba(0, 0, 0, 0.7); /* Semi-transparent background */
    color: white;
    padding: 30px;
    border-radius: 25px; /* Curved corners */
    max-width: 800px;
    width: 90%;
    text-align: center;
    z-index: 10; /* Ensures the container is on top of the background */
}

/* Text styling */
h1 {
    font-size: 2.5rem;
    margin-bottom: 20px;
}

p {
    font-size: 1.2rem;
}

/* Social media flex container */
.social-links {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin: 20px 0;
}

.social-link-container {
    background-color: rgba(255, 255, 255, 0.2); /* Slightly transparent background */
    padding: 15px 20px;
    border-radius: 30px;
}

.social-link-container a {
    color: white;
    font-size: 1.2rem;
}

/* Footer */
.footer {
    position: absolute;
    bottom: 10px;
    left: 50%;
    transform: translateX(-50%);
    color: white;
    font-size: 0.8rem;
}
