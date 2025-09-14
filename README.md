<!doctype html>

<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>README — Teamgrow Solutions Website Template</title>
  <style>
    :root{
      --bg:#f6f9fb;
      --card:#ffffff;
      --accent:#0ea5a4;
      --muted:#556074;
      --text:#0b2436;
      --mono: ui-monospace, SFMono-Regular, Menlo, Monaco, "Roboto Mono", "Courier New", monospace;
    }
    body{font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; margin:0; background:var(--bg); color:var(--text); line-height:1.5;}
    header{background:linear-gradient(90deg,#e6faf8, #f1fbff); padding:28px 20px; border-bottom:1px solid #e6eef2}
    .wrap{max-width:980px;margin:28px auto;padding:0 20px}
    h1{font-size:28px;margin:0 0 8px}
    p.lead{color:var(--muted);margin:0 0 18px}
    .card{background:var(--card);border-radius:12px;padding:20px;box-shadow:0 8px 30px rgba(11,36,54,0.06);margin-bottom:18px}
    h2{font-size:18px;margin:0 0 12px}
    pre{background:#0b2436;color:#e6fbf8;padding:12px;border-radius:8px;overflow:auto;font-family:var(--mono);font-size:13px}
    code{background:#f3f7f9;padding:2px 6px;border-radius:6px;font-family:var(--mono);font-size:13px}
    ul{margin:0 0 12px 20px}
    .grid{display:grid;grid-template-columns:1fr 1fr;gap:14px}
    .note{background:#fff9f2;border-left:4px solid #ffb74d;padding:12px;border-radius:8px;color:#6b4a00}
    footer{color:var(--muted);font-size:13px;text-align:center;padding:18px 0}
    @media (max-width:820px){.grid{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <header>
    <div class="wrap">
      <h1>Teamgrow Solutions — Website Template (README)</h1>
      <p class="lead">This HTML README explains how this multi-section homepage works, how to use it as a reusable template for future projects, AI prompt suggestions to create similar or better sites, and instructions to run it in Codespaces or locally.</p>
    </div>
  </header>

  <main class="wrap">
    <section class="card">
      <h2>What this repo is</h2>
      <p>
        This repository contains a clean, responsive <strong>single-page / multi-section</strong> HTML template built as the Teamgrow Solutions homepage. It is intentionally simple and well-commented so it can be used as a base (template) for other websites you will build in the future.
      </p>

```
  <div class="grid" style="margin-top:12px">
    <div>
      <h3>Included sections</h3>
      <ul>
        <li>Hero (full-width background with overlay, headline, CTA)</li>
        <li>About (image + copy)</li>
        <li>Services (four-card grid)</li>
        <li>Why Choose Us (value cards)</li>
        <li>Elevator Pitch banner</li>
        <li>Contact (form + contact info)</li>
        <li>Footer</li>
      </ul>
    </div>

    <div>
      <h3>Design & features</h3>
      <ul>
        <li>Responsive layout (desktop → mobile)</li>
        <li>Smooth AOS scroll animation hooks (AOS library included)</li>
        <li>High-quality Unsplash placeholders for quick prototyping</li>
        <li>Elegant typography (Poppins via Google Fonts)</li>
        <li>Clearly commented HTML/CSS to speed customization</li>
      </ul>
    </div>
  </div>
</section>

<section class="card">
  <h2>How to use this template (quick)</h2>
  <ol>
    <li>Clone or fork the repo into your GitHub account.</li>
    <li>Open the repo in <strong>GitHub Codespaces</strong> or your local editor.</li>
    <li>Replace placeholder images (logo, hero, section images) located in <code>/images</code> or referenced in the HTML.</li>
    <li>Edit text content (title, tagline, service items) directly in <code>index.html</code>.</li>
    <li>Run a local static server to preview (instructions below).</li>
  </ol>

  <h3>Run locally (simple HTTP server)</h3>
  <p>From your project folder (where <code>index.html</code> lives):</p>
  <pre><code>python3 -m http.server 8000</code></pre>
  <p>Open <code>http://localhost:8000</code> in your browser.</p>

  <h3>Run in GitHub Codespaces</h3>
  <ol>
    <li>Open the repo in Codespaces (GitHub → Code → Open with Codespaces).</li>
    <li>In the Codespaces terminal run:
      <pre><code>python3 -m http.server 8000</code></pre>
    </li>
    <li>Open the forwarded port in Codespaces preview (port 8000) or click the link Codespaces provides. The site will be served from the workspace.</li>
  </ol>

  <div class="note">
    <strong>Note:</strong> If you see 404s for images, check file names. Avoid spaces in filenames (use <code>teamgrow-logo.jpg</code> or <code>teamgrow_logo.png</code>).
  </div>
</section>

<section class="card">
  <h2>AI prompt styles — reuse & extend</h2>
  <p>Use these prompt templates with an AI (ChatGPT, Claude, etc.) to produce variations of this site or generate higher-fidelity alternatives. Replace bracketed values with your details.</p>

  <h3>1. Clean corporate landing (starter)</h3>
  <pre><code>
```

"Create a responsive HTML/CSS homepage for a business called '\[Company Name]'.
Include: full-screen hero with background image and gradient overlay, headline, short tagline, two CTAs.
Add About, Services (grid of cards), Why Choose Us, Contact form, and footer.
Use modern typography, subtle shadows, and smooth scroll-reveal animations (AOS).
Provide well-commented HTML and CSS and use Unsplash placeholders for images." </code></pre>

```
  <h3>2. Aesthetic agency site (visual-forward)</h3>
  <pre><code>
```

"Design a high-end agency landing page. Focus on large hero imagery, elegant typography (Poppins), branded accent color, animated micro-interactions for service cards, and a 'case studies' section.
Produce accessible HTML/CSS with minimal JS and clear comments for handoff." </code></pre>

```
  <h3>3. Generate variants & accessibility improvements</h3>
  <pre><code>
```

"Create three color & layout variants for the given HTML template: 'Conservative Corporate', 'Vibrant Startup', 'Minimal Portfolio'. Include CSS variables for quick theme swap. Ensure contrast and include skip-to-content link for accessibility." </code></pre>

```
  <p><strong>Tip:</strong> Ask the AI to output code only (no extra commentary) and to include inline comments marking where to edit text, images, and colors.</p>
</section>

<section class="card">
  <h2>How to adapt the template for future projects</h2>
  <ul>
    <li><strong>Branding swap:</strong> Replace <code>teamgrow logo.jpg</code> and the hero image — keep the layout.</li>
    <li><strong>Content swap:</strong> Replace text blocks and service lists to match each new client's offerings.</li>
    <li><strong>Modularize:</strong> Move CSS into <code>/css/style.css</code> and images into <code>/images</code> so each new project just swaps those folders.</li>
    <li><strong>Templates:</strong> Keep a base branch called <code>template-base</code> with the clean scaffold and copy for new projects.</li>
  </ul>

  <h3>Example file structure (recommended)</h3>
  <pre><code>
```

/ (repo root)
├─ index.html
├─ README.html         ← (this file, HTML README)
├─ css/
│  └─ style.css
├─ images/
│  ├─ teamgrow-logo.png
│  └─ hero.jpg
└─ assets/
└─ ... (fonts, icons, scripts) </code></pre> </section>

```
<section class="card">
  <h2>Deployment</h2>
  <h3>GitHub Pages (quick)</h3>
  <ol>
    <li>Push your branch to GitHub.</li>
    <li>Go to repository → Settings → Pages → Source → choose the main branch and the folder (usually <code>/ (root)</code>).</li>
    <li>Save — GitHub Pages will publish at <code>https://&lt;your-username&gt;.github.io/&lt;repo&gt;</code>.</li>
  </ol>

  <h3>Vercel / Netlify</h3>
  <p>Both support static HTML sites. Connect your repo and hit Deploy — they automatically detect and publish. Use the production domain or a custom domain you own.</p>
</section>

<section class="card">
  <h2>Developer notes & checklist</h2>
  <ul>
    <li>✅ Remove spaces from image filenames. Use kebab-case or snake_case.</li>
    <li>✅ Ensure all HTML tags are properly closed (common cause of missing sections).</li>
    <li>✅ If header is fixed, add <code>padding-top</code> to <code>body</code> or the main wrapper equal to header height.</li>
    <li>✅ For local dev, run <code>python3 -m http.server 8000</code> or use Live Server extension.</li>
    <li>✅ Replace placeholder Unsplash URLs with client-supplied images before production.</li>
    <li>✅ Optional: extract CSS into external file and minify for production.</li>
  </ul>
</section>

<section class="card">
  <h2>Contact & support</h2>
  <p>If you want me to:</p>
  <ul>
    <li>Convert this template into a React component or Tailwind-based scaffold — ask and I’ll produce the code.</li>
    <li>Set up a contact form backend (Netlify Functions, Vercel Serverless, or a simple server endpoint) — tell me your preferred provider and I’ll add examples.</li>
    <li>Produce additional theme variants or a Figma-style visual mockup — I can export assets and provide design notes.</li>
  </ul>
</section>
```

  </main>

  <footer>
    <div style="max-width:980px;margin:0 auto;padding:14px 20px;color:var(--muted)">
      Teamgrow Solutions Template • Use this HTML README to onboard team members and speed future builds.
    </div>
  </footer>
</body>
</html>
