# 👋 Hello, I'm <span id="typed-text"></span><span id="cursor"></span>

<img src="https://avatars.githubusercontent.com/u/your_github_username?v=4" alt="Ritik Rawal's Avatar" width="200" height="200" />

**I'm a 2nd year student pursuing B.tech CSE AIML from Brainware University.**

💻 **Technology Stack:**
- JavaScript
- C++
- Bootstrap
- Heroku
- Node.js
- React
- MongoDB
- MySQL
- Git

🌱 **I'm currently working on:**
- MERN Stack Web Development
- Data Structures and Algorithms skills

🌟 **GitHub Stats:**

![Ritik Rawal's GitHub Stats](https://github-readme-stats.vercel.app/api?username=your_github_username&show_icons=true&theme=radical)

💬 **Ask me about:**
- Web Development
- Data Structures and Algorithms
- Mentoring

✉️ **How to reach me:**
- Email: [iaamsougata@gmail.com]
- LinkedIn: [www.linkedin.com/in/sougata-mandal-51a55824b]

📚 **Certifications:**
- Developer Program Member (PRO)

<p align="center">
  <a href="https://github.com/ryo-ma/github-profile-trophy">
    <img src="https://github-profile-trophy.vercel.app/?username=SougataXdev&theme=radical" alt="Ritik Rawal's Trophies" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/SougataXdev">
    <img src="https://komarev.com/ghpvc/?username=SougataXdev&label=Profile%20views&color=0e75b6&style=flat" alt="Profile Views" />
  </a>
  <a href="https://github.com/SougataXdev?tab=repositories&sort=stars">
    <img src="https://img.shields.io/github/stars/SougataXdev?style=social" alt="GitHub Stars" />
  </a>
</p>

<script>
  // List of strings to display
  const strings = ["Sougata Mandal"];

  // Index of the string to display
  let i = 0;

  // Speed of typing (milliseconds)
  const speed = 150;

  // Function to simulate typing
  function typeWriter() {
    if (i < strings[0].length) {
      document.getElementById("typed-text").innerHTML += strings[0].charAt(i);
      i++;
      setTimeout(typeWriter, speed);
    }
  }

  // Start typing when page loads
  window.onload = function() {
    typeWriter();
  };
</script>

<style>
  /* Styling for the cursor */
  #cursor {
    display: inline-block;
    width: 8px;
    height: 20px;
    background-color: #000;
    animation: blink 0.8s infinite;
  }

  /* Blink animation for the cursor */
  @keyframes blink {
    50% {
      opacity: 0;
    }
  }
</style>
