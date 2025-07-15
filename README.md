import React from "react";

export default function ResumeWebsite() {
  return (
    <main className="min-h-screen bg-white text-gray-900 font-sans p-8">
      <section className="max-w-4xl mx-auto">
        <header className="text-center mb-8">
          <h1 className="text-4xl font-bold">Atharva Sandip Joshi</h1>
          <p className="mt-2">Mumbai, India · <a className="text-blue-600" href="mailto:atharvajoshi2520@gmail.com">atharvajoshi2520@gmail.com</a></p>
          <p>
            <a href="https://linkedin.com/in/atharva20" className="text-blue-600">LinkedIn</a> | 
            <a href="https://github.com/atharva20-coder" className="text-blue-600"> GitHub</a>
          </p>
        </header>

        <Section title="✨ Summary">
          <p>
            Engineer with a strong foundation in full-stack development, real-time embedded systems, and applied ML. Built and deployed tools in AI diagnostics, automation, and social media. Solved 255+ LeetCode problems and currently mentoring beginners via YouTube to clarify core DSA concepts.
          </p>
        </Section>

        <Section title="💼 Experience">
          <Experience
            role="Web Developer"
            company="MechHelp, Nagpur"
            duration="Sept 2024 – March 2025"
            bullets={[
              "Developed and deployed the official company website with Firebase integration.",
              "Automated deployment workflows using Git and shell scripts, reducing manual updates by 80%."
            ]}
          />
          <Experience
            role="Research Intern"
            company="RCOEM, Nagpur"
            duration="Dec 2023 – May 2024"
            bullets={[
              "Built and deployed PyTorch-based leaf disease classifier with Django web UI.",
              "Achieved 94%+ classification accuracy using MobileNetV2 and real-time inference."
            ]}
          />
        </Section>

        <Section title="💡 Skills">
          <Skill title="Languages" items={["Java", "Python", "C++", "SQL", "JavaScript"]} />
          <Skill title="Web/Backend" items={["Next.js", "Django", "Node.js", "Prisma", "Firebase"]} />
          <Skill title="AI/ML" items={["PyTorch", "TensorFlow", "Keras", "OpenCV"]} />
          <Skill title="Databases" items={["MySQL", "PostgreSQL", "Firebase"]} />
          <Skill title="Systems & Tools" items={["Embedded C", "Arduino", "Multithreading", "Git", "Docker"]} />
        </Section>

        <Section title="📚 Projects">
          <Project
            title="Swoopin – AI-Powered Social Media Automation Tool"
            link="https://swoopin.vercel.app"
            bullets={[
              "Built a full-stack SaaS integrating OpenAI and Instagram APIs to automate content workflows.",
              "Integrated Stripe billing and caching to reduce latency by 40%."
            ]}
          />
          <Project
            title="CyberGrid Guardian – Real-Time Fault Monitoring"
            link="https://github.com/atharva20-coder/cyberGrid"
            bullets={[
              "Java Swing app to monitor SPI data from Arduino sensors and visualize anomalies.",
              "Stored logs in MySQL using JDBC and visualized via jFreeChart."
            ]}
          />
          <Project
            title="Apple Leaf Disease Classifier"
            link="https://colab.research.google.com/drive/172facR1dMm7p9kZMLFWLLiNpj-mZDgsh"
            bullets={[
              "Trained MobileNetV2 model for 94%+ accurate disease classification.",
              "Deployed with Django for real-time inference UI."
            ]}
          />
          <Project
            title="SolAlign – Solar Tilt Calculator"
            link="https://devatharvajoshi.vercel.app/solalign"
            bullets={[
              "Android app for computing solar panel tilt using GPS and seasonal factors.",
              "Used by field engineers in 4+ districts."
            ]}
          />
        </Section>

        <Section title="🎓 Education">
          <p>
            <strong>B.Tech – Electrical Engineering</strong>  
            <br/>Shri Ramdeobaba College of Engineering, Nagpur  
            <br/>Graduated: May 2024 | CGPA: 9.66 / 10 (Dean’s Topper)
          </p>
        </Section>

        <Section title="🏆 Achievements">
          <ul className="list-disc list-inside">
            <li>Solved 255+ LeetCode problems in Trees, Graphs, and DP.</li>
            <li>Created a YouTube channel teaching DSA to beginners.</li>
            <li>Dean’s Scholar 4 years in a row.</li>
            <li>Selected for state-level tech exhibitions (AI, automation).</li>
          </ul>
        </Section>

        <Section title="📖 Certifications">
          <ul className="list-disc list-inside">
            <li>TensorFlow for Deep Learning – Google/Udacity</li>
            <li>Cloud App Dev with Node.js and React – IBM</li>
            <li>Data Analysis Fundamentals – LT EduTech</li>
          </ul>
        </Section>
      </section>
    </main>
  );
}

function Section({ title, children }) {
  return (
    <div className="mb-8">
      <h2 className="text-xl font-semibold border-b border-gray-300 pb-1 mb-2">{title}</h2>
      {children}
    </div>
  );
}

function Experience({ role, company, duration, bullets }) {
  return (
    <div className="mb-4">
      <h3 className="font-bold">{role} – {company}</h3>
      <p className="text-sm italic mb-1">{duration}</p>
      <ul className="list-disc list-inside text-sm">
        {bullets.map((b, i) => <li key={i}>{b}</li>)}
      </ul>
    </div>
  );
}

function Skill({ title, items }) {
  return (
    <p><strong>{title}:</strong> {items.join(", ")}</p>
  );
}

function Project({ title, link, bullets }) {
  return (
    <div className="mb-4">
      <a href={link} target="_blank" rel="noopener noreferrer" className="text-blue-600 font-bold">{title}</a>
      <ul className="list-disc list-inside text-sm">
        {bullets.map((b, i) => <li key={i}>{b}</li>)}
      </ul>
    </div>
  );
}
