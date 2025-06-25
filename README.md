<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tech Hive</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background: #f7f9fb;
      color: #222;
    }
    header {
      background: linear-gradient(90deg, #1e3cfd, #1fa2ff);
      color: white;
      padding: 2rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
    }
    .region-buttons {
      margin-top: 1rem;
    }
    .region-buttons button {
      background: rgba(255,255,255,0.2);
      border: none;
      color: white;
      margin: 0 5px;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      cursor: pointer;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1rem;
      padding: 2rem;
    }
    .card {
      background: white;
      border-radius: 10px;
      padding: 1.5rem;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    }
    .card h3 {
      margin-top: 0;
    }
    .tag {
      display: inline-block;
      background: #ddd;
      padding: 2px 8px;
      margin: 2px;
      border-radius: 4px;
      font-size: 0.75rem;
    }
    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
    }
    .btn {
      display: inline-block;
      background: #3366ff;
      color: white;
      padding: 0.5rem 1rem;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Explore. Optimize. Contribute.</h1>
    <p>One Automation Community.</p>
    <div class="region-buttons">
      <button>Europe</button>
      <button>Asia</button>
      <button>America</button>
    </div>
  </header>

  <section class="grid">
    <div class="card" style="background: #2563eb; color: white">
      <h3>Power Automate</h3>
      <p>Discover connectors, use cases, and ready-to-use workflow templates.</p>
      <p>120+ Flows, 45 Connectors</p>
      <a href="#" class="btn">Explore</a>
    </div>
    <div class="card" style="background: #f97316; color: white">
      <h3>Zflow</h3>
      <p>Ready-made templates and approval process automations.</p>
      <p>85+ Templates, 30 Processes</p>
      <a href="#" class="btn">Explore</a>
    </div>
    <div class="card" style="background: #10b981; color: white">
      <h3>Other Tools</h3>
      <p>Explore SAP Automation, Python scripts, and RPA bots.</p>
      <span class="tag">SAP Tools</span>
      <span class="tag">Python</span>
      <span class="tag">RPA Bots</span><br>
      <a href="#" class="btn">Explore</a>
    </div>
  </section>

  <section class="grid">
    <div class="card">
      <h3>Templates & Best Practices</h3>
      <ul>
        <li>Expense Approval Flow</li>
        <li>Customer Onboarding</li>
        <li>Data Migration Tool</li>
      </ul>
      <a href="#" class="btn">View All Templates</a>
    </div>
    <div class="card">
      <h3>Workflow Optimization</h3>
      <p>Processing Time: -35%</p>
      <p>Error Rate: -42%</p>
      <p>User Adoption: +28%</p>
      <a href="#" class="btn" style="background:#c084fc">View Optimization Guide</a>
    </div>
    <div class="card">
      <h3>Latest Automation News</h3>
      <ul>
        <li>Zflow 2.0 Released (New)</li>
        <li>Power Automate Connectors (Update)</li>
        <li>RPA Bot Training Session (Event)</li>
      </ul>
      <a href="#" class="btn" style="background:#facc15; color:black">View All Updates</a>
    </div>
  </section>

  <section class="grid">
    <div class="card">
      <h3>Innovation Challenges</h3>
      <p>Customer Support Automation – 32 submissions</p>
      <a href="#" class="btn">View All Challenges</a>
    </div>
    <div class="card">
      <h3>Discussion Forums</h3>
      <ul>
        <li>SAP Integration Issues (12 replies)</li>
        <li>HR Flow Optimization (8 replies)</li>
      </ul>
      <a href="#" class="btn">Join Discussions</a>
    </div>
    <div class="card" style="background: #3b82f6; color: white">
      <h3>Submit Your Automation Idea</h3>
      <p>Guides, Videos, Documentation</p>
      <a href="#" class="btn">Submit Now</a>
    </div>
  </section>

  <section class="grid">
    <div class="card">
      <h3>Featured Automations</h3>
      <ul>
        <li>Invoice Processing – 85% time saved</li>
        <li>Employee Onboarding – 70% time saved</li>
        <li>Data Migration Tool – 92% time saved</li>
        <li>Customer Support Bot – 65% time saved</li>
      </ul>
    </div>
  </section>

  <footer>
    <p><strong>Tech Hive</strong> — One Automation Community</p>
    <p><a href="#" style="color:white">About</a> | <a href="#" style="color:white">Contact</a> | <a href="#" style="color:white">Help Center</a> | <a href="#" style="color:white">Privacy Policy</a></p>
  </footer>
</body>
</html>
