<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfolio - IT Theme</title>
  <link rel="stylesheet" href="style.css" />
  <!-- Link ke font dan ikon -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>
  <!-- Background Animasi -->
  <div class="animated-bg"></div>

  <nav>
    <button onclick="showPage('home')"><i class="fas fa-home"></i> Home</button>
    <button onclick="showPage('about')"><i class="fas fa-user"></i> About Me</button>
    <button onclick="showPage('experience')"><i class="fas fa-briefcase"></i> Experience</button>
    <button onclick="showPage('education')"><i class="fas fa-graduation-cap"></i> Education</button>
    <button onclick="showPage('certificate')"><i class="fas fa-certificate"></i> Certificates</button>
    <button onclick="showPage('contact')"><i class="fas fa-envelope"></i> Contact</button>
  </nav>

  <div id="home" class="page active">
    <h1>Hi, I am <span class="highlight">[Your Name]</span></h1>
    <img src="your-photo.jpg" alt="Your Photo" class="profile-photo" />
    <p>Welcome to my portfolio!</p>
    <div class="icons">
      <i class="fab fa-html5"></i>
      <i class="fab fa-css3-alt"></i>
      <i class="fab fa-js"></i>
      <i class="fab fa-python"></i>
      <i class="fab fa-node-js"></i>
    </div>
  </div>

  <div id="about" class="page">
    <h1>About Me</h1>
    <p>I am passionate about technology and always eager to learn new skills.</p>
  </div>

  <div id="experience" class="page">
    <h1>Experience</h1>
    <p>I have worked in several IT projects, including web development, software engineering, and more.</p>
  </div>

  <div id="education" class="page">
    <h1>Education History</h1>
    <p>I graduated with a degree in Computer Science and specialized in web and software development.</p>
  </div>

  <div id="certificate" class="page">
    <h1>My Certificates</h1>
    <p>Certified in various IT skills such as JavaScript, Python, and Cloud Computing.</p>
  </div>

  <div id="contact" class="page">
    <h1>Contact Information</h1>
    <p>Email: <a href="mailto:your-email@example.com">your-email@example.com</a></p>
    <p>Phone: +1234567890</p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/yourprofile" target="_blank">https://www.linkedin.com/in/yourprofile</a></p>
  </div>

  <script src="script.js"></script>
</body>
</html>
