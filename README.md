
<style>
@import url('https://fonts.googleapis.com/css2?family=Cinzel:wght@500;600;700;800&family=Inter:wght@400;500;600;700&family=IM+Fell+English:ital@0;1&display=swap');

:root {
  --ink: #101411;
  --panel: #191e19;
  --gold: #d7aa60;
  --bright: #f2cf8b;
  --paper: #f0dfbd;
  --muted: #bcb6a6;
}

body {
  background: var(--ink) !important;
  color: #eee5d1 !important;
  font-family: Inter, sans-serif !important;
}
header, footer, .view { display: none !important; }
.wrapper, section, #main_content {
  max-width: 1100px !important;
}
#main_content {
  padding: 0 !important;
  border: 0 !important;
  background: transparent !important;
}
a { color: var(--bright); }
a:hover { color: white; }

.dragon { max-width: 1100px; margin: auto; }
.hero {
  text-align: center;
  padding: 60px 22px;
  border: 1px solid #705632;
  border-radius: 14px;
  background:
    radial-gradient(ellipse at 50% 0%, #654425, transparent 68%),
    linear-gradient(145deg, #20251e, #0c100e 75%);
}
.crest {
  color: var(--gold);
  font-size: 56px;
  text-shadow: 0 0 25px #a66a28;
}
.eyebrow {
  color: var(--gold);
  font-size: 11px;
  letter-spacing: 3px;
  text-transform: uppercase;
}
.hero h1 {
  color: var(--bright) !important;
  font: 800 clamp(36px, 7vw, 66px)/1.2 Cinzel, serif !important;
  letter-spacing: 2px;
  margin: 18px 0 !important;
}
.hero p { max-width: 680px; margin: 14px auto; line-height: 1.8; }
.motto {
  color: var(--paper);
  font: italic 21px 'IM Fell English', serif;
}
.actions, .nav {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 10px;
}
.actions { margin-top: 25px; }
.btn {
  display: inline-block;
  padding: 11px 16px;
  border: 1px solid var(--gold);
  border-radius: 5px;
  color: var(--bright) !important;
  text-decoration: none !important;
  font-size: 11px;
  letter-spacing: 1px;
}
.btn.primary {
  background: var(--gold);
  color: #17140e !important;
  font-weight: 700;
}
.nav {
  padding: 22px 8px;
  border-bottom: 1px solid #54452e;
  margin-bottom: 26px;
  gap: 12px 22px;
}
.nav a { color: var(--paper); font-size: 12px; text-decoration: none; }
.chapter {
  margin: 26px 0;
  padding: 27px;
  border: 1px solid #665237;
  border-radius: 9px;
  background: var(--panel);
  scroll-margin-top: 20px;
}
.chapter h2 {
  color: var(--bright) !important;
  font: 600 22px Cinzel, serif !important;
  border-bottom: 1px solid #695332;
  padding-bottom: 13px;
  margin-top: 0 !important;
}
.chapter h3 { color: var(--paper) !important; font: 600 16px Cinzel, serif !important; }
.chapter p, .chapter li { font-size: 14px; line-height: 1.8; }
.gold { color: var(--bright); }
.grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 14px;
}
.card {
  padding: 19px;
  border: 1px solid #4c432f;
  border-radius: 7px;
  background: #0d110f;
}
.card h3 { margin-top: 0; }
.card p { color: var(--muted); }
.card a { font-size: 12px; }
.tag {
  display: inline-block;
  padding: 4px 9px;
  margin: 3px 3px 3px 0;
  border: 1px solid #655239;
  border-radius: 20px;
  color: var(--bright);
  font-size: 10px;
}
.skills { display: flex; flex-wrap: wrap; gap: 8px; }
.skills span {
  padding: 8px 11px;
  background: #0c100e;
  border: 1px solid #51452f;
  border-radius: 5px;
  color: var(--paper);
  font-size: 12px;
}
.timeline { border-left: 2px solid #80623a; margin-left: 8px; padding-left: 22px; }
.event { position: relative; margin: 22px 0; }
.event:before {
  content: '';
  position: absolute;
  left: -29px;
  top: 5px;
  width: 10px;
  height: 10px;
  background: var(--gold);
  border-radius: 50%;
}
.date { color: var(--gold); font-size: 11px; letter-spacing: 1px; }
.quote {
  color: var(--paper);
  text-align: center;
  font: italic 21px/1.8 'IM Fell English', serif;
  padding: 18px 8px;
}
.stats {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 10px;
  margin-top: 25px;
}
.stat { text-align: center; padding: 15px 5px; border: 1px solid #53452f; border-radius: 7px; }
.stat strong { display: block; color: var(--bright); font: 600 20px Cinzel, serif; }
.stat span { color: var(--muted); font-size: 10px; }
.contact {
  padding: 32px 18px;
  text-align: center;
  border: 1px solid var(--gold);
  border-radius: 10px;
  background: linear-gradient(145deg, #3b3020, #151813);
}
.contact h2 { color: var(--bright); font-family: Cinzel, serif; }
.footer { text-align: center; color: #aaa08a; font-size: 11px; letter-spacing: 2px; padding: 28px 8px; }
@media(max-width:620px) {
  .grid { grid-template-columns: 1fr; }
  .chapter { padding: 18px; }
  .hero { padding: 42px 14px; }
  .stats { gap: 5px; }
  .stat strong { font-size: 16px; }
  .nav { gap: 12px; }
}
</style>

<div class="dragon">

<div class="hero">
  <div class="crest">♜ 🐉 ♜</div>
  <div class="eyebrow">The Dragon's Archive · The Engineer's Chronicle</div>
  <h1>NITHISH R</h1>
  <p class="motto">"Dream beyond the horizon. Build what does not yet exist."</p>
  <p>
    AI/ML Engineer · Generative AI · Intelligent Systems
    <br>
    Exploring the frontier where research meets real-world engineering.
  </p>
  <div class="actions">
    <a class="btn primary" href="#projects">⚔ EXPLORE MY WORK</a>
    <a class="btn" href="https://github.com/nithish-ctrl">⌘ GITHUB</a>
    <a class="btn" href="https://www.linkedin.com/in/nithish-ravi/">✉ CONNECT</a>
    <a class="btn" href="/assets/Nithish_R_Resume.pdf">📜 VIEW RESUME</a>
  </div>
  <div class="stats">
    <div class="stat"><strong>AI / ML</strong><span>MY DOMAIN</span></div>
    <div class="stat"><strong>BUILD</strong><span>MY APPROACH</span></div>
    <div class="stat"><strong>∞</strong><span>MY CURIOSITY</span></div>
  </div>
</div>

<div class="nav">
  <a href="#about">CHRONICLE</a>
  <a href="#skills">ARSENAL</a>
  <a href="#experience">JOURNEY</a>
  <a href="#projects">INVENTIONS</a>
  <a href="#research">RESEARCH</a>
  <a href="#education">ORIGINS</a>
  <a href="#achievements">VICTORIES</a>
  <a href="#contact">RAVEN'S POST</a>
</div>

<div class="chapter" id="about">
<h2>📜 I. The Chronicle — About Me</h2>

<p>
Greetings, traveller. I am <strong class="gold">Nithish R</strong>,
a Computer Science and Engineering graduate from the
<strong>National Institute of Technology, Warangal</strong>.
My interests lie in machine learning, deep learning, generative AI,
computer vision, and building intelligent systems that solve
meaningful problems.
</p>

<p>
I enjoy exploring how models work beneath the surface, implementing
ideas rather than treating them as black boxes, and connecting
research concepts to practical applications. My projects span
local LLMs and AI agents, document retrieval, medical image analysis,
industrial computer vision, and data-driven fault diagnosis.
</p>

<p>
My current quest is to become a stronger research-oriented engineer:
someone who can understand a problem, study the underlying methods,
build a working system, evaluate it honestly, and communicate the
results clearly.
</p>

<div class="quote">"Curiosity lights the forge. Persistence shapes the blade."</div>
</div>

<div class="chapter" id="skills">
<h2>🛡 II. The Arsenal — Technical Skills</h2>

<h3>Programming Languages</h3>
<div class="skills">
<span>Python</span><span>C / C++</span><span>Java</span>
<span>SQL</span><span>JavaScript</span>
</div>

<h3>Machine Learning & Deep Learning</h3>
<div class="skills">
<span>PyTorch</span><span>Scikit-learn</span><span>TensorFlow</span>
<span>Neural Networks</span><span>CNNs</span><span>ResNet</span>
<span>Transformers</span><span>GANs</span><span>Model Evaluation</span>
</div>

<h3>Generative AI & Intelligent Agents</h3>
<div class="skills">
<span>LLMs</span><span>RAG</span><span>LangChain</span>
<span>LangGraph</span><span>Embeddings</span><span>ChromaDB</span>
<span>llama.cpp</span><span>Prompt Engineering</span><span>Tool Integration</span>
</div>

<h3>Computer Vision & Data</h3>
<div class="skills">
<span>OpenCV</span><span>YOLO</span><span>Image Classification</span>
<span>Data Preprocessing</span><span>Feature Engineering</span>
<span>Time-Series Analysis</span><span>Anomaly Detection</span>
</div>

<h3>Tools & Development</h3>
<div class="skills">
<span>Git</span><span>GitHub</span><span>Linux</span>
<span>VS Code</span><span>Jupyter</span><span>Google Colab</span>
<span>Streamlit</span><span>FFmpeg</span><span>REST APIs</span>
</div>
</div>

<div class="chapter" id="experience">
<h2>🏰 III. The Journey — Experience</h2>

<div class="timeline">
  <div class="event">
    <div class="date">INTERNSHIP · ADD EXACT DATES</div>
    <h3>LTTS — Engineering Intern</h3>
    <p>
      Worked with testing frameworks and computer-vision workflows
      for detecting LEDs and screws. Contributed to custom annotation
      pipelines and real-time YOLO-based inference.
    </p>
    <span class="tag">YOLO</span><span class="tag">Computer Vision</span>
    <span class="tag">Testing Frameworks</span>
  </div>

  <div class="event">
    <div class="date">RESEARCH PROJECT · ADD EXACT DATES</div>
    <h3>Medical Image Analysis — Cancer Prediction</h3>
    <p>
      Explored ResNet-based cancer prediction using density-based
      heatmap tissue images, applying deep-learning and image-analysis
      techniques with PyTorch.
    </p>
    <span class="tag">PyTorch</span><span class="tag">ResNet</span>
    <span class="tag">Medical Imaging</span>
  </div>

  <div class="event">
    <div class="date">LEADERSHIP · ADD EXACT DATES</div>
    <h3>AI/ML Club — Mentor & Organizer</h3>
    <p>
      Mentored juniors in machine learning and AI, supported project
      development and internship preparation, and helped organize
      technical activities involving 150+ participants.
    </p>
    <span class="tag">Mentorship</span><span class="tag">Leadership</span>
  </div>
</div>
</div>

<div class="chapter" id="projects">
<h2>⚗ IV. The Inventor's Guild — Featured Projects</h2>

<div class="grid">
  <div class="card">
    <h3>🐉 Multi-Tool AI Agent</h3>
    <p>
      A personal assistant built around local LLM experiments and
      LangChain/LangGraph, integrating web search, knowledge lookup,
      Obsidian notes, conversation logs, productivity tools, and
      extensible tool workflows.
    </p>
    <span class="tag">Agents</span><span class="tag">LangGraph</span>
    <span class="tag">Local LLM</span>
    <p><a href="https://github.com/nithish-ctrl">Explore my repositories ↗</a></p>
  </div>

  <div class="card">
    <h3>📚 Local LLM & RAG Experiments</h3>
    <p>
      Exploring local language models, embeddings, vector retrieval,
      and persistent conversational memory, with a focus on
      understanding retrieval quality and reliable grounded responses.
    </p>
    <span class="tag">RAG</span><span class="tag">ChromaDB</span>
    <span class="tag">llama.cpp</span>
    <p><a href="https://github.com/nithish-ctrl">Explore my repositories ↗</a></p>
  </div>

  <div class="card">
    <h3>🎬 AI Content Automation</h3>
    <p>
      A local content-generation pipeline combining language-model
      scripts, Piper text-to-speech, Whisper transcription,
      subtitle generation, FFmpeg video assembly, and an upload workflow.
    </p>
    <span class="tag">Automation</span><span class="tag">TTS</span>
    <span class="tag">Whisper</span><span class="tag">FFmpeg</span>
    <p><a href="https://github.com/nithish-ctrl">Explore my repositories ↗</a></p>
  </div>

  <div class="card">
    <h3>❄ WGAN-GP for Chiller Fault Diagnosis</h3>
    <p>
      Investigating fault- and severity-conditioned data generation
      for chiller fault diagnosis, with physics-informed constraints
      as a research direction. Final results and limitations should
      be documented alongside the implementation.
    </p>
    <span class="tag">GANs</span><span class="tag">Time Series</span>
    <span class="tag">Fault Diagnosis</span>
    <p><a href="https://github.com/nithish-ctrl">Explore my repositories ↗</a></p>
  </div>

  <div class="card">
    <h3>🧠 Transformer-Based Emotion Classification</h3>
    <p>
      A text-classification project exploring six emotion categories
      using transformer models. Add the final evaluation metrics,
      dataset details, and error analysis when publishing the project.
    </p>
    <span class="tag">NLP</span><span class="tag">Transformers</span>
    <p><a href="https://github.com/nithish-ctrl">Explore my repositories ↗</a></p>
  </div>

  <div class="card">
    <h3>📐 2D Drawing to DXF Digitization</h3>
    <p>
      Exploring computer-vision and deep-learning methods to digitize
      2D engineering drawings into DXF geometry, connecting image
      processing with practical CAD workflows.
    </p>
    <span class="tag">Computer Vision</span><span class="tag">CAD</span>
    <span class="tag">DXF</span>
    <p><a href="https://github.com/nithish-ctrl">Explore my repositories ↗</a></p>
  </div>

  <div class="card">
    <h3>⚙ IoT-Based Tool Failure Prediction</h3>
    <p>
      Applied random-forest-based anomaly detection concepts to
      equipment data for tool-failure prediction and condition
      monitoring.
    </p>
    <span class="tag">Random Forest</span><span class="tag">IoT</span>
    <span class="tag">Anomaly Detection</span>
    <p><a href="https://github.com/nithish-ctrl">Explore my repositories ↗</a></p>
  </div>

  <div class="card">
    <h3>🤖 Robotics & Kinematics — Exploration</h3>
    <p>
      Exploring forward and inverse kinematics and the possibility
      of combining visual object identification with robot motion
      planning. Update this entry as implementation progresses.
    </p>
    <span class="tag">Robotics</span><span class="tag">Kinematics</span>
    <span class="tag">Computer Vision</span>
    <p><a href="https://github.com/nithish-ctrl">Explore my repositories ↗</a></p>
  </div>
</div>

<p style="text-align:center;margin-top:24px">
  <a class="btn primary" href="https://github.com/nithish-ctrl?tab=repositories">
    EXPLORE ALL REPOSITORIES ↗
  </a>
</p>
</div>

<div class="chapter" id="research">
<h2>🔬 V. The Researcher's Observatory</h2>

<p>
I am interested in understanding methods deeply, reproducing
experiments, and studying how intelligent systems behave beyond
their headline metrics.
</p>

<div class="grid">
  <div class="card">
    <h3>01 · Physics-Informed Generative Models</h3>
    <p>
      Research direction: combining conditional synthetic data
      generation with physical constraints for industrial fault
      diagnosis.
    </p>
    <span class="tag">WGAN-GP</span><span class="tag">Physics-Informed ML</span>
  </div>

  <div class="card">
    <h3>02 · Reliable Local AI Agents</h3>
    <p>
      Research direction: exploring tool selection, retrieval,
      memory persistence, and reliable execution in local-LLM
      agent systems.
    </p>
    <span class="tag">LLMs</span><span class="tag">RAG</span>
  </div>

  <div class="card">
    <h3>03 · Vision for Engineering Automation</h3>
    <p>
      Research direction: using computer vision to bridge
      unstructured visual information and structured engineering
      representations.
    </p>
    <span class="tag">Computer Vision</span><span class="tag">CAD</span>
  </div>

  <div class="card">
    <h3>Publications & Technical Writing</h3>
    <p>
      No publication links are listed here yet. Add verified papers,
      preprints, technical reports, or reproducibility studies
      when they are ready to share.
    </p>
    <p><a href="https://github.com/nithish-ctrl">View code and experiments ↗</a></p>
  </div>
</div>

<h3>My Research Workflow</h3>
<ul>
  <li>Define the problem and study relevant literature.</li>
  <li>Establish baselines and document experimental settings.</li>
  <li>Implement, test, and measure performance using suitable metrics.</li>
  <li>Record failure cases, limitations, and reproducibility details.</li>
  <li>Share code and findings when they are ready for public release.</li>
</ul>
</div>

<div class="chapter" id="education">
<h2>🎓 VI. The Origins — Education</h2>
<div class="card">
  <div class="date">2021–2025 · VERIFY DATES</div>
  <h3>National Institute of Technology, Warangal</h3>
  <p>B.Tech — Computer Science and Engineering</p>
  <p>
    Areas of study and interest: algorithms, machine learning,
    artificial intelligence, data structures, databases, and
    software engineering.
  </p>
  <p><strong class="gold">CGPA:</strong> Add your verified CGPA if you wish to display it.</p>
</div>
</div>

<div class="chapter" id="achievements">
<h2>🏆 VII. The Hall of Victories</h2>
<ul>
  <li>Contributed to technical club activities involving 150+ participants.</li>
  <li>Built projects spanning computer vision, NLP, generative AI, and predictive analytics.</li>
  <li>Add verified hackathon placements, awards, competition rankings, or publications here.</li>
  <li>Add certifications with their official verification links.</li>
</ul>

<h3>Certifications & Learning</h3>
<ul>
  <li>Certification or course name — <a href="CERTIFICATE-URL">View certificate ↗</a></li>
  <li>Certification or course name — <a href="CERTIFICATE-URL">View certificate ↗</a></li>
</ul>
</div>

<div class="chapter">
<h2>🧭 VIII. Current Quests</h2>
<div class="grid">
  <div class="card">
    <h3>Model Mastery</h3>
    <p>Implementing ML and deep-learning architectures to understand their mathematics, strengths, and failure modes.</p>
  </div>
  <div class="card">
    <h3>Autonomous Systems</h3>
    <p>Building more capable local AI agents with dependable tools, retrieval, and memory.</p>
  </div>
  <div class="card">
    <h3>Research Engineering</h3>
    <p>Reproducing ideas, designing controlled experiments, and reporting results honestly.</p>
  </div>
  <div class="card">
    <h3>Embodied Intelligence</h3>
    <p>Exploring robotics, kinematics, and vision-guided engineering systems.</p>
  </div>
</div>
</div>

<div class="contact" id="contact">
  <div class="crest">✉</div>
  <div class="eyebrow">The Raven's Post</div>
  <h2>Every Great Quest Begins With a Conversation</h2>
  <p>
    Interested in AI/ML, research engineering, intelligent systems,
    or building something ambitious? Let's connect.
  </p>
  <div class="actions">
    <a class="btn primary" href="mailto:nithish221b@gmail.com">SEND A RAVEN ↗</a>
    <a class="btn" href="https://www.linkedin.com/in/nithish-ravi/">LINKEDIN ↗</a>
    <a class="btn" href="https://github.com/nithish-ctrl">GITHUB ↗</a>
  </div>
</div>

<div class="footer">
  DREAM · BUILD · DISCOVER · REPEAT
  <br><br>
  Forged with curiosity. Powered by code.
  <br>
  © 2026 Nithish R · THE DRAGON'S ARCHIVE
</div>

</div>
