# romanfu.github.io
Roman's personal website
<!doctype html>
<div>
<strong>Fullerton Fashion Association</strong>
<div class="muted">President, content and events</div>
</div>
<div class="muted">2023 to 2024</div>
</div>
<div class="row">
<div>
<strong>American Marketing Association</strong>
<div class="muted">Co-VP Fundraising</div>
</div>
<div class="muted">2024</div>
</div>
</div>
</div>
</section>


<section id="contact" class="grid">
<div class="card" style="grid-column: span 12;">
<h2>Contact</h2>
<p class="muted">Open to internships and collabs. Best via email or Instagram.</p>
<div class="row">
<div class="tags">
<a class="tag" href="mailto:roman@example.com">Email</a>
<a class="tag" href="https://www.linkedin.com" target="_blank" rel="noreferrer noopener">LinkedIn</a>
<a class="tag" href="https://www.instagram.com" target="_blank" rel="noreferrer noopener">Instagram</a>
<a class="tag" href="https://github.com" target="_blank" rel="noreferrer noopener">GitHub</a>
</div>
<form action="https://formspree.io/f/your-id" method="POST" style="display:flex; gap:10px; flex-wrap:wrap; align-items:center;">
<label class="sr-only" for="email">Email</label>
<input id="email" name="email" type="email" placeholder="your@email" required style="padding:10px 12px; background:transparent; border:1px solid color-mix(in oklab, var(--muted) 30%, transparent); border-radius:10px; color:var(--text)" />
<label class="sr-only" for="msg">Message</label>
<input id="msg" name="message" type="text" placeholder="Message" required style="flex:1; min-width:220px; padding:10px 12px; background:transparent; border:1px solid color-mix(in oklab, var(--muted) 30%, transparent); border-radius:10px; color:var(--text)" />
<button class="btn" type="submit">Send</button>
</form>
</div>
</div>
</section>
</main>


<footer>
<div class="container row">
<small class="muted">© <span id="year"></span> Roman Fu</small>
<small class="muted">Built with HTML and CSS • Hosted on GitHub Pages</small>
</div>
</footer>


<script>
const themeBtn = document.getElementById('theme');
const root = document.documentElement;
const saved = localStorage.getItem('theme');
if(saved){ root.setAttribute('data-theme', saved); }
themeBtn.addEventListener('click', () => {
const cur = root.getAttribute('data-theme') === 'light' ? 'dark' : 'light';
root.setAttribute('data-theme', cur);
localStorage.setItem('theme', cur);
});
document.getElementById('year').textContent = new Date().getFullYear();
</script>
</body>
</html>
