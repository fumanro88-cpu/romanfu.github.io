# romanfu.github.io
Roman's personal website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Roman Fu - For Hire</title>
  <meta name="description" content="For Hire page - Roman Fu, CSUF Marketing and Psychology student - campus activations, research, and creative marketing." />
  <meta property="og:title" content="Roman Fu - For Hire" />
  <meta property="og:description" content="Who, What, When, Where, Why, and How - hire Roman Fu." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="images/roman-cover.jpg" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg:#0f1115; --card:#151822; --muted:#9aa4b2; --text:#e6eaf2; --brand:#6ee7b7; --accent:#60a5fa; --ring:#a78bfa;
    }
    *{box-sizing:border-box}
    html,body{margin:0;height:100%;scroll-behavior:smooth;font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Arial}
    body{background:linear-gradient(120deg,#0b0e13,#0f1115 40%,#10141b);color:var(--text)}
    a{color:var(--accent);text-decoration:none}
    a:hover{text-decoration:underline}
    .container{max-width:1100px;margin:0 auto;padding:24px}
    header{position:sticky;top:0;backdrop-filter:saturate(140%) blur(8px);background:rgba(16,20,27,.7);border-bottom:1px solid rgba(255,255,255,.06);z-index:40}
    nav{display:flex;align-items:center;justify-content:space-between}
    .nav-links{display:flex;gap:16px;flex-wrap:wrap}
    .badge{display:inline-flex;align-items:center;gap:8px;background:linear-gradient(90deg,#1c2430,#161c27);padding:8px 12px;border:1px solid rgba(255,255,255,.08);border-radius:9999px}
    .section{padding:56px 0;border-bottom:1px solid rgba(255,255,255,.07)}
    h1{font-size:44px;line-height:1.05;margin:12px 0 8px}
    h2{font-size:28px;margin:0 0 12px}
    h3{font-size:20px;margin:18px 0 8px;color:#d7dceb}
    p{color:var(--muted);line-height:1.7;margin:8px 0 0}
    .hero{display:grid;grid-template-columns:1.1fr .9fr;gap:24px;align-items:center}
    .card{background:linear-gradient(180deg,#171b26,#121622);border:1px solid rgba(255,255,255,.08);border-radius:18px;padding:20px;box-shadow:0 10px 40px rgba(0,0,0,.35)}
    .btn{display:inline-flex;align-items:center;gap:10px;background:linear-gradient(90deg,var(--brand),#4ade80);color:#0b0e13;font-weight:700;border:none;border-radius:12px;padding:12px 16px;cursor:pointer}
    .btn.secondary{background:transparent;color:var(--text);border:1px solid rgba(255,255,255,.18)}
    .grid{display:grid;gap:16px}
    .grid.cols-2{grid-template-columns:repeat(2,1fr)}
    .grid.cols-3{grid-template-columns:repeat(3,1fr)}
    .grid.cols-4{grid-template-columns:repeat(4,1fr)}
    @media (max-width:920px){.hero{grid-template-columns:1fr}.grid.cols-3{grid-template-columns:repeat(2,1fr)}.grid.cols-4{grid-template-columns:repeat(2,1fr)}}
    @media (max-width:560px){.grid.cols-2,.grid.cols-3,.grid.cols-4{grid-template-columns:1fr}}
    .pill{display:inline-block;padding:6px 10px;border:1px solid rgba(255,255,255,.14);border-radius:9999px;font-size:12px;color:#b5becc}
    .list{display:grid;gap:10px;margin-top:8px}
    .list li{background:rgba(255,255,255,.03);border:1px solid rgba(255,255,255,.08);padding:12px;border-radius:12px}
    .gallery img{width:100%;height:230px;object-fit:cover;border-radius:14px;border:1px solid rgba(255,255,255,.12);background:#0b0e13}
    .kpis{display:flex;gap:16px;flex-wrap:wrap;margin-top:10px}
    .kpi{flex:1 1 160px;background:linear-gradient(180deg,#121623,#0f1320);border:1px solid rgba(255,255,255,.08);border-radius:14px;padding:14px}
    .kpi b{font-size:22px;color:#d9f99d}
    footer{padding:34px 0;color:#9aa4b2}
    .contact-card{display:grid;grid-template-columns:1.1fr .9fr;gap:16px}
    @media (max-width:840px){.contact-card{grid-template-columns:1fr}}
    .contact-item{display:flex;align-items:center;gap:10px}
    .sr-only{position:absolute;width:1px;height:1px;padding:0;margin:-1px;overflow:hidden;clip:rect(0,0,0,0);white-space:nowrap;border:0}
    /* subtle scroll anchors */
    .anchor{scroll-margin-top:96px}
    /* link cards */
    .linkcard{display:flex;align-items:center;justify-content:space-between;padding:14px 16px;border:1px solid rgba(255,255,255,.12);border-radius:12px;background:rgba(255,255,255,.03)}
  </style>
  <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "Person",
      "name": "Roman Fu",
      "jobTitle": "Marketing Student - Campus Activations and Research",
      "email": "mailto:fumanro88@gmail.com",
      "telephone": "+1-951-852-6664",
      "url": "https://romanfu.github.io/",
      "sameAs": [
        "https://www.linkedin.com/in/roman-fu-6142561b3/"
      ],
      "address": {
        "@type": "PostalAddress",
        "addressLocality": "Fullerton",
        "addressRegion": "CA",
        "addressCountry": "US"
      }
    }
  </script>
</head>
<body>
  <header>
    <div class="container">
      <nav aria-label="Primary">
        <div class="badge" aria-label="Contact details">
          <span>📞 <a href="tel:+19518526664" aria-label="Call Roman">+1 951 852 6664</a></span>
          <span>•</span>
          <span>✉️ <a href="mailto:fumanro88@gmail.com" aria-label="Email Roman">fumanro88@gmail.com</a></span>
        </div>
        <div class="nav-links">
          <a href="#who">Who</a>
          <a href="#what">What</a>
          <a href="#when">When</a>
          <a href="#where">Where</a>
          <a href="#why">Why</a>
          <a href="#how">How</a>
          <a href="#resume">Resume</a>
          <a href="#gallery">Photos</a>
        </div>
      </nav>
    </div>
  </header>

  <main class="container">
    <!-- HERO -->
    <section class="section hero">
      <div class="card">
        <span class="pill">For Hire - Student Marketer and Research Assistant</span>
        <h1>Hi, I am <span style="color:var(--brand)">Roman Fu</span>.</h1>
        <p>I build creative campus activations, synthesize data into clear insights, and help brands grow with smart experiments. I am double majoring in Business Marketing and Psychology at Cal State Fullerton.</p>
        <div class="kpis" aria-label="Highlights">
          <div class="kpi"><b>30,000+</b><br><span class="muted">Social impressions across campaigns</span></div>
          <div class="kpi"><b>100</b><br><span class="muted">Conversions from Depop activations</span></div>
          <div class="kpi"><b>$7,300</b><br><span class="muted">Raised for student org initiatives</span></div>
          <div class="kpi"><b>500+</b><br><span class="muted">Lessons taught as a program coordinator</span></div>
        </div>
        <div style="margin-top:16px;display:flex;gap:10px;flex-wrap:wrap">
          <a class="btn" href="#how">Hire me</a>
          <a class="btn secondary" href="#resume">View resume</a>
          <a class="btn secondary" href="https://www.linkedin.com/in/roman-fu-6142561b3/" target="_blank" rel="noopener">LinkedIn</a>
        </div>
      </div>
      <div class="card">
        <img src="images/roman-cover.jpg" alt="Roman smiling at a campus event" style="width:100%;height:100%;object-fit:cover;border-radius:14px" />
      </div>
    </section>

    <!-- WHO -->
    <section id="who" class="section anchor">
      <h2>Who is Roman Fu</h2>
      <div class="grid cols-2">
        <div class="card">
          <h3>About</h3>
          <p>I am a student marketer with a research mindset. I like campaigns that are measurable and experiences that feel personal. My background blends event activations, social media, and research methods. I care about community impact and I like projects where I can test ideas fast.</p>
          <ul class="list">
            <li><strong>Education</strong> - California State University Fullerton - B.A. Business Administration, Marketing concentration - B.A. Psychology - Expected 2026</li>
            <li><strong>Strengths</strong> - Activation planning - data analysis - content production - team leadership</li>
            <li><strong>Tools</strong> - Excel - SPSS - Canva - CapCut - Adobe - Google Workspace - Microsoft Suite - Brandwatch</li>
          </ul>
        </div>
        <div class="card">
          <h3>Quick facts</h3>
          <ul class="list">
            <li>Led Poshmark partnership - 400+ sign-ups - grew FFA to largest CSUF student organization</li>
            <li>Team lead for YouTube x NFL Street Team at USC and CSUF - 8,000 flyers - 800 scans - 10,000+ impressions</li>
            <li>Depop Campus Manager - planned 8 activations - 100 conversions - weekly strategy syncs</li>
            <li>Research intern - Project Gamble - segmentation frameworks - survey design - IRB standards</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- WHAT -->
    <section id="what" class="section anchor">
      <h2>What are you looking for</h2>
      <div class="grid cols-2">
        <div class="card">
          <p>I am seeking part-time or project-based roles in campus marketing, event activations, social media, or research assistance. I add the most value where outreach meets analysis, such as planning tablings that convert and reporting insights that steer the next sprint.</p>
          <div class="list">
            <div class="linkcard"><span>Campus activations and tabling that drive sign-ups</span><span>🎯</span></div>
            <div class="linkcard"><span>Social campaigns with clear KPI tracking</span><span>📊</span></div>
            <div class="linkcard"><span>Survey design - field data collection - reporting</span><span>🧪</span></div>
            <div class="linkcard"><span>Partnerships and student org collaborations</span><span>🤝</span></div>
          </div>
        </div>
        <div class="card">
          <h3>Example deliverables</h3>
          <ul class="list">
            <li>Activation plan with staffing, incentives, and budget</li>
            <li>Content calendar - hooks, CTAs, assets, and metrics</li>
            <li>Survey instrument - pilot feedback - revision log</li>
            <li>Post-activation report - conversions - lessons learned</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- WHEN -->
    <section id="when" class="section anchor">
      <h2>When can you start</h2>
      <div class="card">
        <p>I can start immediately for remote work and most on-campus projects. For off-campus or field work, I can coordinate schedules around class times. Weekend and evening availability is flexible. I respond quickly and I like clear weekly checkpoints.</p>
      </div>
    </section>

    <!-- WHERE -->
    <section id="where" class="section anchor">
      <h2>Where are you located</h2>
      <div class="card">
        <p>Based in Fullerton, California with access to the CSUF campus community. Open to Orange County and Los Angeles assignments. Comfortable with hybrid or remote work.</p>
      </div>
    </section>

    <!-- WHY -->
    <section id="why" class="section anchor">
      <h2>Why a For Hire page</h2>
      <div class="grid cols-2">
        <div class="card">
          <p>I treat this page like a living portfolio that cuts the guesswork for recruiters. It shows who I am, what I can do, and how to book me fast. It is also proof that I can ship a clean, useful page - which is a useful signal for marketing work that needs clarity and speed.</p>
          <p>Hiring is easier when there is less friction. This page puts contact buttons up front, shows relevant metrics, and gives a quick story, so you can decide in minutes.</p>
        </div>
        <div class="card">
          <h3>Benefits for my search</h3>
          <ul class="list">
            <li>Shows measurable outcomes - impressions, conversions, funds raised</li>
            <li>Highlights leadership - FFA President and Formula SAE CMO</li>
            <li>Demonstrates research literacy - IRB, survey design, analysis</li>
            <li>Provides easy contact and immediate next steps</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- HOW -->
    <section id="how" class="section anchor">
      <h2>How to reach me</h2>
      <div class="contact-card">
        <div class="card">
          <div class="contact-item">📞 <a href="tel:+19518526664">+1 951 852 6664</a></div>
          <div class="contact-item">✉️ <a href="mailto:fumanro88@gmail.com">fumanro88@gmail.com</a></div>
          <div class="contact-item">💼 <a target="_blank" rel="noopener" href="https://www.linkedin.com/in/roman-fu-6142561b3/">LinkedIn - roman-fu</a></div>
        </div>
        <div class="card">
          <h3>Quick intro message</h3>
          <p>If you want me to support an activation or research sprint, include your timeline, location, and goals. I will reply with my availability and a simple scope.</p>
          <a class="btn" href="mailto:fumanro88@gmail.com?subject=Hire%20Roman%20Fu&body=Hi%20Roman%2C%0A%0AWe'd%20like%20help%20with%3A%20%5Bbrief%20description%5D%0ATimeline%3A%20%0ALocation%3A%20%0ABudget%3A%20%0A%0AThanks!">Email me</a>
        </div>
      </div>
    </section>

    <!-- RESUME -->
    <section id="resume" class="section anchor">
      <h2>Resume</h2>
      <div class="grid cols-2">
        <div class="card">
          <h3>Experience</h3>
          <ul class="list">
            <li><strong>Campus Manager - Depop</strong> - Sep 2025 to Present - planned 8 activations - 100 conversions - weekly strategy - 30,000 plus impressions</li>
            <li><strong>Team Lead - Newbridge Marketing</strong> - May 2025 to Present - led YouTube x NFL Street Team at USC and CSUF - 8,000 flyers - 800 QR scans - 10,000 plus impressions - survey insights</li>
            <li><strong>Research Intern - Project Gamble - CSUF and UCI</strong> - Sep 2025 to Present - segmentation for survey design and outreach - refine instruments - visual reports - weekly presentations - field collection with IRB standards</li>
            <li><strong>Marketing Intern - Temecula Chamber of Commerce</strong> - Jun 2024 to Aug 2024 - produced ShopLocal materials using Canva - Sprout Social - CapCut - supported 10 workshops and events</li>
            <li><strong>Program Coordinator - United Studios of Self Defense</strong> - May 2017 to Aug 2021 - 50 conversions - 500 plus lessons - five partner demos driving 20 percent more prospects</li>
          </ul>
        </div>
        <div class="card">
          <h3>Activities and leadership</h3>
          <ul class="list">
            <li><strong>Chief Marketing Officer - Formula SAE</strong> - Aug 2025 to Present - built the marketing team - strategy and growth objectives - operations and scalability</li>
            <li><strong>President - Fullerton Fashion Association</strong> - Nov 2023 to Jan 2025 - Poshmark partnership - 400 plus sign-ups - 30 percent lift in engagement - 8 hosted by Poshmark - 40 general events</li>
            <li><strong>American Marketing Association - CSUF</strong> - Co-VP of Fundraising - led sponsorship outreach and event support</li>
            <li><strong>Depop Campus Ambassador - prior cohort</strong> - supported tablings and student partnerships</li>
            <li><strong>Study Abroad - London - HSS 499</strong> - built a video essay on fashion - identity - and culture - performed museum research and interviews</li>
          </ul>
          <h3>Skills</h3>
          <p>Excel - vlookup - pivot tables and charts - solver - goal seek - SPSS - Canva - CapCut - Adobe - Google Workspace - Microsoft Suite - Brandwatch - event and activation planning - data analysis - team leadership and workflow management</p>
        </div>
      </div>
    </section>

    <!-- EXTRA CURRICULAR SHOWCASE -->
    <section id="extras" class="section anchor">
      <h2>Extracurricular showcase</h2>
      <div class="grid cols-3">
        <div class="card">
          <h3>Campus Activations</h3>
          <p>Concept to tabling - incentives - staffing - art supplies - QR tracking - post-mortem reporting.</p>
        </div>
        <div class="card">
          <h3>Fashion and Culture</h3>
          <p>Led FFA growth - organized speaker panels and brand collabs - documented exhibits in London for research.</p>
        </div>
        <div class="card">
          <h3>Research Support</h3>
          <p>Segmentation frameworks - field surveys - coding and thematic synthesis - visual reports for stakeholders.</p>
        </div>
      </div>
    </section>

    <!-- GALLERY -->
    <section id="gallery" class="section anchor">
      <h2>Photos</h2>
      <p>These images should highlight personality and work style. Replace the placeholder files in the <code>images/</code> folder with your own photos using the same names to keep the layout intact.</p>
      <div class="gallery grid cols-4" aria-label="Photo gallery">
        <img src="images/roman1.jpg" alt="Roman at a campus table activation" />
        <img src="images/roman2.jpg" alt="Roman leading a meeting with teammates" />
        <img src="images/roman3.jpg" alt="Roman at a networking event" />
        <img src="images/roman4.jpg" alt="Roman filming social content" />
        <img src="images/roman5.jpg" alt="Roman presenting a report" />
        <img src="images/roman6.jpg" alt="Roman at a museum - London study abroad" />
        <img src="images/roman7.jpg" alt="Roman at a fashion event booth" />
        <img src="images/roman8.jpg" alt="Roman working on a laptop outdoors" />
        <img src="images/roman9.jpg" alt="Roman with Formula SAE team" />
        <img src="images/roman10.jpg" alt="Roman tabling with Depop signage" />
        <img src="images/roman11.jpg" alt="Roman with friends at a campus event" />
        <img src="images/roman12.jpg" alt="Roman casual portrait" />
      </div>
    </section>
  </main>

  <footer class="container">
    <div class="grid cols-2">
      <div>
        <strong>Roman Fu</strong>
        <p>Business Administration - Marketing - and Psychology at CSUF. For Hire for creative activations and research support.</p>
      </div>
      <div class="list">
        <div class="linkcard"><span>Phone</span><a href="tel:+19518526664">+1 951 852 6664</a></div>
        <div class="linkcard"><span>Email</span><a href="mailto:fumanro88@gmail.com">fumanro88@gmail.com</a></div>
        <div class="linkcard"><span>LinkedIn</span><a target="_blank" rel="noopener" href="https://www.linkedin.com/in/roman-fu-6142561b3/">linkedin.com/in/roman-fu-6142561b3</a></div>
      </div>
    </div>
    <p style="margin-top:14px;color:#7c8596">© <span id="yr"></span> Roman Fu. All rights reserved.</p>
  </footer>

  <script>
    document.getElementById('yr').textContent = new Date().getFullYear();
  </script>
</body>
</html>

