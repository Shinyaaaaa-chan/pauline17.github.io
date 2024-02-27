<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
   
    <style>
        /* CSS code goes here */
        body {
            font-family: Arial, sans-serif;
            background-color: #8E7AB5; 
            color: #333;
            margin: 0;
            padding: 0;
        }

        header img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            margin-top: -75px; 
        }

        main {
            padding: 20px;
        }

        section {
            margin-bottom: 20px;
            background-color: #c5a0c5; 
            padding: 20px;
            border-radius: 8px; 
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); 
        }

        h2 {
            color: #35155D; 
            display: inline-block;
            margin-bottom: 10px;
        }
        
        p {
            margin: 10px 0;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        footer {
            background-color: #a81b7c;
            color: #fff;
            text-align: center;
            padding: 20px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        form {
            background-color: #8E7AB5;
            padding: 20px;
            margin-top: 20px;
            border-radius: 5px;
        }

        .icon {
            color: #a81b7c; 
            margin-right: 10px;
        }
        
        .about-me {
            text-align: center;
        }
        
        .about-me p {
            margin: 10px auto;
        }
        
        .profile-pic {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            margin-bottom: 100px;
            position: absolute;
            left: 20px;
            top: auto; 
            bottom: 230px; 
        }

        .cover-photo {
            width: 100%;
            height: 250px; 
            background-image: url('https://i.pinimg.com/originals/83/b8/09/83b809857acd41a7bad4935b4734f9fc.gif'); /* URL to your cover photo */
            background-size: cover;
            background-position: center;
            position: relative;
            margin-bottom: 20px;
        }

        .profile-name {
            display: inline-block;
            margin-left: 50px; 
            vertical-align: middle;
        }

        .profile-info {
            text-align: center;
        }

        .personal-details {
            padding-top: 20px;
        }
    </style>
</head>
<body>

    <!-- Cover photo section -->
    <div class="cover-photo"></div>

    <!-- Main content section -->
    <main>
        <!-- Profile picture -->
        <img src="c:\Users\HP\OneDrive\Pictures\images\ayamiiiiiii\HTML\WEB_PAGE\shinya.jpg" alt="Profile Picture" class="profile-pic"> <!-- Professional photo -->

        <h1>SHANE PAULINE JAYME</h1>
        
        <!-- About Me description -->
        <div class="about-me">
            <h2></i>About Me</h2>
            <b><p>I am an 2nd year student taking Bachelor of Science in Information Technology in Laguna State Polytechnic University, San Pablo City Campus  I am honing my skills in software development and digital innovation. Passionate about harnessing technology to solve real-world problems, I eagerly embrace every opportunity to expand my knowledge and contribute to the ever-evolving field of IT.</p></b>
        </div>

        <!-- Personal Information section -->
        <section id="personal-info">
            <div class="container">
                <h2><i class="fas fa-user icon"></i>Personal Information</h2>
                <p><i class="fas fa-home icon"></i>From: Bay, Laguna</p> <!-- Live in section -->
                <p><i class="fas fa-heart icon"></i>Status: Single</p>
                <p><i class="fas fa-calendar-alt icon"></i>Birthday: 06-17-02</p>
            </div>
        </section>

        <!-- Education section -->
        <section id="education">
            <div class="container">
                <h2><i class="fas fa-graduation-cap icon"></i>Education</h2>
                <p><i class="fas fa-university icon"></i>Sto Domingo Elementary School (2010-2016)</p>
                <p><i class="fas fa-university icon"></i>Nicolas L. Galvez Memorial Integrated Natonal High School (2016-2022)</p>
                <p><i class="fas fa-trophy icon"></i>2nd place in Badminton since 2019-2020</p>
                <p><i class="fas fa-trophy icon"></i>3rd place in Poster Making</p>
                <p><i class="fas fa-trophy icon"></i>Academic achiever since 2016-2022</p>
                <p><i class="fas fa-university icon"></i>Currently studying BS. Information Technology at Laguna State Polytechnic University</p>
            </div>
        </section>

        <!-- Skills section -->
        <section id="skills">
            <div class="container">
                <h2><i class="fas fa-cogs icon"></i>Skills</h2>
                <ul>
                    <li>Photography</li>
                    <li>Graphic Design</li>
                    <li>Video Editing</li>
                    <!-- Add more skills as needed -->
                </ul>
            </div>
        </section>

        <!-- Projects section -->
        <section id="projects">
            <div class="container">
                <h2><i class="fas fa-project-diagram icon"></i>Projects</h2>
                <!-- Showcase your projects with brief descriptions, roles, and links -->
                <div class="project">
                    <h3>KAPEER YU: An Online Social Media Platform for LSPU students</h3>
                    <p>Description: KAPEER YU is an exclusive online social media platform for LSPU students, fostering  academic and social media connectivity in a  secure environment. It offers a seamless spaces for students to share resources, discuss coursework, and engage in campus events. </p>
                    <p>Role: Designer</p>
                </div>
                <!-- Add more projects as needed -->
            </div>
        </section>

        </section>

        <!-- Contact Information section -->
        <section id="contact">
            <div class="container">
                <h2><i class="fas fa-address-book icon"></i>Contact Information</h2>
                <!-- Provide contact information -->
                <p><i class="fas fa-envelope icon"></i>Email: shanejayme119@gmail.com</p>
                <p><i class="fab fa-instagram icon"></i>Instagram: shayamiiiiii</p>
                
            </div>
        </section>
    </main>
</body>
</html>
