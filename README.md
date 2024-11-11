/* Make the body take full height and allow scrolling */
html, body {
    height: 100%;
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
}

/* Main box styling */
.box {
    background: rgba(0, 0, 0, 0.5); /* Slight black background for readability */
    border-radius: 15px;
    padding: 30px;
    margin: 20px 0;
    width: 80%;
    max-width: 700px;
    box-sizing: border-box;
    flex: 1; /* Allow box to expand and fill space */
}

/* Heading styling */
h1 {
    font-size: 2.5rem;
    margin-bottom: 20px;
    color: white; /* Change text color to white */
}

/* Launch text styling */
.launch-text {
    font-size: 1.4rem;
    margin-bottom: 20px;
    font-style: normal; /* Normal readable font style */
    font-weight: normal;
}

/* Social links styling */
.social-links a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-size: 1.2rem;
    padding: 10px;
    border-radius: 30px; /* Set border radius to 30px for social containers */
    background-color: rgba(255, 255, 255, 0.2);
    transition: background-color 0.3s ease;
}

/* Hover effect for social links */
.social-links a:hover {
    background-color: rgba(255, 255, 255, 0.4);
}

/* Footer styling */
.footer {
    position: fixed;
    bottom: 0;
    width: 100%;
    text-align: center;
    font-size: 1rem;
    color: rgba(255, 255, 255, 0.7);
    padding: 10px 0;
    background-color: rgba(0, 0, 0, 0.7); /* Ensure footer has a background */
    box-sizing: border-box;
}

/* Website link styling */
.website-link {
    font-size: 1.4rem;
    margin-top: 20px;
    color: #3E6240; /* Green color for the website link */
    text-decoration: none;
}

/* Website link hover effect */
.website-link:hover {
    text-decoration: underline;
}

/* Copyright styling */
.copyright {
    font-size: 1rem;
    color: rgba(255, 255, 255, 0.6);
    margin-top: 10px;
}

.copyright i {
    color: #FFD700; /* Gold color for the copyright icon */
}

/* Responsive design */
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
