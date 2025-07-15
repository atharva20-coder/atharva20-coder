<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Atharva Sandip Joshi - Resume</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      padding: 2rem;
      background-color: white;
      color: #1a202c;
    }
    .container {
      max-width: 800px;
      margin: 0 auto;
      position: relative;
    }
    header {
      text-align: center;
      margin-bottom: 2rem;
    }
    h1 {
      font-size: 2.5rem;
      font-weight: bold;
    }
    section {
      margin-bottom: 2rem;
    }
    h2 {
      font-size: 1.25rem;
      font-weight: 600;
      border-bottom: 1px solid #ccc;
      padding-bottom: 0.25rem;
      margin-bottom: 0.5rem;
    }
    h3 {
      font-weight: bold;
    }
    .italic {
      font-style: italic;
    }
    .list {
      list-style-type: disc;
      padding-left: 1.25rem;
      font-size: 0.95rem;
    }
    a {
      color: #2563eb;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    p, li {
      margin-bottom: 0.5rem;
    }
    #downloadBtn {
      position: absolute;
      top: 1rem;
      right: 1rem;
      padding: 0.5rem 1.5rem;
      background-color: #6b7280;
      color: white;
      font-weight: bold;
      border: none;
      border-radius: 9999px;
      cursor: pointer;
    }
    #downloadBtn:hover {
      background-color: #4b5563;
    }
  </style>
</head>
<body>
  <main class="container" id="resumeContent">
    <button id="downloadBtn">Download as PDF</button>
    <header>
      <h1>Atharva Sandip Joshi</h1>
      <p>Mumbai, India · <a href="mailto:atharvajoshi2520@gmail.com">atharvajoshi2520@gmail.com</a></p>
      <p><a href="https://linkedin.com/in/atharva20">LinkedIn</a> | <a href="https://github.com/atharva20-coder">GitHub</a></p>
    </header>

    <section>
      <h2>✨ Summary</h2>
      <p>
        Engineer with a strong foundation in full-stack development, real-time embedded systems, and applied ML. Built and deployed tools in AI diagnostics, automation, and social media. Solved 255+ LeetCode problems and currently mentoring beginners via YouTube to clarify core DSA concepts.
      </p>
    </section>

    <section>
      <h2>💼 Experience</h2>
      <div>
        <h3>Web Developer – MechHelp, Nagpur</h3>
        <p class="italic">Sept 2024 – March 2025</p>
        <ul class="list">
          <li>Developed and deployed the official company website with Firebase integration.</li>
          <li>Automated deployment workflows using Git and shell scripts, reducing manual updates by 80%.</li>
        </ul>
      </div>
      <div>
        <h3>Research Intern – RCOEM, Nagpur</h3>
        <p class="italic">Dec 2023 – May 2024</p>
        <ul class="list">
          <li>Built and deployed PyTorch-based leaf disease classifier with Django web UI.</li>
          <li>Achieved 94%+ classification accuracy using MobileNetV2 and real-time inference.</li>
        </ul>
      </div>
    </section>

    <section>
      <h2>💡 Skills</h2>
      <p><strong>Languages:</strong> Java, Python, C++, SQL, JavaScript</p>
      <p><strong>Web/Backend:</strong> Next.js, Django, Node.js, Prisma, Firebase</p>
      <p><strong>AI/ML:</strong> PyTorch, TensorFlow, Keras, OpenCV</p>
      <p><strong>Databases:</strong> MySQL, PostgreSQL, Firebase</p>
      <p><strong>Systems & Tools:</strong> Embedded C, Arduino, Multithreading, Git, Docker</p>
    </section>

    <section>
      <h2>📚 Projects</h2>
      <div>
        <a href="https://swoopin.vercel.app" target="_blank"><strong>Swoopin – AI-Powered Social Media Automation Tool</strong></a>
        <ul class="list">
          <li>Built a full-stack SaaS integrating OpenAI and Instagram APIs to automate content workflows.</li>
          <li>Integrated Stripe billing and caching to reduce latency by 40%.</li>
        </ul>
      </div>
      <div>
        <a href="https://github.com/atharva20-coder/cyberGrid" target="_blank"><strong>CyberGrid Guardian – Real-Time Fault Monitoring</strong></a>
        <ul class="list">
          <li>Java Swing app to monitor SPI data from Arduino sensors and visualize anomalies.</li>
          <li>Stored logs in MySQL using JDBC and visualized via jFreeChart.</li>
        </ul>
      </div>
      <div>
        <a href="https://colab.research.google.com/drive/172facR1dMm7p9kZMLFWLLiNpj-mZDgsh" target="_blank"><strong>Apple Leaf Disease Classifier</strong></a>
        <ul class="list">
          <li>Trained MobileNetV2 model for 94%+ accurate disease classification.</li>
          <li>Deployed with Django for real-time inference UI.</li>
        </ul>
      </div>
      <div>
        <a href="https://devatharvajoshi.vercel.app/solalign" target="_blank"><strong>SolAlign – Solar Tilt Calculator</strong></a>
        <ul class="list">
          <li>Android app for computing solar panel tilt using GPS and seasonal factors.</li>
          <li>Used by field engineers in 4+ districts.</li>
        </ul>
      </div>
    </section>

    <section>
      <h2>🎓 Education</h2>
      <p>
        <strong>B.Tech – Electrical Engineering</strong><br />
        Shri Ramdeobaba College of Engineering, Nagpur<br />
        Graduated: May 2024 | CGPA: 9.66 / 10 (Dean’s Topper)
      </p>
    </section>

    <section>
      <h2>🏆 Achievements</h2>
      <ul class="list">
        <li>Solved 255+ LeetCode problems in Trees, Graphs, and DP.</li>
        <li>Created a YouTube channel teaching DSA to beginners.</li>
        <li>Dean’s Scholar 4 years in a row.</li>
        <li>Selected for state-level tech exhibitions (AI, automation).</li>
      </ul>
    </section>

    <section>
      <h2>📖 Certifications</h2>
      <ul class="list">
        <li>TensorFlow for Deep Learning – Google/Udacity</li>
        <li>Cloud App Dev with Node.js and React – IBM</li>
        <li>Data Analysis Fundamentals – LT EduTech</li>
      </ul>
    </section>
  </main>

  <script src="https://cdnjs.cloudflare.com/ajax/libs/html2pdf.js/0.10.1/html2pdf.bundle.min.js"></script>
  <script>
    document.getElementById("downloadBtn").addEventListener("click", function () {
      const element = document.body; // Capture full body instead of just resumeContent
      const opt = {
        margin: 0.2,
        filename: "Atharva_Joshi_Resume.pdf",
        image: { type: "jpeg", quality: 0.98 },
        html2canvas: { scale: 2, useCORS: true },
        jsPDF: { unit: "in", format: "a4", orientation: "portrait" }
      };
      html2pdf().set(opt).from(element).save();
    });
  </script>
</body>
</html>
