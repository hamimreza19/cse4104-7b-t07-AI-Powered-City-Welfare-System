<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AI-Powered City Welfare System - Khulna City</title>
  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      line-height: 1.6;
      color: #24292e;
      max-width: 900px;
      margin: 0 auto;
      padding: 2rem 1rem;
      background-color: #ffffff;
    }
    h1, h2, h3 {
      border-bottom: 1px solid #eaecef;
      padding-bottom: 0.3em;
      margin-top: 1.5em;
    }
    .text-center { text-align: center; }
    .badge { display: inline-block; margin: 2px; }
    .nav-links a { margin: 0 5px; color: #0366d6; text-decoration: none; font-weight: 500; }
    .nav-links a:hover { text-decoration: underline; }
    table {
      width: 100%;
      border-collapse: collapse;
      margin: 1em 0;
    }
    th, td {
      border: 1px solid #dfe2e5;
      padding: 8px 12px;
      text-align: left;
    }
    th { background-color: #f6f8fa; }
    blockquote {
      margin: 1em 0;
      padding: 0 1em;
      color: #6a737d;
      border-left: 0.25em solid #dfe2e5;
      background-color: #f8f9fa;
    }
    code, pre {
      font-family: SFMono-Regular, Consolas, "Liberation Mono", Menlo, monospace;
      background-color: #f6f8fa;
      border-radius: 3px;
    }
    code { padding: 0.2em 0.4em; }
    pre { padding: 16px; overflow: auto; }
    hr { height: 0.25em; padding: 0; margin: 24px 0; background-color: #e1e4e8; border: 0; }
  </style>
</head>
<body>

<div class="text-center">
  <h1>🏙️ AI-Powered City Welfare System</h1>
  <h3>One platform for Khulna City: report problems, track their resolution, and understand local news with AI.</h3>

  <p>
    <img class="badge" src="https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge" alt="Status" />
    <img class="badge" src="https://img.shields.io/badge/Course-CSE%204104-Software%20Development%20III-blue?style=for-the-badge" alt="Course" />
    <img class="badge" src="https://img.shields.io/badge/Team-CSE4104--7B--T07-purple?style=for-the-badge" alt="Team" />
  </p>
  <p>
    <img class="badge" src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
    <img class="badge" src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
    <img class="badge" src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
    <img class="badge" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
    <img class="badge" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
    <img class="badge" src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
    <img class="badge" src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  </p>

  <p><strong>Northern University of Business and Technology, Khulna</strong><br />
  Department of Computer Science and Engineering</p>

  <p class="nav-links">
    <a href="#project-description">📖 Description</a> •
    <a href="#team-information">👥 Team</a> •
    <a href="#proposed-features">✨ Features</a> •
    <a href="#technology-stack">🛠️ Tech Stack</a> •
    <a href="#repository-structure">🗂️ Structure</a> •
    <a href="#roadmap">🗓️ Roadmap</a>
  </p>
</div>

<hr />

<h2 id="project-title">📌 Project Title</h2>
<p><strong>AI-Powered City Welfare System</strong>: a full-stack web platform for Khulna City, Bangladesh.</p>

<h2 id="project-description">📖 Project Description</h2>
<p>Residents of Khulna face recurring urban problems: waterlogging in the rainy season, electricity faults, uncollected garbage and lost belongings. Information about these problems is scattered across news sites, social media pages and word of mouth. Citizens cannot easily find reliable, location-specific information, and complaints have no verification or status tracking.</p>

<p>The <strong>AI-Powered City Welfare System</strong> brings four civic needs into one platform:</p>

<table>
  <thead>
    <tr>
      <th style="text-align:center;">Icon</th>
      <th>Need</th>
      <th>What the system provides</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:center;">🌧️</td>
      <td><strong>Waterlogging</strong></td>
      <td>Classified local news and citizen reports on an interactive map</td>
    </tr>
    <tr>
      <td style="text-align:center;">🎒</td>
      <td><strong>Lost and Found</strong></td>
      <td>Searchable listings with secure claim requests</td>
    </tr>
    <tr>
      <td style="text-align:center;">⚡</td>
      <td><strong>Electricity problems</strong></td>
      <td>Reports with location, photo and status tracking</td>
    </tr>
    <tr>
      <td style="text-align:center;">🗑️</td>
      <td><strong>Garbage collection</strong></td>
      <td>Collection requests assigned to teams and tracked to completion</td>
    </tr>
  </tbody>
</table>

<p>Citizens submit reports and follow their progress. Administrators verify, assign and resolve them from a dashboard. An NLP service reads local English and Bangla news, classifies waterlogging articles and extracts the affected Khulna locations.</p>

<blockquote>
  <p><strong>Design principle:</strong> AI results are always kept separate from verified facts. An incident is never marked as verified from an NLP result alone, and administrators make the final decision.</p>
</blockquote>

<h3>🎯 Objectives</h3>
<ul>
  <li>Let citizens report and track waterlogging, electricity and garbage problems, and post lost or found items.</li>
  <li>Classify local news with NLP and extract Khulna location names in English and Bangla.</li>
  <li>Show incidents and reports on an interactive map, with verified and unverified items clearly separated.</li>
  <li>Provide secure login with role-based access for citizens, administrators and optional collection staff.</li>
  <li>Give administrators a dashboard to review, verify, assign and resolve reports.</li>
  <li>Protect personal information and state clearly what the AI can and cannot do.</li>
</ul>

<h2 id="team-information">👥 Team Information</h2>
<div class="text-center">
  <table>
    <tr>
      <th>Field</th>
      <th>Details</th>
    </tr>
    <tr>
      <td><strong>Team Name</strong></td>
      <td><code>CSE4104-7B-T07</code></td>
    </tr>
    <tr>
      <td><strong>Section</strong></td>
      <td>7B</td>
    </tr>
    <tr>
      <td><strong>Course</strong></td>
      <td>CSE 4104: Software Development III</td>
    </tr>
    <tr>
      <td><strong>Team Leader</strong></td>
      <td>Alex Alin Gomes</td>
    </tr>
  </table>

  <table>
    <thead>
      <tr>
        <th style="text-align:center;">#</th>
        <th>Member</th>
        <th style="text-align:center;">Student ID</th>
        <th style="text-align:center;">Role</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="text-align:center;">1</td>
        <td>Sabbir Hossain</td>
        <td style="text-align:center;"><code>11230321293</code></td>
        <td style="text-align:center;">Member</td>
      </tr>
      <tr>
        <td style="text-align:center;">2</td>
        <td>Ahte Shamul Hoque Nadim Biswas</td>
        <td style="text-align:center;"><code>11230321297</code></td>
        <td style="text-align:center;">Member</td>
      </tr>
      <tr>
        <td style="text-align:center;">3</td>
        <td>Alex Alin Gomes</td>
        <td style="text-align:center;"><code>11230321307</code></td>
        <td style="text-align:center;">👑 Team Leader</td>
      </tr>
      <tr>
        <td style="text-align:center;">4</td>
        <td>Md Hamim Reza</td>
        <td style="text-align:center;"><code>11230321311</code></td>
        <td style="text-align:center;">Member</td>
      </tr>
    </tbody>
  </table>
</div>

<h2 id="proposed-features">✨ Proposed Features</h2>
<table>
  <thead>
    <tr>
      <th>Module</th>
      <th>Key features</th>
      <th>Role of AI</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>🌧️ <strong>Waterlogging Information</strong></td>
      <td>Collect news from permitted RSS feeds; community reports with location, photo and severity; interactive map with verified and unverified markers; admin approve, reject or resolve</td>
      <td>NLP classifies news (Waterlogging, Flood, Heavy Rainfall, Road Problem, Irrelevant) and extracts Khulna locations</td>
    </tr>
    <tr>
      <td>🎒 <strong>Lost and Found</strong></td>
      <td>Post lost or found items with photo, category, date and location; search and filter; secure claim requests; status Open, Claimed or Returned; no public phone numbers or addresses</td>
      <td>Optional text matching of similar listings</td>
    </tr>
    <tr>
      <td>⚡ <strong>Electricity Problem Reporting</strong></td>
      <td>Report outages, low voltage, damaged poles and exposed wires; map view; duplicate-report control; status flow Submitted → Under Review → Acknowledged → In Progress → Resolved</td>
      <td>None in MVP</td>
    </tr>
    <tr>
      <td>🗑️ <strong>Garbage Collection</strong></td>
      <td>Report garbage and request collection by waste category; map view; admin assigns collection teams; status flow Submitted → Approved → Assigned → Collection in Progress → Completed; basic statistics</td>
      <td>None in MVP</td>
    </tr>
  </tbody>
</table>

<h2 id="technology-stack">🛠️ Technology Stack</h2>
<table>
  <thead>
    <tr>
      <th>Layer</th>
      <th>Technology</th>
      <th>Purpose</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>🎨 <strong>Frontend</strong></td>
      <td>React.js, Tailwind CSS, React Router, Axios</td>
      <td>Responsive interface, forms, dashboards</td>
    </tr>
    <tr>
      <td>⚙️ <strong>Backend</strong></td>
      <td>Node.js, Express.js, REST API, JWT, bcrypt, Prisma ORM</td>
      <td>Authentication, business logic, database access</td>
    </tr>
    <tr>
      <td>🗄️ <strong>Database</strong></td>
      <td>PostgreSQL with PostGIS</td>
      <td>Relational data and location queries</td>
    </tr>
    <tr>
      <td>🤖 <strong>AI Integration</strong></td>
      <td>Python, FastAPI, scikit-learn, spaCy, Pandas, TF-IDF, Logistic Regression; Gemini API (optional)</td>
      <td>News classification, location extraction, optional lost and found matching</td>
    </tr>
    <tr>
      <td>🗺️ <strong>Maps</strong></td>
      <td>Leaflet, OpenStreetMap</td>
      <td>Interactive Khulna map</td>
    </tr>
    <tr>
      <td>🚀 <strong>Deployment</strong></td>
      <td>Vercel, Render or Railway, Supabase</td>
      <td>Hosting for frontend, backend, NLP service and database</td>
    </tr>
    <tr>
      <td>🧰 <strong>Tools</strong></td>
      <td>Git, GitHub, Postman, Figma, VS Code</td>
      <td>Version control, API testing, UI design</td>
    </tr>
  </tbody>
</table>

<h2 id="repository-structure">🗂️ Repository Structure</h2>
<pre><code>cse4104-7b-t07-AI-Powered-City-Welfare-System/
├── frontend/          # React application
├── backend/           # Node.js and Express REST API
├── nlp-service/       # Python FastAPI NLP service
├── documentation/     # Proposal, SRS, diagrams, reports
└── README.md</code></pre>
<blockquote>The folders above are the planned structure and will be filled in as development progresses.</blockquote>

<h2 id="roadmap">🗓️ Roadmap</h2>
<table>
  <thead>
    <tr>
      <th style="text-align:center;">Weeks</th>
      <th>Milestone</th>
      <th style="text-align:center;">Status</th>
    </tr>
  </thead>
  <tbody>
    <tr><td style="text-align:center;">1-2</td><td>Proposal, SRS, architecture, ER diagram, wireframes, GitHub setup</td><td style="text-align:center;">🟡 In progress</td></tr>
    <tr><td style="text-align:center;">3-4</td><td>Project setup, database, authentication, basic dashboard</td><td style="text-align:center;">⚪ Planned</td></tr>
    <tr><td style="text-align:center;">5-6</td><td>Waterlogging, lost and found, electricity and garbage modules</td><td style="text-align:center;">⚪ Planned</td></tr>
    <tr><td style="text-align:center;">7-8</td><td>News dataset, NLP model, NLP API and integration</td><td style="text-align:center;">⚪ Planned</td></tr>
    <tr><td style="text-align:center;">9-10</td><td>Map integration and location filtering</td><td style="text-align:center;">⚪ Planned</td></tr>
    <tr><td style="text-align:center;">11-12</td><td>Admin dashboard, verification, cross-module integration</td><td style="text-align:center;">⚪ Planned</td></tr>
    <tr><td style="text-align:center;">13</td><td>Testing, security checks, bug fixing</td><td style="text-align:center;">⚪ Planned</td></tr>
    <tr><td style="text-align:center;">14</td><td>Deployment, documentation, final presentation</td><td style="text-align:center;">⚪ Planned</td></tr>
  </tbody>
</table>

<h2 id="getting-started">🚀 Getting Started</h2>
<p>Setup and run instructions will be added as the project is built.</p>

<pre><code># Clone the repository
git clone https://github.com/hamimreza19/cse4104-7b-t07-AI-Powered-City-Welfare-System.git
cd cse4104-7b-t07-AI-Powered-City-Welfare-System</code></pre>

<hr />

<div class="text-center">
  <p><strong>Team CSE4104-7B-T07</strong> · CSE 4104 Software Development III<br />
  Northern University of Business and Technology, Khulna</p>
  <p>Made with ❤️ for the people of Khulna</p>
</div>

</body>
</html>
