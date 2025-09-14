
  <header>
    <div class="wrap">
      <h1>Teamgrow Solutions — Website Template (README)</h1>
      <p class="lead">A polished HTML README for the Teamgrow Solutions template. Use this file to learn how to run, customize, and reuse the site as a base for future projects.</p>
    </div>
  </header>

  <main class="wrap" role="main">

    <!-- Overview -->
    <section class="card" id="overview">
      <h2>Overview</h2>
      <p>This repository contains a simple, responsive, <strong>multi-section</strong> HTML template originally built for Teamgrow Solutions. It's intentionally modular and well-commented so you can reuse it as a starting point for new client sites.</p>
      <div class="grid" style="margin-top:12px">
        <div>
          <h3>Included sections</h3>
          <ul>
            <li>Hero (full-width background with overlay, headline, CTA)</li>
            <li>About (image + copy)</li>
            <li>Services (card grid)</li>
            <li>Why Choose Us (value cards)</li>
            <li>Elevator pitch banner</li>
            <li>Contact (form + sidebar contact info)</li>
            <li>Footer</li>
          </ul>
        </div>
        <div>
          <h3>Design & features</h3>
          <ul>
            <li>Responsive layout (desktop → tablet → mobile)</li>
            <li>Scroll reveal animation hooks (AOS)</li>
            <li>Unsplash placeholders for rapid prototyping</li>
            <li>Poppins font (Google Fonts) and CSS variables for easy theming</li>
            <li>Clear inline comments in the HTML/CSS for handoff</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Quick start -->
    <section class="card" id="quick-start">
      <h2>Quick start — run locally or in Codespaces</h2>
      <ol>
        <li>Clone or fork the repo to your GitHub account.</li>
        <li>Open in <strong>GitHub Codespaces</strong> (Code → Open with Codespaces) or your local editor.</li>
        <li>Make edits to <code>index.html</code>, replace images in <code>/images</code>, or change CSS variables.</li>
      </ol>

      <h3>Run with Python's simple HTTP server</h3>
      <p>From the project root (where <code>index.html</code> lives):</p>
      <pre><code>python3 -m http.server 8000</code></pre>
      <p>Open <code>http://localhost:8000</code> in your browser (or use the forwarded port URL in Codespaces).</p>

      <div class="note" style="margin-top:12px">
        <strong>Tip:</strong> If images return 404, check filenames. Use kebab-case (e.g. <code>teamgrow-logo.jpg</code>) and place images inside an <code>/images</code> folder.
      </div>
    </section>

    <!-- AI Prompts -->
    <section class="card" id="ai-prompts">
      <h2>AI prompt styles — copy & paste</h2>
      <p>Use these prompts with an AI assistant to generate variations or improved templates. Replace values inside <code>[]</code> with your specifics.</p>

      <h3>Corporate landing (starter)</h3>
      <pre><code>
"Create a responsive HTML/CSS homepage for '[Company Name]'. Include:
- full-screen hero with background image + gradient overlay
- headline + tagline + two CTAs
- About, Services (card grid), Why Choose Us, Contact form
- Use Poppins (Google Fonts), CSS variables, and include AOS scroll hooks
- Output only the HTML and CSS with inline comments"
</code></pre>

      <h3>Visual-forward agency</h3>
      <pre><code>
"Design a high-end agency landing page. Focus on large hero imagery, elegant typography, animated micro-interactions for service cards, and a case studies section. Provide accessible HTML/CSS with minimal JS and comments. Use Unsplash placeholders for images."
</code></pre>

      <h3>Theme variants generator</h3>
      <pre><code>
"Produce three theme variants for this template: 'Conservative Corporate', 'Vibrant Startup', 'Minimal Portfolio'. Implement each as CSS variable sets and include a small JS theme-switcher example."
</code></pre>

      <p><strong>Usage tip:</strong> Ask the AI to return code-only responses and to include comments marking editable areas (images, text, colors, links).</p>
    </section>

    <!-- Customization -->
    <section class="card" id="customization">
      <h2>Customization & recommended workflow</h2>
      <ul>
        <li><strong>Brand swap:</strong> Replace <code>teamgrow-logo.jpg</code> and hero image. Keep dimensions consistent (e.g., hero ~1600×900).</li>
        <li><strong>Extract CSS:</strong> Move inline styles into <code>/css/style.css</code> for maintainability.</li>
        <li><strong>Modularize:</strong> Break repeating blocks into partials (if using a static site generator or server-side framework).</li>
        <li><strong>Template branch:</strong> Keep a <code>template-base</code> branch for future projects.</li>
      </ul>

      <h3>Recommended file structure</h3>
      <pre><code>
/ (repo root)
├─ index.html
├─ README.html    ← this file (HTML README)
├─ css/
│  └─ style.css
├─ images/
│  ├─ teamgrow-logo.png
│  └─ hero.jpg
└─ assets/
   └─ ... (fonts, icons, scripts)
</code></pre>
    </section>

    <!-- Deployment -->
    <section class="card" id="deployment">
      <h2>Deployment</h2>
      <h3>GitHub Pages</h3>
      <ol>
        <li>Push your code to GitHub.</li>
        <li>Go to <strong>Settings → Pages</strong> and choose the branch (e.g., <code>main</code>) and root folder.</li>
        <li>Save and wait — the site will be published at <code>https://&lt;username&gt;.github.io/&lt;repo&gt;/</code>.</li>
      </ol>

      <h3>Vercel / Netlify</h3>
      <p>Connect your repo, configure the root as the publish directory, and deploy. Both providers detect static HTML automatically.</p>
    </section>

    <!-- Checklist -->
    <section class="card" id="checklist">
      <h2>Developer checklist</h2>
      <ul>
        <li>✅ Remove spaces from image filenames.</li>
        <li>✅ Ensure all HTML tags are properly closed (common cause of missing sections).</li>
        <li>✅ If header is fixed, add <code>padding-top</code> to <code>body</code> equal to header height.</li>
        <li>✅ Run <code>python3 -m http.server 8000</code> for local preview.</li>
        <li>✅ Replace Unsplash placeholders with real assets before production.</li>
      </ul>
    </section>

    <!-- Support -->
    <section class="card" id="support">
      <h2>Support & next steps</h2>
      <p>If you want any of the following, say which and I’ll update the template directly:</p>
      <ul>
        <li>Convert to React / Next.js or Tailwind CSS scaffold.</li>
        <li>Hook up a contact form backend (Netlify Forms / Vercel functions / simple Node endpoint).</li>
        <li>Create theme variants or a Figma-style mockup export.</li>
      </ul>
    </section>

  </main>

  <footer>
    <div style="max-width:980px;margin:0 auto;padding:14px 20px;color:var(--muted)">
      Teamgrow Solutions Template • Use this HTML README to onboard team members and speed future builds.
    </div>
  </footer>
</body>
</html>
