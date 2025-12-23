<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="Professional portfolio for Cloud, DevOps, and AI" />
  <title>Cloud • DevOps • AI — Professional Profile</title>
  <style>
    :root {
      --bg: #0f1216; --bg-alt: #141922; --card: #161b26;
      --text: #e6e9ef; --muted: #9aa6b2; --primary: #4f8cff;
      --border: #223047; --accent: #22d3ee;
    }
    * { box-sizing: border-box }
    body { margin: 0; background: var(--bg); color: var(--text); font-family: system-ui, -apple-system, Segoe UI, Roboto, Inter, Arial, sans-serif; line-height: 1.6 }
    a { color: inherit; text-decoration: none }
    .container { width: min(1100px, 92vw); margin: 0 auto }
    header { border-bottom: 1px solid var(--border); }
    nav { display: flex; align-items: center; justify-content: space-between; padding: 14px 4vw }
    .brand { font-weight: 700; display: flex; align-items: center; gap: 10px }
    .brand .logo { font-size: 20px }
    .nav-links { display: flex; gap: 18px; list-style: none; margin: 0; padding: 0 }
    .nav-links a:hover { color: var(--accent) }
    .btn { display: inline-flex; align-items: center; padding: 10px 14px; border-radius: 10px; border: 1px solid var(--border); background: var(--card); color: var(--text) }
    .btn-primary { background: var(--primary); border-color: var(--primary) }
    .btn-outline { background: transparent }
    .hero { display: grid; grid-template-columns: 1.2fr .8fr; gap: 24px; align-items: center; padding: 40px 4vw }
    h1 { margin: 0 0 8px; font-size: clamp(26px, 4.5vw, 38px) }
    h2 { margin: 0 0 12px; font-size: clamp(22px, 3vw, 28px) }
    h3 { margin: 0 0 8px; font-size: 18px }
    .muted { color: var(--muted) }
    .hero-cta { display: flex; gap: 10px; margin-top: 14px }
    .avatar { display: flex; justify-content: flex-end }
    .avatar img { width: 200px; height: 200px; border-radius: 16px; object-fit: cover; border: 1px solid var(--border) }
    .section { padding: 46px 0 }
    .section.alt { background: var(--bg-alt) }
    .card { background: var(--card); border: 1px solid var(--border); border-radius: 14px; padding: 16px }
    .grid-3 { display: grid; grid-template-columns: repeat(3, 1fr); gap: 16px }
    .grid-2 { display: grid; grid-template-columns: 1fr 1fr; gap: 16px }
    .stats { list-style: none; margin: 12px 0 0; padding: 0; display: grid; grid-template-columns: repeat(3, 1fr); gap: 12px }
    .stats li { background: var(--card); border: 1px solid var(--border); border-radius: 12px; padding: 12px }
    .tags { list-style: none; padding: 0; margin: 8px 0 0; display: flex; flex-wrap: wrap; gap: 8px; color: var(--muted); font-size: 14px }
    .project { display: grid; grid-template-rows: 150px auto; overflow: hidden }
    .project img { width: 100%; height: 150px; object-fit: cover; border-bottom: 1px solid var(--border) }
    .diagram { background: var(--card); border: 1px solid var(--border); border-radius: 14px; padding: 12px }
    svg { width: 100%; height: auto; color: var(--muted) }
    .node { fill: #1e2635; stroke: #2a3953; stroke-width: 1.4 }
    .node.root { fill: #1b2333 }
    .node-text { fill: var(--text); font-size: 13px; text-anchor: middle; font-family: inherit }
    .node-text.small { font-size: 12px }
    .contact { display: grid; grid-template-columns: 1fr 1fr; gap: 16px }
    input, textarea { width: 100%; border: 1px solid var(--border); background: #0b0f15; color: var(--text); border-radius: 10px; padding: 10px; font: inherit }
    label { font-size: 14px }
    footer { border-top: 1px solid var(--border); color: var(--muted); padding: 18px 0; text-align: center }
    @media (max-width: 980px) {
      .hero { grid-template-columns: 1fr }
      .grid-3 { grid-template-columns: 1fr 1fr }
      .stats { grid-template-columns: 1fr 1fr }
      .contact { grid-template-columns: 1fr }
    }
    @media (max-width: 620px) {
      .grid-3 { grid-template-columns: 1fr }
      .stats { grid-template-columns: 1fr }
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <div class="brand"><span class="logo">☁︎</span><span>Cloud • DevOps • AI</span></div>
      <ul class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#stack">Tech tree</a></li>
        <li><a href="#contact" class="btn btn-primary">Contact</a></li>
      </ul>
    </nav>
    <section class="hero">
      <div>
        <h1>Formal professional in Cloud, DevOps, and AI</h1>
        <p class="muted">I architect scalable cloud platforms, automate delivery pipelines, and build reliable machine learning solutions for business outcomes.</p>
        <div class="hero-cta">
          <a class="btn btn-primary" href="#projects">View projects</a>
          <a class="btn btn-outline" href="#contact">Hire me</a>
        </div>
        <p class="muted">Location: Amalāpuram, AP, India • Availability: Remote & Onsite</p>
      </div>
      <div class="avatar">
        <img src="assets/img/avatar.jpg" alt="Professional headshot" />
      </div>
    </section>
  </header>

  <main>
    <section id="about" class="section">
      <div class="container">
        <h2>About</h2>
        <p>Cloud architect and DevOps/MLOps engineer experienced across AWS, Azure, GCP, Kubernetes, Terraform, Python, and modern ML tooling. I deliver secure, cost-efficient platforms and well-monitored AI systems.</p>
        <ul class="stats">
          <li><strong>Experience:</strong> 5–8 years</li>
          <li><strong>Focus:</strong> Platform engineering, SRE, MLOps</li>
          <li><strong>Certifications:</strong> AWS SA, Azure Admin, CKAD, Terraform</li>
        </ul>
      </div>
    </section>

    <section id="skills" class="section alt">
      <div class="container">
        <h2>Skills</h2>
        <div class="grid-3">
          <div class="card">
            <h3>Cloud</h3>
            <p class="muted">AWS, Azure, GCP; VPC, IAM, serverless, observability, FinOps.</p>
            <ul class="tags"><li>AWS</li><li>Azure</li><li>GCP</li><li>Serverless</li></ul>
          </div>
          <div class="card">
            <h3>DevOps</h3>
            <p class="muted">CI/CD, GitOps, Kubernetes, Docker, IaC, policy-as-code, SRE practices.</p>
            <ul class="tags"><li>Kubernetes</li><li>Docker</li><li>Terraform</li><li>GitHub Actions</li></ul>
          </div>
          <div class="card">
            <h3>AI/ML</h3>
            <p class="muted">Model training & serving, pipelines, monitoring, registries, A/B rollout.</p>
            <ul class="tags"><li>Python</li><li>PyTorch</li><li>MLflow</li><li>DataOps</li></ul>
          </div>
        </div>
      </div>
    </section>

    <section id="projects" class="section">
      <div class="container">
        <h2>Projects</h2>
        <div class="grid-3">
          <div class="card project">
            <img src="assets/img/project-cloud-1.jpg" alt="Cloud architecture" />
            <div>
              <h3>Multi-cloud platform</h3>
              <p class="muted">Portable infra across AWS/GCP with policy-as-code and FinOps dashboards.</p>
              <ul class="tags"><li>AWS</li><li>GCP</li><li>Terraform</li><li>Grafana</li></ul>
            </div>
          </div>
          <div class="card project">
            <img src="assets/img/project-ai-1.jpg" alt="ML pipeline" />
            <div>
              <h3>Scalable ML inference</h3>
              <p class="muted">Autoscaled serving, model registry, A/B rollout, end-to-end monitoring.</p>
              <ul class="tags"><li>K8s</li><li>PyTorch</li><li>Prometheus</li><li>Argo</li></ul>
            </div>
          </div>
          <div class="card project">
            <img src="assets/img/project-devops-1.jpg" alt="CI/CD pipeline" />
            <div>
              <h3>GitOps delivery</h3>
              <p class="muted">Standardized pipelines with OPA policies, secrets, progressive delivery.</p>
              <ul class="tags"><li>Actions</li><li>ArgoCD</li><li>OPA</li><li>Vault</li></ul>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="stack" class="section alt">
      <div class="container">
        <h2>Tech tree</h2>
        <div class="diagram">
          <svg viewBox="0 0 900 420" role="img" aria-label="Tech stack tree">
            <g stroke="currentColor" stroke-width="2" opacity="0.35">
              <line x1="450" y1="50" x2="220" y2="130" />
              <line x1="450" y1="50" x2="450" y2="130" />
              <line x1="450" y1="50" x2="680" y2="130" />

              <line x1="220" y1="130" x2="120" y2="220" />
              <line x1="220" y1="130" x2="220" y2="220" />
              <line x1="220" y1="130" x2="320" y2="220" />

              <line x1="450" y1="130" x2="380" y2="220" />
              <line x1="450" y1="130" x2="450" y2="220" />
              <line x1="450" y1="130" x2="520" y2="220" />

              <line x1="680" y1="130" x2="580" y2="220" />
              <line x1="680" y1="130" x2="680" y2="220" />
              <line x1="680" y1="130" x2="780" y2="220" />
            </g>

            <g transform="translate(390,20)">
              <rect width="120" height="40" rx="8" class="node root"></rect>
              <text x="60" y="25" class="node-text">Platform</text>
            </g>

            <g transform="translate(160,110)">
              <rect width="120" height="40" rx="8" class="node"></rect>
              <text x="60" y="25" class="node-text">Cloud</text>
            </g>
            <g transform="translate(390,110)">
              <rect width="120" height="40" rx="8" class="node"></rect>
              <text x="60" y="25" class="node-text">DevOps</text>
            </g>
            <g transform="translate(620,110)">
              <rect width="120" height="40" rx="8" class="node"></rect>
              <text x="60" y="25" class="node-text">AI/ML</text>
            </g>

            <g transform="translate(80,210)">
              <rect width="100" height="36" rx="8" class="node"></rect>
              <text x="50" y="23" class="node-text small">AWS</text>
            </g>
            <g transform="translate(180,210)">
              <rect width="100" height="36" rx="8" class="node"></rect>
              <text x="50" y="23" class="node-text small">Azure</text>
            </g>
            <g transform="translate(280,210)">
              <rect width="100" height="36" rx="8" class="node"></rect>
              <text x="50" y="23" class="node-text small">GCP</text>
            </g>

            <g transform="translate(340,210)">
              <rect width="110" height="36" rx="8" class="node"></rect>
              <text x="55" y="23" class="node-text small">Kubernetes</text>
            </g>
            <g transform="translate(460,210)">
              <rect width="100" height="36" rx="8" class="node"></rect>
              <text x="50" y="23" class="node-text small">Terraform</text>
            </g>
            <g transform="translate(560,210)">
              <rect width="120" height="36" rx="8" class="node"></rect>
              <text x="60" y="23" class="node-text small">GitHub Actions</text>
            </g>

            <g transform="translate(600,210)">
              <rect width="100" height="36" rx="8" class="node"></rect>
              <text x="50" y="23" class="node-text small">Python</text>
            </g>
            <g transform="translate(700,210)">
              <rect width="100" height="36" rx="8" class="node"></rect>
              <text x="50" y="23" class="node-text small">PyTorch</text>
            </g>
            <g transform="translate(800,210)">
              <rect width="100" height="36" rx="8" class="node"></rect>
              <text x="50" y="23" class="node-text small">MLflow</text>
            </g>
          </svg>
        </div>
      </div>
    </section>

    <section id="contact" class="section">
      <div class="container">
        <h2>Contact</h2>
        <div class="contact">
          <div class="card">
            <form>
              <div style="margin-bottom:10px;">
                <label for="name">Name</label><br/>
                <input id="name" name="name" type="text" placeholder="Your name" required />
              </div>
              <div style="margin-bottom:10px;">
                <label for="email">Email</label><br/>
                <input id="email" name="email" type="email" placeholder="your@email.com" required />
              </div>
              <div style="margin-bottom:10px;">
                <label for="message">Message</label><br/>
                <textarea id="message" name="message" rows="5" placeholder="Project details or role..." required></textarea>
              </div>
              <button class="btn btn-primary" type="submit">Send</button>
            </form>
          </div>
          <div class="card">
            <h3>Details</h3>
            <p class="muted">Email: you@example.com</p>
            <p class="muted">LinkedIn: linkedin.com/in/yourprofile</p>
            <p class="muted">GitHub: github.com/yourhandle</p>
            <p class="muted">Location: Amalāpuram, AP, India (IST)</p>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer><div class="container">© <span id="year"></span> Your Name — Cloud • DevOps • AI</div></footer>
  <script>document.getElementById('year').textContent = new Date().getFullYear();</script>
</body>
</html>
