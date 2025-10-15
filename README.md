# romanfu.github.io
Roman's personal website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Roman Fu | For Hire</title>
  <meta name="description" content="Roman Fu — CSUF Marketing + Psychology student. Campus Manager at Depop, Team Lead at Newbridge Marketing, CMO of Formula SAE. Portfolio, resume, photos, and contact." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #0b0c10;
      --card: #111217;
      --muted: #9aa1ac;
      --text: #e8ecf1;
      --brand: #8fd3fe;
      --accent: #a78bfa;
      --ring: rgba(143, 211, 254, 0.4);
    }
    * { box-sizing: border-box; }
    html, body { margin: 0; background: linear-gradient(180deg, #0b0c10 0%, #0e1116 60%, #0b0c10 100%); color: var(--text); font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif; }
    a { color: var(--brand); text-decoration: none; }
    a:hover { text-decoration: underline; }
    .container { width: min(1100px, 92vw); margin: 0 auto; }
    header { position: sticky; top: 0; backdrop-filter: saturate(140%) blur(8px); background: rgba(11,12,16,0.7); border-bottom: 1px solid rgba(255,255,255,0.06); z-index: 100; }
    nav { display: flex; align-items: center; justify-content: space-between; padding: 12px 0; }
    .brand { font-weight: 800; letter-spacing: 0.5px; display: flex; align-items: center; gap: 10px; }
    .brand .dot { width: 10px; height: 10px; border-radius: 50%; background: radial-gradient(circle at 30% 30%, var(--brand), var(--accent)); box-shadow: 0 0 18px var(--ring); }
    .navlinks { display: flex; gap: 16px; flex-wrap: wrap; }
    .btn { display: inline-flex; align-items: center; gap: 8px; border: 1px solid rgba(255,255,255,0.12); padding: 10px 14px; border-radius: 999px; transition: transform .1s ease, border-color .2s ease; }
    .btn:hover { transform: translateY(-1px); border-color: var(--brand); }
    .hero { display: grid; grid-template-columns: 1.1fr .9fr; gap: 28px; align-items: center; padding: 48px 0 24px; }
    .card { background: radial-gradient(1200px 500px at -10% -10%, rgba(167,139,250,.12), transparent 45%), linear-gradient(180deg, rgba(255,255,255,0.04), rgba(255,255,255,0.02)); border: 1px solid rgba(255,255,255,0.08); border-radius: 18px; padding: 22px; box-shadow: 0 12px 40px rgba(0,0,0,0.35); }
    .hero h1 { font-size: clamp(32px, 3.6vw, 52px); margin: 10px 0 8px; line-height: 1.05; }
    .hero p.lead { color: var(--muted); font-size: clamp(16px, 1.5vw, 18px); margin: 0 0 16px; }
    .pillrow { display: flex; flex-wrap: wrap; gap: 8px; margin: 8px 0 12px; }
    .pill { background: rgba(255,255,255,0.06); border: 1px solid rgba(255,255,255,0.10); padding: 6px 10px; border-radius: 999px; font-size: 13px; color: #dbe7f4; }
    .avatar { aspect-ratio: 4/3; width: 100%; border-radius: 18px; object-fit: cover; border: 1px solid rgba(255,255,255,0.10); box-shadow: 0 10px 35px rgba(0,0,0,0.35); }
    .grid { display: grid; gap: 18px; }
    .grid.two { grid-template-columns: 1fr 1fr; }
    .grid.three { grid-template-columns: repeat(3, 1fr); }
    @media (max-width: 900px){ .hero { grid-template-columns: 1fr; } .grid.two, .grid.three { grid-template-columns: 1fr; } }
    section { padding: 20px 0 10px; }
    section h2 { font-size: 24px; margin: 4px 0 10px; }
    .kicker { color: var(--muted); font-weight: 600; text-transform: uppercase; letter-spacing: .08em; font-size: 12px; }
    ul { margin: 10px 0 0 18px; line-height: 1.7; }
    .resume h3 { margin: 14px 0 6px; font-size: 18px; }
    .meta { color: var(--muted); font-size: 14px; }
    .gallery { display: grid; grid-template-columns: repeat(6, 1fr); gap: 10px; }
    .gallery img { width: 100%; aspect-ratio: 1 / 1; object-fit: cover; border-radius: 12px; border: 1px solid rgba(255,255,255,0.1); }
    .band { margin: 22px 0; height: 1px; background: linear-gradient(90deg, transparent, rgba(255,255,255,0.12), transparent); }
    .contact { display: grid; grid-template-columns: 1.2fr .8fr; gap: 20px; align-items: start; }
    @media (max-width: 900px){ .contact { grid-template-columns: 1fr; } }
    .contact .card strong { display: inline-block; min-width: 115px; }
    .footer { color: var(--muted); font-size: 13px; padding: 30px 0 60px; text-align: center; }
    .badge { border: 1px solid rgba(255,255,255,0.14); padding: 2px 8px; border-radius: 999px; font-size: 12px; color: #e6f2ff; }
    .notice { font-size: 12px; color: var(--muted); }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <nav>
        <div class="brand"><span class="dot"></span> <span>Roman Fu</span></div>
        <div class="navlinks">
          <a class="btn" href="#who">Who</a>
          <a class="btn" href="#what">What</a>
          <a class="btn" href="#when">When</a>
          <a class="btn" href="#where">Where</a>
          <a class="btn" href="#why">Why</a>
          <a class="btn" href="#how">How</a>
          <a class="btn" href="#resume">Resume</a>
          <a class="btn" href="#photos">Photos</a>
        </div>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="hero">
      <div class="card">
        <span class="kicker">For Hire</span>
        <h1>Hi, I’m Roman Fu</h1>
        <p class="lead">CSUF Business Marketing and Psychology student pairing brand strategy with behavioral research. Campus Manager at Depop, Team Lead at Newbridge Marketing, and CMO for Formula SAE. I plan and execute campaigns that convert and I communicate insights that teams can act on.</p>
        <div class="pillrow">
          <span class="pill">Campus Activations</span>
          <span class="pill">Social Strategy</span>
          <span class="pill">Data Storytelling</span>
          <span class="pill">Behavioral Research</span>
          <span class="pill">Event Ops</span>
          <span class="pill">Leadership</span>
        </div>
        <div class="pillrow">
          <a class="btn" href="mailto:fumanro88@gmail.com">Email</a>
          <a class="btn" href="tel:+19518526664">Call</a>
          <a class="btn" href="https://www.linkedin.com/in/roman-fu-6142561b3/" target="_blank" rel="noopener">LinkedIn</a>
          <a class="btn" href="RomanFu_10092025_m.pdf" target="_blank">Resume PDF</a>
          <a class="btn" href="https://www.linkedin.com/in/roman-fu-6142561b3/" target="_blank" rel="noopener">My LinkedIn Profile</a>
        </div>
      </div>
      <div>
        <img class="avatar" src="roman professional photo.jpg" alt="Professional photo of Roman Fu" />
      </div>
    </section>

    <!-- rest of the code remains unchanged -->

    <footer class="footer">
      <div>© <span id="y"></span> Roman Fu • <span class="badge">Open to Work</span></div>
    </footer>
  </main>

  <script>
    // Year stamp
    document.getElementById('y').textContent = new Date().getFullYear();
  </script>
</body>
</html>

