<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>QA Reports</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  <style>
    *, *::before, *::after {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    :root {
      --bg: #0d1117;
      --bg-elevated: #161b22;
      --bg-card: rgba(22, 27, 34, 0.75);
      --border: rgba(48, 54, 61, 0.8);
      --border-hover: rgba(59, 130, 246, 0.4);
      --text: #f0f6fc;
      --text-muted: #8b949e;
      --accent: #3b82f6;
      --accent-dim: rgba(59, 130, 246, 0.15);
      --success: #3fb950;
      --warning: #d29922;
      --danger: #f85149;
      --low: #58a6ff;
      --glass: rgba(255, 255, 255, 0.03);
      --shadow: 0 8px 32px rgba(0, 0, 0, 0.4);
      --radius: 12px;
      --radius-sm: 8px;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
      min-height: 100vh;
      overflow-x: hidden;
      cursor: none;
    }

    a, button {
      cursor: none;
    }

    /* Custom Cursor */
    .cursor {
      position: fixed;
      width: 20px;
      height: 20px;
      border: 1.5px solid rgba(255, 255, 255, 0.85);
      border-radius: 50%;
      pointer-events: none;
      z-index: 9999;
      transform: translate(-50%, -50%);
      transition: width 0.2s ease, height 0.2s ease, border-color 0.2s ease, background 0.2s ease;
      mix-blend-mode: difference;
    }

    .cursor-dot {
      position: fixed;
      width: 4px;
      height: 4px;
      background: #fff;
      border-radius: 50%;
      pointer-events: none;
      z-index: 10000;
      transform: translate(-50%, -50%);
      transition: background 0.2s ease;
    }

    .cursor.grow {
      width: 42px;
      height: 42px;
      border-color: var(--accent);
      background: rgba(59, 130, 246, 0.08);
    }

    .cursor.link-hover {
      border-color: var(--accent);
      background: rgba(59, 130, 246, 0.12);
    }

    /* Navigation */
    .nav {
      position: sticky;
      top: 0;
      z-index: 100;
      background: rgba(13, 17, 23, 0.85);
      backdrop-filter: blur(16px);
      -webkit-backdrop-filter: blur(16px);
      border-bottom: 1px solid var(--border);
      padding: 0 2rem;
    }

    .nav-inner {
      max-width: 1100px;
      margin: 0 auto;
      display: flex;
      align-items: center;
      justify-content: space-between;
      height: 64px;
    }

    .nav-logo {
      font-weight: 600;
      font-size: 1.05rem;
      letter-spacing: -0.02em;
      color: var(--text);
      text-decoration: none;
    }

    .nav-links {
      display: flex;
      gap: 2rem;
      list-style: none;
    }

    .nav-links a {
      color: var(--text-muted);
      text-decoration: none;
      font-size: 0.9rem;
      font-weight: 500;
      transition: color 0.2s ease;
    }

    .nav-links a:hover,
    .nav-links a.active {
      color: var(--text);
    }

    .nav-date {
      font-size: 0.85rem;
      color: var(--text-muted);
      font-weight: 500;
      font-variant-numeric: tabular-nums;
    }

    /* Hero */
    .hero {
      max-width: 1100px;
      margin: 0 auto;
      padding: 5rem 2rem 3rem;
      text-align: center;
    }

    .hero h1 {
      font-size: clamp(2.2rem, 5vw, 3.2rem);
      font-weight: 700;
      letter-spacing: -0.03em;
      margin-bottom: 0.75rem;
      background: linear-gradient(180deg, #fff 0%, #c9d1d9 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }

    .hero p {
      color: var(--text-muted);
      font-size: 1.1rem;
      max-width: 480px;
      margin: 0 auto 3rem;
    }

    /* Stats */
    .stats {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 1rem;
      max-width: 800px;
      margin: 0 auto;
    }

    .stat-card {
      background: var(--bg-card);
      border: 1px solid var(--border);
      border-radius: var(--radius);
      padding: 1.5rem 1rem;
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.5s ease, transform 0.5s ease, border-color 0.25s ease, box-shadow 0.25s ease;
    }

    .stat-card.visible {
      opacity: 1;
      transform: translateY(0);
    }

    .stat-card:hover {
      border-color: var(--border-hover);
      box-shadow: 0 4px 24px rgba(59, 130, 246, 0.08);
    }

    .stat-label {
      font-size: 0.8rem;
      color: var(--text-muted);
      font-weight: 500;
      text-transform: uppercase;
      letter-spacing: 0.04em;
      margin-bottom: 0.4rem;
    }

    .stat-value {
      font-size: 2rem;
      font-weight: 700;
      letter-spacing: -0.03em;
      font-variant-numeric: tabular-nums;
    }

    .stat-value.open { color: var(--accent); }
    .stat-value.critical { color: var(--danger); }
    .stat-value.medium { color: var(--warning); }
    .stat-value.low { color: var(--low); }

    /* Reports Section */
    .reports {
      max-width: 1100px;
      margin: 0 auto;
      padding: 2rem 2rem 5rem;
    }

    .section-title {
      font-size: 1.25rem;
      font-weight: 600;
      letter-spacing: -0.02em;
      margin-bottom: 1.5rem;
      color: var(--text);
    }

    .report-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(340px, 1fr));
      gap: 1.5rem;
    }

    .report-card {
      background: var(--bg-card);
      border: 1px solid var(--border);
      border-radius: var(--radius);
      padding: 1.75rem;
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      opacity: 0;
      transform: translateY(28px);
      transition: opacity 0.6s ease, transform 0.6s ease, border-color 0.3s ease, box-shadow 0.3s ease;
    }

    .report-card.visible {
      opacity: 1;
      transform: translateY(0);
    }

    .report-card:hover {
      border-color: var(--border-hover);
      box-shadow: var(--shadow);
      transform: translateY(-4px);
    }

    .report-header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 1.25rem;
      flex-wrap: wrap;
      gap: 0.5rem;
    }

    .bug-id {
      font-family: 'Inter', monospace;
      font-size: 0.85rem;
      font-weight: 600;
      color: var(--accent);
      background: var(--accent-dim);
      padding: 0.3rem 0.65rem;
      border-radius: 6px;
      letter-spacing: 0.02em;
    }

    .badges {
      display: flex;
      gap: 0.5rem;
    }

    .badge {
      font-size: 0.72rem;
      font-weight: 600;
      padding: 0.25rem 0.6rem;
      border-radius: 6px;
      text-transform: uppercase;
      letter-spacing: 0.03em;
    }

    .badge-open {
      background: rgba(63, 185, 80, 0.15);
      color: var(--success);
    }

    .badge-low {
      background: rgba(88, 166, 255, 0.15);
      color: var(--low);
    }

    .badge-medium {
      background: rgba(210, 153, 34, 0.15);
      color: var(--warning);
    }

    .report-meta {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 0.75rem;
      margin-bottom: 1.25rem;
      padding-bottom: 1.25rem;
      border-bottom: 1px solid var(--border);
    }

    .meta-item label {
      display: block;
      font-size: 0.7rem;
      color: var(--text-muted);
      text-transform: uppercase;
      letter-spacing: 0.04em;
      margin-bottom: 0.15rem;
    }

    .meta-item span {
      font-size: 0.9rem;
      font-weight: 500;
    }

    .report-body {
      margin-bottom: 1.25rem;
    }

    .report-body h4 {
      font-size: 0.75rem;
      color: var(--text-muted);
      text-transform: uppercase;
      letter-spacing: 0.04em;
      margin-bottom: 0.35rem;
      margin-top: 1rem;
    }

    .report-body h4:first-child {
      margin-top: 0;
    }

    .report-body p {
      font-size: 0.9rem;
      color: var(--text);
      line-height: 1.55;
    }

    .report-body code {
      background: rgba(255, 255, 255, 0.06);
      padding: 0.1rem 0.4rem;
      border-radius: 4px;
      font-size: 0.85rem;
      font-family: 'Inter', monospace;
    }

    .bug-img {
      width: 100%;
      height: 160px;
      object-fit: cover;
      border-radius: var(--radius-sm);
      border: 1px solid var(--border);
      margin-top: 1rem;
      background: var(--bg-elevated);
    }

    .img-placeholder {
      width: 100%;
      height: 160px;
      border-radius: var(--radius-sm);
      border: 1px dashed var(--border);
      margin-top: 1rem;
      display: flex;
      align-items: center;
      justify-content: center;
      color: var(--text-muted);
      font-size: 0.85rem;
      background: var(--glass);
    }

    .copy-btn {
      position: relative;
      width: 100%;
      padding: 0.7rem 1rem;
      background: var(--accent);
      color: #fff;
      border: none;
      border-radius: var(--radius-sm);
      font-family: inherit;
      font-size: 0.875rem;
      font-weight: 600;
      overflow: hidden;
      transition: background 0.2s ease, transform 0.15s ease;
    }

    .copy-btn:hover {
      background: #2563eb;
    }

    .copy-btn:active {
      transform: scale(0.98);
    }

    .copy-btn .ripple {
      position: absolute;
      border-radius: 50%;
      background: rgba(255, 255, 255, 0.35);
      transform: scale(0);
      animation: ripple 0.5s linear;
      pointer-events: none;
    }

    @keyframes ripple {
      to {
        transform: scale(4);
        opacity: 0;
      }
    }

    /* Toast */
    .toast {
      position: fixed;
      bottom: 1.75rem;
      right: 1.75rem;
      background: var(--bg-elevated);
      border: 1px solid var(--border);
      color: var(--text);
      padding: 0.85rem 1.25rem;
      border-radius: var(--radius-sm);
      font-size: 0.9rem;
      font-weight: 500;
      display: flex;
      align-items: center;
      gap: 0.5rem;
      box-shadow: var(--shadow);
      z-index: 1000;
      opacity: 0;
      transform: translateY(12px);
      transition: opacity 0.3s ease, transform 0.3s ease;
      pointer-events: none;
    }

    .toast.show {
      opacity: 1;
      transform: translateY(0);
    }

    .toast .check {
      color: var(--success);
      font-size: 1rem;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 2.5rem 2rem;
      border-top: 1px solid var(--border);
      color: var(--text-muted);
      font-size: 0.85rem;
    }

    /* Responsive */
    @media (max-width: 768px) {
      .nav-links {
        display: none;
      }

      .stats {
        grid-template-columns: repeat(2, 1fr);
      }

      .hero {
        padding: 3.5rem 1.25rem 2rem;
      }

      .reports {
        padding: 1.5rem 1.25rem 3.5rem;
      }

      .report-grid {
        grid-template-columns: 1fr;
      }

      .nav {
        padding: 0 1.25rem;
      }
    }

    @media (max-width: 480px) {
      .stats {
        grid-template-columns: 1fr 1fr;
        gap: 0.75rem;
      }

      .stat-value {
        font-size: 1.6rem;
      }

      .report-meta {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  <div class="cursor" id="cursor"></div>
  <div class="cursor-dot" id="cursorDot"></div>

  <nav class="nav">
    <div class="nav-inner">
      <a href="#" class="nav-logo">QA Reports</a>
      <ul class="nav-links">
        <li><a href="#" class="active">Dashboard</a></li>
        <li><a href="#reports">Reports</a></li>
        <li><a href="#about">About</a></li>
      </ul>
      <div class="nav-date" id="navDate"></div>
    </div>
  </nav>

  <section class="hero">
    <h1>Website QA Reports</h1>
    <p>Professional reports documenting issues found during website testing.</p>
    <div class="stats">
      <div class="stat-card" data-delay="0">
        <div class="stat-label">Open Reports</div>
        <div class="stat-value open">2</div>
      </div>
      <div class="stat-card" data-delay="100">
        <div class="stat-label">Critical</div>
        <div class="stat-value critical">0</div>
      </div>
      <div class="stat-card" data-delay="200">
        <div class="stat-label">Medium</div>
        <div class="stat-value medium">1</div>
      </div>
      <div class="stat-card" data-delay="300">
        <div class="stat-label">Low</div>
        <div class="stat-value low">1</div>
      </div>
    </div>
  </section>

  <section class="reports" id="reports">
    <h2 class="section-title">Bug Reports</h2>
    <div class="report-grid">

      <!-- Bug 1 -->
      <article class="report-card" data-report="1">
        <div class="report-header">
          <span class="bug-id">BR-0001</span>
          <div class="badges">
            <span class="badge badge-open">Open</span>
            <span class="badge badge-low">Low</span>
          </div>
        </div>
        <div class="report-meta">
          <div class="meta-item">
            <label>Product</label>
            <span>Roblox Free Robux Limited</span>
          </div>
          <div class="meta-item">
            <label>Price</label>
            <span>$6</span>
          </div>
        </div>
        <div class="report-body">
          <h4>Issue</h4>
          <p>There is a spelling mistake on the main action button.</p>
          <p style="margin-top:0.5rem">Current text: <code>Earen Your Reward</code></p>
          <p>Correct text: <code>Earn Your Reward</code></p>
          <h4>Expected Result</h4>
          <p>The button should display <code>Earn Your Reward</code>.</p>
          <h4>Actual Result</h4>
          <p>The button displays <code>Earen Your Reward</code>.</p>
          <img src="bug1.png" alt="Bug screenshot" class="bug-img" onerror="this.style.display='none';this.nextElementSibling.style.display='flex'">
          <div class="img-placeholder" style="display:none">bug1.png</div>
        </div>
        <button class="copy-btn" data-bug="1">Copy Report</button>
      </article>

      <!-- Bug 2 -->
      <article class="report-card" data-report="2">
        <div class="report-header">
          <span class="bug-id">BR-0002</span>
          <div class="badges">
            <span class="badge badge-open">Open</span>
            <span class="badge badge-medium">Medium</span>
          </div>
        </div>
        <div class="report-meta">
          <div class="meta-item">
            <label>Product</label>
            <span>Roblox 5000 Giftcard Gen</span>
          </div>
          <div class="meta-item">
            <label>Price</label>
            <span>$6</span>
          </div>
        </div>
        <div class="report-body">
          <h4>Issue</h4>
          <p>After entering a username and clicking the Generate button, nothing happens. The button appears completely non-functional.</p>
          <h4>Expected Result</h4>
          <p>Clicking Generate should begin the process or provide feedback.</p>
          <h4>Actual Result</h4>
          <p>Nothing happens. No loading. No redirect. No error message.</p>
        </div>
        <button class="copy-btn" data-bug="2">Copy Report</button>
      </article>

    </div>
  </section>

  <footer id="about">
    Designed &amp; Built by Ryn
  </footer>

  <div class="toast" id="toast">
    <span class="check">✔</span>
    Report copied successfully
  </div>

  <script>
    (function () {
      // Date
      const dateEl = document.getElementById('navDate');
      const now = new Date();
      const options = { weekday: 'short', month: 'short', day: 'numeric', year: 'numeric' };
      dateEl.textContent = now.toLocaleDateString('en-US', options);

      // Custom Cursor
      const cursor = document.getElementById('cursor');
      const dot = document.getElementById('cursorDot');
      let mouseX = 0, mouseY = 0;
      let cursorX = 0, cursorY = 0;
      let dotX = 0, dotY = 0;

      document.addEventListener('mousemove', (e) => {
        mouseX = e.clientX;
        mouseY = e.clientY;
      });

      function animateCursor() {
        cursorX += (mouseX - cursorX) * 0.18;
        cursorY += (mouseY - cursorY) * 0.18;
        dotX += (mouseX - dotX) * 0.35;
        dotY += (mouseY - dotY) * 0.35;

        cursor.style.left = cursorX + 'px';
        cursor.style.top = cursorY + 'px';
        dot.style.left = dotX + 'px';
        dot.style.top = dotY + 'px';

        requestAnimationFrame(animateCursor);
      }
      animateCursor();

      const interactive = 'a, button, .copy-btn, .stat-card, .report-card';
      document.querySelectorAll(interactive).forEach(el => {
        el.addEventListener('mouseenter', () => {
          cursor.classList.add('grow');
          if (el.tagName === 'A') cursor.classList.add('link-hover');
        });
        el.addEventListener('mouseleave', () => {
          cursor.classList.remove('grow', 'link-hover');
        });
      });

      // Stats animation on load
      const statCards = document.querySelectorAll('.stat-card');
      statCards.forEach((card, i) => {
        setTimeout(() => {
          card.classList.add('visible');
        }, 150 + i * 100);
      });

      // Scroll fade-in for report cards
      const observer = new IntersectionObserver((entries) => {
        entries.forEach(entry => {
          if (entry.isIntersecting) {
            entry.target.classList.add('visible');
            observer.unobserve(entry.target);
          }
        });
      }, { threshold: 0.15 });

      document.querySelectorAll('.report-card').forEach(card => {
        observer.observe(card);
      });

      // Report data for copy
      const reports = {
        1: `Bug ID: BR-0001
Status: Open
Severity: Low
Product: Roblox Free Robux Limited
Price: $6

Issue:
There is a spelling mistake on the main action button.
Current text: "Earen Your Reward"
Correct text: "Earn Your Reward"

Expected Result:
The button should display "Earn Your Reward".

Actual Result:
The button displays "Earen Your Reward".`,

        2: `Bug ID: BR-0002
Status: Open
Severity: Medium
Product: Roblox 5000 Giftcard Gen
Price: $6

Issue:
After entering a username and clicking the Generate button, nothing happens.
The button appears completely non-functional.

Expected Result:
Clicking Generate should begin the process or provide feedback.

Actual Result:
Nothing happens.
No loading.
No redirect.
No error message.`
      };

      // Copy + ripple + toast
      const toast = document.getElementById('toast');
      let toastTimer;

      document.querySelectorAll('.copy-btn').forEach(btn => {
        btn.addEventListener('click', function (e) {
          const bugId = this.getAttribute('data-bug');
          const text = reports[bugId];

          navigator.clipboard.writeText(text).then(() => {
            clearTimeout(toastTimer);
            toast.classList.add('show');
            toastTimer = setTimeout(() => toast.classList.remove('show'), 2400);
          }).catch(() => {
            const ta = document.createElement('textarea');
            ta.value = text;
            document.body.appendChild(ta);
            ta.select();
            document.execCommand('copy');
            document.body.removeChild(ta);
            clearTimeout(toastTimer);
            toast.classList.add('show');
            toastTimer = setTimeout(() => toast.classList.remove('show'), 2400);
          });

          // Ripple
          const rect = this.getBoundingClientRect();
          const ripple = document.createElement('span');
          ripple.className = 'ripple';
          const size = Math.max(rect.width, rect.height);
          ripple.style.width = ripple.style.height = size + 'px';
          ripple.style.left = (e.clientX - rect.left - size / 2) + 'px';
          ripple.style.top = (e.clientY - rect.top - size / 2) + 'px';
          this.appendChild(ripple);
          setTimeout(() => ripple.remove(), 500);
        });
      });
    })();
  </script>
</body>
</html>
