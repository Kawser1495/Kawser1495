<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Kawser Talukder — ML Profile</title>
  <style>
    :root{
      --bg:#0f1724; --card:#0b1220; --muted:#9aa6b2; --accent:#00d1ff;
      --glass: rgba(255,255,255,0.03);
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    html,body{height:100%;margin:0;background:linear-gradient(180deg,#071227 0%, #071827 100%);color:#e6eef6;}
    .container{max-width:900px;margin:28px auto;padding:22px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border-radius:14px;box-shadow:0 10px 30px rgba(2,6,23,0.6);}
    header{display:flex;gap:18px;align-items:center;}
    .avatar{width:88px;height:88px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#7b61ff);display:flex;align-items:center;justify-content:center;font-weight:700;font-size:34px;color:#071827;}
    h1{margin:0;font-size:28px}
    .subtitle{color:var(--muted);margin-top:6px}
    hr{border:0;height:1px;background:linear-gradient(90deg,transparent,var(--muted),transparent);margin:18px 0;border-radius:2px}
    .cols{display:grid;grid-template-columns:1fr 320px;gap:20px}
    @media (max-width:880px){.cols{grid-template-columns:1fr;}.right{order:2}}
    .card{background:var(--glass);padding:14px;border-radius:10px}
    .section-title{display:flex;align-items:center;gap:10px;font-weight:700;color:#dbe9ff;margin-bottom:8px}
    ul{margin:8px 0 0 18px;padding:0;color:var(--muted)}
    .tech-badges{display:flex;flex-wrap:wrap;gap:8px;margin-top:8px}
    .badge{background:#071827;padding:8px 12px;border-radius:6px;border:1px solid rgba(255,255,255,0.03);font-weight:600}
    .stats img{width:100% ;border-radius:8px}
    .links{display:flex;gap:8px;flex-wrap:wrap}
    .btn{display:inline-block;padding:8px 12px;border-radius:8px;text-decoration:none;font-weight:600}
    .btn.github{background:#0f1724;color:#e6eef6;border:1px solid rgba(255,255,255,0.03)}
    .btn.linkedin{background:#0077B5;color:#fff}
    .contact{color:var(--muted);margin-top:10px}
    footer{margin-top:18px;color:var(--muted);font-size:13px;text-align:center}
    .motto{font-style:italic;color:#fff;margin-top:8px}
  </style>
</head>
<body>
  <div class="container" role="main">
    <header>
      <div class="avatar">KT</div>
      <div>
        <h1>Hi, I'm <strong>Kawser Talukder</strong></h1>
        <div class="subtitle">Aspiring Machine Learning Specialist · Computer Science Student · Building data-driven solutions</div>
        <div class="motto">“Keep learning, keep building — every small project is a step toward mastery.”</div>
      </div>
    </header>

    <hr />

    <div class="cols">
      <!-- LEFT / MAIN -->
      <div>
        <section class="card" aria-labelledby="about">
          <div id="about" class="section-title">🧩 About Me</div>
          <p style="color:var(--muted);margin:0">
            Exploring the intersection of Machine Learning, Artificial Intelligence, and Software Engineering.
            Skilled in C, C++, C#, Java, and Python. Focused on ML fundamentals, model training, and building small projects to learn fast.
          </p>
        </section>

        <section class="card" style="margin-top:14px" aria-labelledby="learning">
          <div id="learning" class="section-title">🧠 What I'm Learning</div>
          <ul>
            <li>Machine Learning algorithms & data preprocessing</li>
            <li>Python for Data Science — Pandas, NumPy, Matplotlib, Scikit-learn</li>
            <li>Deep Learning basics with TensorFlow / Keras</li>
            <li>Model evaluation, tuning and deployment basics</li>
          </ul>
        </section>

        <section class="card" style="margin-top:14px" aria-labelledby="projects">
          <div id="projects" class="section-title">🚀 Projects & Interests</div>
          <ul>
            <li>Mini ML projects — classification, regression, prediction</li>
            <li>Data analysis and visualization with real datasets</li>
            <li>Simple neural network experiments and small AI tools</li>
            <li>Making tech more human through data-driven work</li>
          </ul>
        </section>

        <section class="card" style="margin-top:14px" aria-labelledby="achieve">
          <div id="achieve" class="section-title">🏆 Achievements & Badges</div>
          <div style="display:flex;gap:10px;flex-wrap:wrap">
            <div class="badge">AI Enthusiast</div>
            <div class="badge">ML Developer</div>
            <div class="badge">Open Source Learner</div>
          </div>
        </section>

        <section class="card" style="margin-top:14px" aria-labelledby="contact">
          <div id="contact" class="section-title">📫 Connect With Me</div>
          <div class="links" style="margin-bottom:10px">
            <a class="btn github" href="https://github.com/Kawser1495" target="_blank" rel="noopener">GitHub</a>
            <a class="btn linkedin" href="https://linkedin.com/comm/mynetwork/discovery-see-all?usecase=PEOPLE_FOLLOWS&followMember=kawser1495" target="_blank" rel="noopener">LinkedIn</a>
            <a class="btn" style="background:#1877F2;color:white" href="https://www.facebook.com/kawser.talukder.90" target="_blank" rel="noopener">Facebook</a>
            <a class="btn" style="background:#D14836;color:white" href="mailto:ktl149516@gmail.com">Email</a>
          </div>
          <div class="contact">Phone: <strong>01646381642</strong></div>
        </section>

      </div>

      <!-- RIGHT / SIDEBAR -->
      <aside class="right" style="min-width:260px">
        <div class="card stats" aria-labelledby="tech">
          <div id="tech" class="section-title">⚙️ Tech Stack</div>
          <div class="tech-badges">
            <div class="badge">C</div>
            <div class="badge">C++</div>
            <div class="badge">C#</div>
            <div class="badge">Java</div>
            <div class="badge">Python</div>
            <div class="badge">TensorFlow</div>
            <div class="badge">Scikit-learn</div>
            <div class="badge">Pandas</div>
          </div>
        </div>

        <div class="card" style="margin-top:14px">
          <div class="section-title">📊 GitHub Stats</div>
          <!-- GitHub readme stats images (live) -->
          <img alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=Kawser1495&show_icons=true&theme=tokyonight" />
          <div style="height:10px"></div>
          <img alt="Most Used Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kawser1495&layout=compact&theme=tokyonight" />
        </div>

        <div class="card" style="margin-top:14px">
          <div class="section-title">👀 Profile Views</div>
          <div style="display:flex;gap:10px;align-items:center">
            <div style="background:#0b1220;padding:8px 12px;border-radius:8px;font-weight:700">Profile Views</div>
            <div style="background:#00f0d8;color:#071827;padding:8px 12px;border-radius:6px">14</div>
          </div>
        </div>
      </aside>
    </div>

    <footer>
      <div>Made by Kawser Talukder — Aspiring Machine Learning Specialist</div>
      <div style="margin-top:6px;color:var(--muted)">Tip: paste this HTML into <code>index.html</code> for GitHub Pages or paste parts into <code>README.md</code> (GitHub supports inline HTML).</div>
    </footer>
  </div>
</body>
</html>
