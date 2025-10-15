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
        </div>
      </div>
      <div>
        <img class="avatar" src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?q=80&w=1200&auto=format&fit=crop" alt="Portrait style photo placeholder — replace with Roman’s photo" />
      </div>
    </section>

    <div class="band"></div>

    <section id="who" class="grid two">
      <div class="card">
        <span class="kicker">Who is Roman Fu?</span>
        <h2>Student, builder, and marketer who likes clean execution</h2>
        <p>I study Business Marketing and Psychology at California State University, Fullerton. I build student teams, run campus activations, and translate qualitative and quantitative signals into campaigns that work. I’m energized by projects where I can test a hypothesis, move fast, and show growth with simple metrics such as sign‑ups, attendance, and impressions.</p>
        <ul>
          <li>President, Fullerton Fashion Association. Scaled membership and engagement with brand‑aligned events and partnerships.</li>
          <li>CMO, Formula SAE. Built the marketing function from zero, set goals, and shipped content calendars and partnerships.</li>
          <li>Research Intern, Project Gamble. Help with segmentation, survey design, field data, and IRB‑compliant workflows.</li>
        </ul>
      </div>
      <div class="card">
        <span class="kicker">Quick Stats</span>
        <h2>At a glance</h2>
        <ul>
          <li>100 conversions from 8 campus activations for Depop</li>
          <li>30,000+ social impressions grown by targeted content</li>
          <li>800 QR scans and 10,000+ impressions for YouTube x NFL campaign</li>
          <li>$7,300 raised for student org programming</li>
          <li>500+ lessons taught as a martial arts instructor and program lead</li>
        </ul>
      </div>
    </section>

    <section id="what" class="card">
      <span class="kicker">What are you looking for?</span>
      <h2>Marketing internships and assistant roles in brand, partnerships, events, or research</h2>
      <p>I’m seeking roles where I can own a channel or activation calendar, collaborate with creative and analytics, and report clear KPI movement. I also enjoy research roles that link audience insights to positioning, messaging, and go‑to‑market tests.</p>
      <ul>
        <li>Brand or Partnerships Intern</li>
        <li>Events and Experiential Assistant</li>
        <li>Social Media and Community Coordinator</li>
        <li>Research Assistant in marketing or applied psychology</li>
      </ul>
    </section>

    <section id="when" class="card">
      <span class="kicker">When can you start?</span>
      <h2>Immediate start with flexible hours</h2>
      <p>I can begin now. I balance classes with a predictable weekly schedule and can support evenings or weekends during key events.</p>
    </section>

    <section id="where" class="card">
      <span class="kicker">Where are you located?</span>
      <h2>Southern California, open to hybrid and onsite assignments</h2>
      <p>Based near California State University, Fullerton. I can commute across Orange County and Los Angeles for meetings and activations. I also work well remotely when tasks are defined with milestones.</p>
    </section>

    <section id="why" class="card">
      <span class="kicker">Why a “for hire” page?</span>
      <h2>Simple proof helps decision makers move faster</h2>
      <p>Hiring managers and campus partners want quick signals. This page collects my work, metrics, and photos so you can skim and decide to talk. It also gives me a space to show personality and share the projects I manage on campus. If you like outcomes and clarity, we will work well together.</p>
    </section>

    <section id="how" class="contact">
      <div class="card">
        <span class="kicker">How can I reach you?</span>
        <h2>Let’s connect</h2>
        <p><strong>Phone:</strong> <a href="tel:+19518526664">+1 (951) 852‑6664</a><br/>
           <strong>Email:</strong> <a href="mailto:fumanro88@gmail.com">fumanro88@gmail.com</a><br/>
           <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/roman-fu-6142561b3/" target="_blank" rel="noopener">linkedin.com/in/roman-fu-6142561b3</a>
        </p>
        <p class="notice">Tip: include your school email if preferred. Phone and email are visible site‑wide for quick contact.</p>
      </div>
      <div class="card">
        <span class="kicker">Availability</span>
        <h2>Let’s set a quick call</h2>
        <p>I’m happy to schedule a 15‑minute intro call to scope your goals and the outcomes you want this semester.</p>
      </div>
    </section>

    <div class="band"></div>

    <section id="resume" class="resume">
      <div class="grid two">
        <div class="card">
          <span class="kicker">Education</span>
          <h2>California State University, Fullerton</h2>
          <p class="meta">B.A. Business Administration, Marketing Concentration; B.A. Psychology • Expected Graduation 2026</p>
        </div>
        <div class="card">
          <span class="kicker">Skills</span>
          <h2>Toolbox</h2>
          <ul>
            <li>Excel: VLOOKUP, PivotTables, charts, Solver, Goal Seek</li>
            <li>Social: Instagram, TikTok, YouTube, Brandwatch</li>
            <li>Design and Editing: Canva, CapCut, Adobe</li>
            <li>Productivity: Google Workspace, Microsoft Suite</li>
            <li>Data: SPSS, coding and thematic synthesis</li>
            <li>Event and Activation planning, team leadership, workflow management</li>
          </ul>
        </div>
      </div>

      <div class="card">
        <span class="kicker">Experience</span>
        <h2>Recent roles</h2>

        <h3>Campus Manager • Depop</h3>
        <p class="meta">September 2025 – Present</p>
        <ul>
          <li>Planned and executed 8 campus activations that generated 100 conversions and improved market penetration</li>
          <li>Led weekly marketing and strategy meetings to optimize segment reach and drive campaign KPIs</li>
          <li>Ran social campaigns with 30,000+ impressions that lifted brand awareness on campus</li>
        </ul>

        <h3>Team Lead • Newbridge Marketing</h3>
        <p class="meta">May 2025 – Present</p>
        <ul>
          <li>Led YouTube x NFL Street Team campaign at USC and CSUF using guerilla tactics</li>
          <li>Distributed 8,000 flyers that drove 800 QR scans and 10,000+ impressions</li>
          <li>Analyzed post‑activation survey data to provide actionable insights</li>
        </ul>

        <h3>Research Intern • Project Gamble (CSUF, UCI)</h3>
        <p class="meta">September 2025 – Present</p>
        <ul>
          <li>Applied target segmentation frameworks to improve community survey design and outreach</li>
          <li>Refined survey instruments, built visual reports, and presented insights weekly</li>
          <li>Supported field data collection and analysis while maintaining IRB standards</li>
        </ul>

        <h3>Marketing Intern • Temecula Chamber of Commerce</h3>
        <p class="meta">June 2024 – August 2024</p>
        <ul>
          <li>Produced assets for ShopLocal using Canva, Sprout Social, and CapCut</li>
          <li>Hosted and attended 10 workshops, networking events, and ribbon cuttings</li>
        </ul>

        <h3>Program Coordinator • United Studios of Self Defense</h3>
        <p class="meta">May 2017 – August 2021</p>
        <ul>
          <li>Communicated enrollment value that led to 50 prospect to customer conversions</li>
          <li>Taught 500+ group and private lessons tailored to learner needs</li>
          <li>Partnered with 5 organizations for promotional demos that raised foot traffic by 20%</li>
        </ul>
      </div>

      <div class="grid two">
        <div class="card">
          <span class="kicker">Activities</span>
          <h2>Leadership and campus work</h2>
          <h3>Chief Marketing Officer • Formula SAE</h3>
          <p class="meta">August 2025 – Present</p>
          <ul>
            <li>Built the marketing team with recruiting, onboarding, and role design</li>
            <li>Shaped strategy, growth targets, campaign timelines, and positioning</li>
            <li>Oversee ops with task delegation, workflow, and plans for scale</li>
          </ul>
          <h3>President • Fullerton Fashion Association</h3>
          <p class="meta">November 2023 – January 2025</p>
          <ul>
            <li>Forged a Poshmark partnership that drove 400+ sign‑ups and a 30% engagement lift</li>
            <li>Raised $7,300+ through partnerships</li>
            <li>Directed 8 Poshmark events and 40 general events while protecting brand standards</li>
          </ul>
          <h3>American Marketing Association • Co‑VP Fundraising</h3>
          <p class="meta">Ongoing</p>
          <ul>
            <li>Coordinated sponsor outreach and campus activations to support chapter goals</li>
          </ul>
        </div>
        <div class="card">
          <span class="kicker">Extras</span>
          <h2>Projects, study abroad, and interests</h2>
          <ul>
            <li>Independent Study: video essay on modern fashion, identity, and race using museum research in London</li>
            <li>Event concepts: Depop IRL tote decorating, clothing swaps, and collabs with campus orgs</li>
            <li>Analytics: Brandwatch listening projects and social KPI tracking</li>
            <li>Fitness goal: building upper‑body strength for climbing and training for a half marathon</li>
          </ul>
        </div>
      </div>
    </section>

    <div class="band"></div>

    <section id="photos" class="card">
      <span class="kicker">Photos</span>
      <h2>A quick look at personality and projects</h2>
      <p>Swap the placeholders with your photos. Keep file names short. The grid adapts to screens and supports as many images as you add.</p>
      <div class="gallery">
        <!-- Replace each src with your own image URLs or paths in your repo (e.g., /images/roman-01.jpg) -->
        <img src="https://images.unsplash.com/photo-1519085360753-af0119f7cbe7?q=80&w=800&auto=format&fit=crop" alt="Activation moment placeholder" />
        <img src="https://images.unsplash.com/photo-1517263904808-5dc91e3e7044?q=80&w=800&auto=format&fit=crop" alt="Speaking at an event placeholder" />
        <img src="https://images.unsplash.com/photo-1507537297725-24a1c029d3ca?q=80&w=800&auto=format&fit=crop" alt="Campus life placeholder" />
        <img src="https://images.unsplash.com/photo-1519681393784-d120267933ba?q=80&w=800&auto=format&fit=crop" alt="Working session placeholder" />
        <img src="https://images.unsplash.com/photo-1492724441997-5dc865305da7?q=80&w=800&auto=format&fit=crop" alt="Brand moment placeholder" />
        <img src="https://images.unsplash.com/photo-1492684223066-81342ee5ff30?q=80&w=800&auto=format&fit=crop" alt="Team photo placeholder" />
      </div>
      <p class="notice">To add more photos, duplicate the <code>&lt;img&gt;</code> tag and update the <code>src</code> and <code>alt</code>.</p>
    </section>

    <section class="card">
      <span class="kicker">Links</span>
      <h2>Downloads and profiles</h2>
      <ul>
        <li><a href="#" onclick="alert('Add your resume PDF to your repo and link it here, like /Roman-Fu-Resume.pdf'); return false;">Download my resume (PDF)</a></li>
        <li><a href="https://www.linkedin.com/in/roman-fu-6142561b3/" target="_blank" rel="noopener">LinkedIn</a></li>
        <li><a href="mailto:fumanro88@gmail.com">Email</a></li>
      </ul>
    </section>

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
