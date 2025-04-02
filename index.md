---
layout: page
sitemap:
  priority: 0.9
---

<div class="intro">
  <h1>Hi, I'm Jonathan</h1>
  <h2>I'm a <span id="typed"></span></h2>
  <a href="#timeline" class="scroll-cue">
    <div class="arrow-down"></div>
  </a>
</div>

<img src="{{ '/assets/img/pudhina.jpg' | prepend: site.baseurl }}" id="about-img">

<div id="describe-text">
	<p>A simple, minimal Jekyll theme for a personal web page and blog, focusing on white space and readability</p>
	<p>Fork and use the theme from the <strong> <a href="https://github.com/knhash/Pudhina"> repository</a> </strong></p>
</div>

<!-- Start of timeline -->
<!-- Arctic Wolf -->
<div class="main-timeline" id="timeline">
  <div class="timeline-block">
    <span class="timeline-date">August 2024 – December 2024</span>
    <div class="timeline-marker experience"></div>
    <div class="timeline-content">
      <img src="assets\img\aw-logo.png" class="timeline-logo" alt="Arctic Wolf Logo">
      <h3>Endpoint Security Developer</h3>
      <h4>Arctic Wolf</h4>
      <p>Details...</p>
    </div>
  </div>
  
  <!-- Sheridan College -->
  <div class="timeline-block">
    <span class="timeline-date">🎓 August 2024</span>
    <div class="timeline-marker education"></div>
    <div class="timeline-content">
      <img src="assets\img\sheridan-logo.png" class="timeline-logo" alt="Sheridan College Logo">
      <h3>Honours Bachelor of Information Sciences (Cyber Security)</h3>
      <h4>Sheridan College – Trafalgar, Oakville, Ontario</h4>
      <p>GPA: 3.76/4.0</p>
    </div>
  </div>
  <!-- Western University -->
  <div class="timeline-block">
    <span class="timeline-date">🎓 April 2020</span>
    <div class="timeline-marker education"></div>
    <div class="timeline-content">
      <img src="assets\img\western-university-logo.png" class="timeline-logo" alt="Western University Logo">
      <h3>Bachelor of Science (Double Major: Biology & Psychology)</h3>
      <h4>Western University - London, Ontario</h4>
    </div>
  </div>
</div>
  <!-- End of timeline -->

<!-- Skills Section -->
<!-- Skills Section (Filterable Tags) -->
<section class="skills-section" id="skills">
  <h2 class="section-title">My Skills</h2>

  <!-- Filter buttons -->
  <div class="filter-buttons">
    <button class="filter-btn active" data-filter="all">All</button>
    <button class="filter-btn" data-filter="programming">Programming</button>
    <button class="filter-btn" data-filter="security">Security</button>
    <button class="filter-btn" data-filter="network">Network</button>
    <button class="filter-btn" data-filter="tools">Tools</button>
    <button class="filter-btn" data-filter="os">Operating Systems</button>
  </div>

  <!-- Skills tag grid -->
  <div class="skills-tags">
    <!-- Programming -->
    <span class="tag" data-category="programming">Python</span>
    <span class="tag" data-category="programming">PowerShell</span>
    <span class="tag" data-category="programming">Bash</span>
    <span class="tag" data-category="programming">Java</span>
    <span class="tag" data-category="programming">SQL</span>
    <span class="tag" data-category="programming">KQL</span>
    <!-- Security -->
    <span class="tag" data-category="security">MITRE ATT&CK</span>
    <span class="tag" data-category="security">Threat Hunting</span>
    <span class="tag" data-category="security">Splunk</span>
    <span class="tag" data-category="security">Kibana</span>
    <span class="tag" data-category="security">Windows Event Logs</span>
    <!-- Network -->
    <span class="tag" data-category="network">Wireshark</span>
    <span class="tag" data-category="network">Active Directory</span>
    <span class="tag" data-category="network">Nmap</span>
    <span class="tag" data-category="network">Sysmon</span>
    <span class="tag" data-category="network">Grafana</span>
    <span class="tag" data-category="network">EDR Solutions</span>
    <!-- Tools -->
    <span class="tag" data-category="tools">Git</span>
    <span class="tag" data-category="tools">VS Code</span>
    <span class="tag" data-category="tools">Jira</span>
    <span class="tag" data-category="tools">Confluence</span>
    <span class="tag" data-category="tools">VMware</span>
    <span class="tag" data-category="tools">Shuffle</span>
    <span class="tag" data-category="tools">TheHive</span>
    <span class="tag" data-category="tools">Wazuh</span>
    <!-- Operating Systems -->
    <span class="tag" data-category="os">Windows</span>
    <span class="tag" data-category="os">Linux (Ubuntu, Kali)</span>
    <span class="tag" data-category="os">MacOS</span>
  </div>
</section>
<!-- End of Skills Section -->
