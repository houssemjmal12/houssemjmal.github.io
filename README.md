<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Houssem Jmal | AI Research Scientist and Engineer</title>
<meta name="description" content="Houssem Jmal is an AI Research Scientist and Engineer and PhD candidate at Nantes Université / Inria, working on federated learning, network security and foundation models.">
<meta name="author" content="Houssem Jmal">
<meta property="og:title" content="Houssem Jmal | AI Research Scientist and Engineer">
<meta property="og:description" content="Federated learning, trustworthy AI and foundation models. PhD candidate at Nantes Université / Inria.">
<meta property="og:type" content="website">
<meta property="og:image" content="https://houssemjmal12.github.io/photo.jpg">
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Person",
  "name": "Houssem Jmal",
  "jobTitle": "AI Research Scientist and Engineer",
  "affiliation": { "@type": "Organization", "name": "Nantes Université / Inria" },
  "knowsAbout": ["Federated Learning", "Network Security", "Reinforcement Learning", "Vision-Language Models", "Machine Learning"],
  "sameAs": [
    "https://github.com/H0uss",
    "https://www.linkedin.com/in/houssem-jmal-735123211/",
    "https://scholar.google.com/citations?user=oTLPP4YAAAAJ&hl=en"
  ]
}
</script>
<style>
:root{
  --bg:#ffffff; --bg2:#f4f7fb; --text:#1c2733; --muted:#5a6978; --navy:#1b2f4e;
  --blue:#1f5fa8; --blue-soft:#e6eef8; --line:#dbe3ec; --card:#ffffff;
  --shadow:0 1px 2px rgba(20,40,70,.06),0 6px 20px rgba(20,40,70,.06);
}
@media (prefers-color-scheme: dark){
  :root{
    --bg:#0e1621; --bg2:#121d2b; --text:#e4ebf3; --muted:#9aabbd; --navy:#e4ebf3;
    --blue:#6aa8ee; --blue-soft:#1a2a40; --line:#243449; --card:#142133;
    --shadow:0 1px 2px rgba(0,0,0,.3),0 6px 20px rgba(0,0,0,.25);
  }
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  margin:0; background:var(--bg); color:var(--text);
  font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif;
  line-height:1.6; font-size:16px;
}
a{color:var(--blue); text-decoration:none}
a:hover{text-decoration:underline}
.wrap{max-width:960px; margin:0 auto; padding:0 24px}

/* nav */
header.nav{
  position:sticky; top:0; z-index:10; background:color-mix(in srgb,var(--bg) 88%,transparent);
  backdrop-filter:blur(8px); border-bottom:1px solid var(--line);
}
.nav .wrap{display:flex; align-items:center; justify-content:space-between; height:56px}
.nav .brand{font-weight:700; color:var(--navy)}
.nav ul{display:flex; gap:20px; list-style:none; margin:0; padding:0; font-size:14px}
.nav ul a{color:var(--muted)}
.nav ul a:hover{color:var(--blue); text-decoration:none}
@media (max-width:640px){ .nav ul{display:none} }

/* hero */
.hero{padding:72px 0 56px; background:linear-gradient(180deg,var(--bg2),var(--bg))}
.hero .eyebrow{color:var(--blue); font-weight:600; font-size:14px; letter-spacing:.04em; text-transform:uppercase}
.hero h1{font-size:clamp(34px,6vw,52px); line-height:1.1; margin:8px 0 12px; color:var(--navy)}
.hero p.lead{font-size:19px; color:var(--muted); max-width:680px; margin:0 0 28px}
.btns{display:flex; flex-wrap:wrap; gap:10px}
.btn{
  display:inline-block; padding:10px 18px; border-radius:8px; font-weight:600; font-size:15px;
  border:1px solid var(--blue); color:var(--blue); background:transparent;
}
.btn.primary{background:var(--blue); color:#fff}
.btn:hover{text-decoration:none; filter:brightness(1.08)}
.meta{margin-top:22px; color:var(--muted); font-size:14px}

.hero .hero-grid{display:flex; align-items:center; justify-content:space-between; gap:40px}
.hero .hero-text{flex:1; min-width:0}
.hero .photo{
  width:200px; height:200px; border-radius:50%; object-fit:cover; flex:none;
  border:4px solid var(--card); box-shadow:var(--shadow);
}
@media (max-width:720px){
  .hero .hero-grid{flex-direction:column-reverse; align-items:flex-start; gap:24px}
  .hero .photo{width:128px; height:128px}
}

/* sections */
section{padding:56px 0; border-top:1px solid var(--line)}
section h2{font-size:26px; margin:0 0 24px; color:var(--navy)}
section h2::after{content:""; display:block; width:44px; height:3px; background:var(--blue); margin-top:8px; border-radius:2px}
.grid{display:grid; gap:16px; grid-template-columns:repeat(auto-fit,minmax(280px,1fr))}
.grid.two{grid-template-columns:repeat(auto-fit,minmax(min(100%,400px),1fr))}
.card{
  background:var(--card); border:1px solid var(--line); border-radius:12px; padding:20px; box-shadow:var(--shadow);
}
.card h3{margin:0 0 6px; font-size:17px; color:var(--navy)}
.card p{margin:0; color:var(--muted); font-size:15px}
.tags{display:flex; flex-wrap:wrap; gap:6px; margin-top:12px}
.tag{background:var(--blue-soft); color:var(--blue); font-size:12.5px; padding:3px 9px; border-radius:999px; font-weight:500}

/* timeline */
.tl{list-style:none; margin:0; padding:0; border-left:2px solid var(--line)}
.tl li{position:relative; padding:0 0 28px 24px}
.tl li::before{
  content:""; position:absolute; left:-7px; top:6px; width:12px; height:12px; border-radius:50%;
  background:var(--blue); border:2px solid var(--bg);
}
.tl .when{font-size:13px; color:var(--muted); font-weight:600}
.tl h3{margin:2px 0 0; font-size:17px; color:var(--navy)}
.tl .org{color:var(--muted); font-size:15px}
.tl p{margin:6px 0 0; font-size:15px}

/* skills */
.skills{display:grid; gap:14px}
.skill-row{display:grid; grid-template-columns:230px 1fr; gap:12px; align-items:start}
.skill-row strong{color:var(--navy); font-size:15px}
.skill-row span{color:var(--text); font-size:15px}
@media (max-width:640px){ .skill-row{grid-template-columns:1fr; gap:2px} }

.pubs{display:flex; flex-wrap:wrap; gap:8px}
.pub{border:1px solid var(--line); border-radius:8px; padding:8px 14px; background:var(--card); font-size:14.5px}

footer{border-top:1px solid var(--line); padding:28px 0 40px; color:var(--muted); font-size:14px}
footer .wrap{display:flex; flex-wrap:wrap; gap:12px; justify-content:space-between}
</style>
</head>
<body>

<header class="nav">
  <div class="wrap">
    <a class="brand" href="#top">Houssem Jmal</a>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#research">Research</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#experience">Experience</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#education">Education</a></li>
    </ul>
  </div>
</header>

<main id="top">
<div class="hero">
  <div class="wrap">
   <div class="hero-grid">
    <div class="hero-text">
    <div class="eyebrow">AI Research Scientist &amp; Engineer</div>
    <h1>Houssem Jmal</h1>
    <p class="lead">PhD candidate at Nantes Université / Inria. I build federated, secure and trustworthy machine learning systems, from algorithms with convergence guarantees to cloud deployment.</p>
    <div class="btns">
      <a class="btn primary" href="Houssem_Jmal_CV.pdf">Download CV (PDF)</a>
      <a class="btn" href="https://scholar.google.com/citations?user=oTLPP4YAAAAJ&amp;hl=en">Google Scholar</a>
      <a class="btn" href="https://github.com/H0uss">GitHub</a>
      <a class="btn" href="https://www.linkedin.com/in/houssem-jmal-735123211/">LinkedIn</a>
      <a class="btn" href="mailto:houssem.jmal@univ-nantes.fr">Email</a>
    </div>
    <div class="meta">Paris, France · Defense expected January 2027 · Open to AI Scientist, AI Engineer and Data Scientist roles</div>
    </div>
    <img class="photo" src="photo.jpg" alt="Portrait of Houssem Jmal" width="200" height="200">
   </div>
  </div>
</div>

<section id="about">
  <div class="wrap">
    <h2>About</h2>
    <p>I am an AI Research Scientist and Engineer, currently a PhD candidate at Nantes Université / Inria (LS2N laboratory, STACK team), with a defense planned for January 2027. My published research covers federated learning and network security, and I have hands-on experience in end-to-end ML development and cloud deployment.</p>
    <p>My work spans federated intrusion detection on non-IID data, client selection with offline reinforcement learning, free-rider detection, and multimodal phishing detection with vision-language models. I also run Mycelia &amp; Rays, a part-time project that applies LLMs and hybrid search to medical document libraries.</p>
  </div>
</section>

<section id="research">
  <div class="wrap">
    <h2>Research</h2>
    <div class="grid two">
      <div class="card">
        <h3>Federated intrusion detection</h3>
        <p>Distributed deep learning optimization algorithms for intrusion detection on non-IID network traffic, improving convergence rate and detection accuracy, with theoretical convergence guarantees.</p>
        <div class="tags"><span class="tag">Federated learning</span><span class="tag">IDS</span><span class="tag">Optimization</span></div>
      </div>
      <div class="card">
        <h3>Client selection with offline RL</h3>
        <p>A Decision Transformer-based client selection framework that reduces computation and communication time, extended with an MLOps lifecycle driven by a trajectory-diversity trigger for data shift.</p>
        <div class="tags"><span class="tag">Decision Transformer</span><span class="tag">Offline RL</span><span class="tag">MLOps</span></div>
      </div>
      <div class="card">
        <h3>Free-rider detection</h3>
        <p>A gradient-sensitivity-based out-of-distribution detection method, and statistical tests applied during critical learning periods that measure dependence, innovation and effort of client updates.</p>
        <div class="tags"><span class="tag">OOD detection</span><span class="tag">Statistical tests</span><span class="tag">Trustworthy AI</span></div>
      </div>
      <div class="card">
        <h3>Multimodal phishing detection</h3>
        <p>A framework combining URL features, HTML DOM parsing and webpage screenshots analyzed with VLMs (Qwen2-VL, SmolVLM-Instruct, Llama-3.2-11B-Vision-Instruct), fine-tuned with PEFT under federated learning.</p>
        <div class="tags"><span class="tag">VLMs</span><span class="tag">PEFT</span><span class="tag">Federated learning</span></div>
      </div>
    </div>

    <h3 style="margin:36px 0 12px;color:var(--navy);font-size:18px">Publications</h3>
    <div class="pubs">
      <span class="pub">IEEE INFOCOM</span>
      <span class="pub">IEEE MSWiM</span>
      <span class="pub">IEEE CCNC</span>
      <span class="pub">Internet of Things Journal</span>
      <span class="pub">IEEE Transactions on Information Forensics and Security (TIFS)</span>
    </div>
    <p style="margin-top:14px">The full list is on <a href="https://scholar.google.com/citations?user=oTLPP4YAAAAJ&amp;hl=en">Google Scholar</a>.</p>
  </div>
</section>

<section id="projects">
  <div class="wrap">
    <h2>Projects</h2>
    <div class="grid two">
      <div class="card">
        <h3><a href="https://myceliandrays.com/">Mycelia &amp; Rays</a></h3>
        <p>AI radiology library platform. An LLM-powered medical document processing pipeline (FastAPI, OCR, prompt chaining) for classification, tagging and organization, plus hybrid semantic and keyword search with ChromaDB and PostgreSQL/pgvector on Google Cloud, enabling source-grounded quiz generation.</p>
        <div class="tags"><span class="tag">LLMs</span><span class="tag">Hybrid search</span><span class="tag">GCP</span></div>
      </div>
      <div class="card">
        <h3><a href="https://di4spds.eu/">Di4SPDS</a></h3>
        <p>A European research project on distributed intelligence for the security and privacy of decentralised systems, in which I contributed to federated-learning-based collaborative intrusion detection.</p>
        <div class="tags"><span class="tag">Federated learning</span><span class="tag">Security</span></div>
      </div>
    </div>
  </div>
</section>

<section id="experience">
  <div class="wrap">
    <h2>Experience</h2>
    <ul class="tl">
      <li>
        <div class="when">Apr. 2024 – Jan. 2027</div>
        <h3>PhD Researcher, Machine Learning</h3>
        <div class="org">Nantes Université, LS2N Laboratory (STACK Team, Inria) · Nantes, France</div>
        <p>Federated learning for the security and privacy of decentralized systems.</p>
      </li>
      <li>
        <div class="when">May 2026 – Present (part-time)</div>
        <h3>Founder, AI Radiology Library Platform</h3>
        <div class="org"><a href="https://myceliandrays.com/">Mycelia &amp; Rays</a></div>
        <p>LLM document pipeline and hybrid search on Google Cloud.</p>
      </li>
      <li>
        <div class="when">Apr. 2025 – Jul. 2025</div>
        <h3>Visiting Researcher, Federated Learning &amp; Reinforcement Learning</h3>
        <div class="org">National Institute of Informatics (NII) · Tokyo, Japan</div>
        <p>Reinforcement learning methods (PPO, DQN, Decision Transformers) for adaptive client selection and non-IID heterogeneity.</p>
      </li>
      <li>
        <div class="when">Jan. 2024 – Apr. 2024</div>
        <h3>Research Engineer, Federated Learning</h3>
        <div class="org">IMT Atlantique · Nantes, France</div>
        <p>Experimental framework for federated learning research on the Grid5000 testbed.</p>
      </li>
      <li>
        <div class="when">Mar. 2023 – Aug. 2023</div>
        <h3>Data Science &amp; NLP Intern</h3>
        <div class="org">Athena Experts · Tunis, Tunisia</div>
        <p>Web scraping and NLP to detect personally identifiable information (PII) leaks.</p>
      </li>
      <li>
        <div class="when">Oct. 2022 – Jun. 2023</div>
        <h3>AI Researcher</h3>
        <div class="org">Ditno INC · Remote</div>
        <p>Graph Neural Networks for automated threat mitigation with firewall rules and Zero-Trust policies.</p>
      </li>
    </ul>
  </div>
</section>

<section id="skills">
  <div class="wrap">
    <h2>Skills</h2>
    <div class="skills">
      <div class="skill-row"><strong>Federated &amp; Distributed Learning</strong><span>Flower, PyTorch, non-IID data heterogeneity, client selection, free-rider &amp; out-of-distribution (OOD) detection, HPC (Grid5000)</span></div>
      <div class="skill-row"><strong>Foundation Models &amp; Post-Training</strong><span>LLMs, VLMs (Qwen2-VL, Llama-3.2-Vision), PEFT (LoRA/QLoRA), instruction tuning, distillation &amp; quantization, RAG, embeddings &amp; vector search (ChromaDB, pgvector), LLM guardrails, agentic AI (MCP, LangChain)</span></div>
      <div class="skill-row"><strong>Deep &amp; Reinforcement Learning</strong><span>Transformers, Decision Transformers, offline RL, PPO, DQN, GNNs, Diffusion Models, NLP</span></div>
      <div class="skill-row"><strong>Trustworthy AI &amp; Security</strong><span>Differential privacy, adversarial robustness, uncertainty quantification, explainable AI (XAI), intrusion detection (IDS), threat modeling</span></div>
      <div class="skill-row"><strong>Engineering &amp; MLOps</strong><span>Python, SQL, PyTorch, TensorFlow, Hugging Face, FastAPI, Docker, Google Cloud Platform (Cloud Run, BigQuery), CI/CD, MLflow, Git</span></div>
      <div class="skill-row"><strong>Certification</strong><span><a href="https://www.credly.com/badges/0ab70808-49cf-46ac-b40b-954600c6996c/public_url">Google Cloud Machine Learning Professional</a></span></div>
      <div class="skill-row"><strong>Languages</strong><span>French (fluent), English (fluent), Arabic (native)</span></div>
    </div>
  </div>
</section>

<section id="education">
  <div class="wrap">
    <h2>Education</h2>
    <ul class="tl">
      <li>
        <div class="when">Apr. 2024 – Jan. 2027 (expected)</div>
        <h3>PhD, Federated Learning for Enhancing the Security and Privacy of Decentralized Systems</h3>
        <div class="org">Nantes Université, LS2N Laboratory (STACK Team, Inria) · Nantes, France</div>
      </li>
      <li>
        <div class="when">Sep. 2020 – Sep. 2023</div>
        <h3>Engineering Degree, Specialization in Signals and Systems Processing</h3>
        <div class="org">Ecole Polytechnique de Tunisie · Tunis, Tunisia</div>
        <p>Machine learning, deep learning, optimization, probability &amp; statistics, mathematical modeling.</p>
      </li>
    </ul>
  </div>
</section>
</main>

<footer>
  <div class="wrap">
    <span>© <span id="yr">2026</span> Houssem Jmal</span>
    <span>
      <a href="https://github.com/H0uss">GitHub</a> ·
      <a href="https://www.linkedin.com/in/houssem-jmal-735123211/">LinkedIn</a> ·
      <a href="https://scholar.google.com/citations?user=oTLPP4YAAAAJ&amp;hl=en">Google Scholar</a> ·
      <a href="mailto:houssem.jmal@univ-nantes.fr">Email</a>
    </span>
  </div>
</footer>
<script>document.getElementById('yr').textContent = new Date().getFullYear();</script>
</body>
</html>
