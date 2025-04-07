body {
    margin: 0;
    font-family: 'Arial', sans-serif;
    background: black url('https://raw.githubusercontent.com/flowlearnerapp/flowlearnerapp.github.io/refs/heads/main/Flowlearnerapp%20background.jpg') no-repeat center center;
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
    overflow-x: hidden;
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
    padding: 15px; /* Adjust the existing padding */
    padding-top: 10px; /* Reduced padding above the container */
    padding-bottom: 60px; /* Add padding at the bottom */
}

.box {
    background: rgba(0, 0, 0, 0.5); 
    border-radius: 30px;
    padding: 10px 20px; /* Modified padding for equal sides */
    margin: 10px 0;
    width: 100%;
    box-sizing: border-box;
}

.profile-photo {
    border-radius: 50%;
    width: 94px;
    height: 94px;
    margin-bottom: 5px; /* Reduced margin below the profile photo */
}

h1 {
    font-size: 2.5rem;
    margin-bottom: 5px; /* Reduced margin below the heading */
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
    gap: 15px; /
}

.social-links a {
    color: white;
    text-decoration: center;
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
.footer {
    width: 100%;
    text-align: center;
    font-size: 1rem;
    color: rgba(255, 255, 255, 0.7);
    padding: 10px 0;
}

.website-link:hover {
    text-decoration: underline;
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
        padding: 10px;
    }
}

body {
  /* Add the following line to enable text adjustment on zoom */
  zoom: 100%;
}