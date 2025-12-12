<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>My Repository — Apple Style</title>
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
/* ---------------------- GLOBAL ---------------------- */
body {
    margin: 0;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI",
                 Roboto, Helvetica Neue, Arial, sans-serif;
    background: #ffffff;
    color: #1d1d1f;
    line-height: 1.6;
}

/* Smooth fade-in */
@keyframes fadeIn {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
}

/* ---------------------- HEADER ---------------------- */
header {
    text-align: center;
    padding: 120px 20px 80px;
    animation: fadeIn 1.2s ease-out;
}

h1 {
    font-size: 52px;
    font-weight: 700;
    margin-bottom: 10px;
    letter-spacing: -1px;
}

.subtitle {
    font-size: 22px;
    font-weight: 400;
    color: #6e6e73;
    margin-top: 0;
}

/* ---------------------- CONTENT ---------------------- */
.container {
    max-width: 900px;
    margin: 0 auto;
    padding: 0 20px 100px;
}

/* Apple-like card */
.section {
    margin-bottom: 90px;
    animation: fadeIn 1.4s ease-out;
}

.section h2 {
    font-size: 32px;
    font-weight: 600;
    margin-bottom: 20px;
    color: #1d1d1f;
}

.section p {
    font-size: 18px;
    color: #515154;
}

/* Code block — clean Apple style */
pre {
    background: #f5f5f7;
    padding: 18px 20px;
    border-radius: 12px;
    overflow-x: auto;
    font-size: 16px;
    border: 1px solid #e5e5e7;
}

code {
    color: #1d1d1f;
    font-family: "SF Mono", Consolas, "Liberation Mono", monospace;
}

/* Clean Apple-style link */
a {
    color: #0071e3;
    text-decoration: none;
    font-weight: 500;
}

a:hover {
    text-decoration: underline;
}

/* Footer */
footer {
    text-align: center;
    font-size: 14px;
    color: #6e6e73;
    padding: 50px 0 40px;
}
</style>
</head>

<body>

<header>
    <h1>My GitHub Repository</h1>
    <p class="subtitle">Simple. Elegant. Functional. Inspired by Apple.</p>
</header>

<div class="container">

    <div class="section">
        <h2>Overview</h2>
        <p>
            A clean and minimal repository page built in the visual style of Apple —
            refined typography, elegant spacing, and a focus on clarity.  
            Easily adaptable and perfect for GitHub Pages.
        </p>
    </div>

    <div class="section">
        <h2>Clone the Repository</h2>
        <pre><code>git clone https://github.com/USERNAME/REPOSITORY.git
cd REPOSITORY</code></pre>
    </div>

    <div class="section">
        <h2>Folder Structure</h2>
        <pre><code>/
├── index.html
├── assets/
│   └── images/
└── docs/
    └── readme.md</code></pre>
    </div>

    <div class="section">
        <h2>Links</h2>
        <p>Repository:  
        <a href="#">https://github.com/USERNAME/REPOSITORY</a></p>

        <p>GitHub Pages:  
        <code>https://USERNAME.github.io/REPOSITORY/</code></p>
    </div>

</div>

<footer>
    © 2025 — Apple-Inspired Repository Template
</footer>

</body>
</html>
