<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sachin Nagar's Portfolio</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f0f4f8;
      margin: 0;
      padding: 0;
      color: #333;
    }

    h1, h3 {
      text-align: center;
      margin: 20px 0;
      color: #1a202c;
    }

    h1 {
      font-size: 3rem;
      animation: fadeIn 2s ease-out;
    }

    h3 {
      font-size: 1.5rem;
      animation: fadeIn 3s ease-out;
    }

    .img-container {
      animation: slideIn 1.5s ease-out;
      margin-top: 20px;
      text-align: center;
    }

    .img-container img {
      width: 100%;
      max-width: 400px;
      border-radius: 15px;
    }

    .connect-icons img {
      margin: 10px;
      transition: transform 0.3s ease;
    }

    .connect-icons img:hover {
      transform: scale(1.1);
    }

    .tools-icons img {
      margin: 10px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .tools-icons img:hover {
      transform: scale(1.1);
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    }

    @keyframes fadeIn {
      0% {
        opacity: 0;
        transform: translateY(-20px);
      }
      100% {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes slideIn {
      0% {
        opacity: 0;
        transform: translateX(100px);
      }
      100% {
        opacity: 1;
        transform: translateX(0);
      }
    }

    .profile-stats {
      display: flex;
      justify-content: space-around;
      margin: 20px 0;
    }

    .profile-stats img {
      border-radius: 10px;
    }
  </style>
</head>
<body>

  <h1>Hi 👋, I'm Sachin Nagar</h1>
  <h3>A Passionate Software Engineer from India</h3>
  
  <div class="img-container">
    <img src="https://camo.githubusercontent.com/cae12fddd9d6982901d82580bdf321d81fb299141098ca1c2d4891870827bf17/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f313336302f302a37513379765349765f7430696f4a2d5a2e676966" alt="coding">
  </div>

  <p align="left">
    <img src="https://komarev.com/ghpvc/?username=thesachindhakad&label=Profile%20views&color=0e75b6&style=flat" alt="thesachindhakad" />
  </p>

  <hr>

  <h2>🔥 About Me</h2>
  <ul>
    <li>🌱 I’m currently learning <strong>Java Full Stack and Data Structures & Algorithms</strong>.</li>
    <li>💬 Ask me about <strong>Backend Development</strong>.</li>
    <li>📫 You can reach me at <strong><a href="mailto:sachindhakad7265@gmail.com">sachindhakad7265@gmail.com</a></strong>.</li>
    <li>📄 Check out my <a href="https://drive.google.com/file/d/11n2JFTJOI-9LLYZdlB8Ohzp6hTbq-_xB/view?usp=sharing">Resume</a>.</li>
  </ul>

  <h2>📢 Connect with Me:</h2>
  <div class="connect-icons">
    <a href="https://linkedin.com/in/sachin-nagar-102929231" target="blank">
      <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="40" width="40">
    </a>
    <a href="https://fb.com/sachin dhakad" target="blank">
      <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="Facebook" height="40" width="40">
    </a>
    <a href="https://instagram.com/thesachindhakad" target="blank">
      <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram" height="40" width="40">
    </a>
    <a href="https://www.hackerrank.com/profile/sachindhakad7265" target="blank">
      <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hackerrank.svg" alt="Hackerrank" height="40" width="40">
    </a>
    <a href="https://leetcode.com/sachin-nagar-dev/" target="blank">
      <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="LeetCode" height="40" width="40">
    </a>
  </div>

  <h2>🛠️ Languages and Tools:</h2>
  <div class="tools-icons">
    <a href="https://getbootstrap.com" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="50" height="50">
    </a>
    <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="50" height="50">
    </a>
    <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="50" height="50">
    </a>
    <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="50" height="50">
    </a>
    <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer">
      <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="50" height="50">
    </a>
    <a href="https://git-scm.com/" target="_blank" rel="noreferrer">
      <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="50" height="50">
    </a>
    <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="50" height="50">
    </a>
    <a href="https://www.java.com" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="50" height="50">
    </a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="50" height="50">
    </a>
    <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="50" height="50">
    </a>
    <a href="https://www.mysql.com/" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="50" height="50">
    </a>
    <a href="https://nodejs.org" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="50" height="50">
    </a>
    <a href="https://www.python.org" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="50" height="50">
    </a>
  </div>

  <h2>🔥 Experience</h2>
  <ul>
    <li><strong>Avyaan Management</strong> [June 2023 – Nov 2023] - Back-End Developer Intern: Built a Transcription Tool using Python.</li>
    <li><strong>Zappian Media Private Limited</strong> [Feb 2024 – March 2024] - Back-End Developer Intern: Contributed to Campaign Lab Web Application.</li>
    <li><strong>Tryidol</strong> - Software Engineer Trainee: Developed and deployed RESTful APIs and enhanced performance.</li>
  </ul>

  <h2>📊 My GitHub Stats</h2>
  <div class="profile-stats">
    <img src="https://github-readme-stats.vercel.app/api?username=thesachindhakad&show_icons=true&locale=en" alt="GitHub Stats">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=thesachindhakad&" alt="GitHub Streak">
    <img src="https://github-readme-stats.vercel.app/api/top-langs?username=thesachindhakad&show_icons=true&locale=en&layout=compact" alt="Top Languages">
  </div>

  <h2>🚀 Let's Connect and Build Something Great!</h2>

</body>
</html>
