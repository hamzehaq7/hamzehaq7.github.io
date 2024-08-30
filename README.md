<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hamzeh Abu Qamar - Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="midnight.jquery.min.css">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
      color: #333;
    }
    nav.fixed {
      position: fixed;
      width: 100%;
      background: linear-gradient(90deg, #004d7a, #008793, #00bf72, #a8eb12);
      padding: 1rem;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }
    h1, h2, h3 {
      color: #004d7a;
    }
    .container {
      width: 80%;
      margin: auto;
      overflow: hidden;
      padding: 2rem 0;
    }
    a {
      color: #008793;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
      color: #004d7a;
    }
    .project {
      background: #fff;
      margin: 1rem 0;
      padding: 1rem;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }
    footer {
      text-align: center;
      padding: 1rem 0;
      background: #333;
      color: #fff;
    }
  </style>
</head>
<body>
  <nav class="fixed">
    <h1>Hamzeh Abu Qamar - Portfolio</h1>
  </nav>

  <div class="container">
    <section>
      <h2>Welcome to my page, enjoy!</h2>
      <p>Hamzeh Abu Qamar is an Electrical Engineering graduate currently pursuing a Master's in Technology Innovation and Entrepreneurship at KAUST...</p>
      <a href="HamzehAbuQamarCV.pdf" class="btn">Download CV</a>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <div class="project">
        <h3>Probing Blood Dynamics: A Novel Piezoelectric Approach to Monitor Flow and Detect Clot Formation</h3>
        <p>The paper is currently under review (major revisions) for MDPI Sensors journal publication.</p>
      </div>
      <div class="project">
        <h3>Regional CubeSat Communication and Constellation Design Evaluation</h3>
        <p>Created a simulator of small satellite constellations... The <a href="Papers/CubeSat_IEEE ICM2023.pdf">paper</a> has been published on IEEE Xplore.</p>
      </div>
      <!-- Add more projects here -->
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <ul>
        <li>Python, AI, ML Programming</li>
        <li>Raspberry Pi & Arduino</li>
        <li>MATLAB & C++</li>
        <li>Public Speaking, Critical Thinking, Leadership</li>
        <li>Entrepreneurship, Project Management</li>
      </ul>
    </section>

    <section id="certificates">
      <h2>Certificates</h2>
      <ul>
        <li>Cisco CCNA: Introduction to Networks</li>
        <li>Google Project Management: Professional Certificate</li>
        <li>IBM Data Science (soon!)</li>
      </ul>
    </section>

    <section id="hobbies">
      <h2>Hobbies & Interests</h2>
      <ul>
        <li>Sports – bodybuilding, soccer, volleyball</li>
        <li>Reading books & online forums about business, entrepreneurship, history, and politics</li>
        <li>Traveling to experience life & get exposed to different cultures</li>
        <li>Analyzing trends & active investing in the stock market</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Email: hamzehabuqamar7@gmail.com, hamzeh.abuqamar@kaust.edu.sa</p>
      <p>Mobile Number: +971561227914, +966565116760</p>
    </section>
  </div>

  <footer>
    <p>Last Updated Sept. 1st, 2024</p>
  </footer>

  <script src="midnight.jquery.min.js"></script>
  <script>
    $(document).ready(function(){
      $('nav.fixed').midnight();
    });
  </script>
</body>
</html>
