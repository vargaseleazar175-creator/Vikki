<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>My Repository — Apple Premium</title>
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
/* ---------------- GLOBAL STYLE ---------------- */
body {
    margin: 0;
    font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue",
                 "Segoe UI", Arial, sans-serif;
    background: #fafafa;
    color: #1d1d1f;
    overflow-x: hidden;
}

@keyframes fadeUp {
    from { opacity: 0; transform: translateY(40px); }
    to   { opacity: 1; transform: translateY(0); }
}

@keyframes fade {
    from { opacity: 0; }
    to   { opacity: 1; }
}

/* ---------------- HERO ---------------- */
.hero {
    height: 85vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    background: radial-gradient(circle at 50% 20%, #ffffff, #e5e5e7);
    padding: 0 20px;
    animation: fade 1.4s ease-out;
}

.hero h1 {
    font-size: 64px;
    font-weight: 700;
    letter-spacing: -1.5px;
    margin-bottom: 15px;
}

.hero p {
    font-size: 22px;
    color: #6e6e73;
}

/* ---------------- GLASS CARD ---------------- */
.card {
    max-width: 1000px;
    margin: 80px auto;
    padding: 50px;
    border-radius: 30px;
    background: rgba(255,255,255,0.65);
    backdrop-filter: blur(18px);
    -webkit-backdrop-filter: blur(18px);
    box-shadow: 0 30px 60px rgba(0,0,0,0.08);
    animation: fadeUp 1.2s ease-out;
}

.card h2 {
    font-size: 36px;
    margin-bottom: 18px;
}

.card p {
    font-size: 20px;
    color: #515154;
}

/* ---------------- CODE BLOCK ---------------- */
pre {
    background: #f2f2f5;
    padding: 20px;
    border-radius: 18px;
    font-size: 16px;
    overflow-x: auto;
    border: 1px solid #e0e0e2;
}

code {
    font-family: "SF Mono", monospace;
    color: #1d1d1f;
}

/* ---------------- LINKS ---------------- */
a {
    color: #0071e3;
    text-decoration: none;
    font-weight: 500;
}
a:hover { text-decoration: underline; }

/* ---------------- FOOTER ---------------- */
footer {
    text-align: center;
    padding: 60px 20px;
    color: #86868b;
    font-size: 14px;
}
</style>

</head>
<body>

<!-- HERO -->
<section class="hero">
    <div>
        <h1>My GitHub Repository</h1>
        <p>Designed with clarity, precision, and the elegance of Apple.</p>
    </div>
</section>

<!-- CONTENT CARD -->
<div class="card">
    <h2>Overview</h2>
    <p>
        This redesigned page adopts Apple’s refined design philosophy:
        soft gradients, clean typography, large breathing space,
        and a glass-morphism layer to deliver a truly premium experience.
    </p>
</div>

<div class="card">
    <h2>Clone the Repository</h2>
<pre><code>git clone https://github.com/USERNAME/REPOSITORY.git
cd REPOSITORY</code></pre>
</div>

<div class="card">
    <h2>Folder Structure</h2>
<pre><code>/
├── index.html
├── assets/
│   └── images/
└── docs/
    └── readme.md</code></pre>
</div>

<div class="card">
    <h2>Links</h2>
    <p><a href="#">GitHub Repository</a></p>
    <p><code>https://USERNAME.github.io/REPOSITORY/</code></p>
</div>

<footer>
    © 2025 — Apple-Inspired Premium Template
</footer>

</body>
</html>
