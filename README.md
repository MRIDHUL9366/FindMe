<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Find Me on GitHub</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f7fc;
            color: #333;
            animation: fadeIn 2s ease-in-out;
        }
        
        h1 {
            text-align: center;
            color: #007bff;
            animation: slideIn 1.5s ease-out;
        }
        
        @keyframes slideIn {
            0% { transform: translateX(-100%); }
            100% { transform: translateX(0); }
        }

        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        .container {
            width: 80%;
            margin: 0 auto;
            text-align: center;
            padding-top: 50px;
        }

        .badge-container img {
            margin: 10px;
            animation: zoomIn 1s ease-in-out;
        }

        @keyframes zoomIn {
            0% { transform: scale(0.8); opacity: 0; }
            100% { transform: scale(1); opacity: 1; }
        }

        h2 {
            color: #333;
            margin-top: 40px;
            font-size: 28px;
            animation: fadeIn 2s ease-in-out;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 5px solid #007bff;
            margin-top: 20px;
            animation: rotate 2s ease-in-out;
        }

        @keyframes rotate {
            0% { transform: rotate(0); }
            100% { transform: rotate(360deg); }
        }

        .contact a {
            color: #007bff;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        .contact a:hover {
            color: #0056b3;
        }

        ul {
            list-style-type: none;
            padding-left: 0;
            animation: fadeIn 2s ease-in-out;
        }

        li {
            font-size: 18px;
            margin: 10px 0;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Welcome to My GitHub</h1>

    <div class="badge-container">
        <img src="https://img.shields.io/badge/Code-Python-blue?style=for-the-badge&logo=python">
        <img src="https://img.shields.io/badge/Framework-Django-green?style=for-the-badge&logo=django">
        <img src="https://img.shields.io/badge/Frontend-HTML/CSS/JS-orange?style=for-the-badge&logo=html5&logo=css3&logo=javascript">
        <img src="https://img.shields.io/badge/Tools-Bootstrap/jQuery-purple?style=for-the-badge&logo=bootstrap&logo=jquery">
    </div>

    <h2>About Me</h2>
    <p>
        Hello! My name is Mridhul, and I'm a Python full-stack developer with experience in Django, HTML, CSS, JavaScript, Bootstrap, and jQuery. 
        I enjoy building web applications and learning new technologies to expand my skill set.
    </p>

    <img class="profile-img" src="https://via.placeholder.com/150" alt="Profile Picture">

    <h2>Skills</h2>
    <ul>
        <li>Python</li>
        <li>Django</li>
        <li>HTML/CSS/JavaScript</li>
        <li>Bootstrap</li>
        <li>jQuery</li>
    </ul>

    <h2>Contact</h2>
    <p class="contact">
        You can reach me via email at <a href="mailto:mridhulmaddy8943@gmail.com">mridhulmaddy8943@gmail.com</a> or connect with me on 
        <a href="https://www.linkedin.com/in/mridhul-s-9b3816296/">LinkedIn</a>.
    </p>
</div>

</body>
</html>
