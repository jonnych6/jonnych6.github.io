---
layout: page
sitemap:
  priority: 0.9
---

<div class="intro">
  <h1>Hi, I'm Jonathan</h1>
  <h2>I'm a <span id="typed"></span></h2>
  <p class="intro-subtext">Initializing terminal on scroll... prompt: jonathan@portfolio</p>
  <a href="#timeline" class="scroll-cue">
    <div class="arrow-down"></div>
  </a>
</div>

<div class="terminal-box">
  <div class="terminal-header">
    <div class="dot red"></div>
    <div class="dot yellow"></div>
    <div class="dot green"></div>
  </div>

  <div class="terminal-content" id="terminal-content">
    <div class="boot-line">[booting up portfolio session...]</div>
    <div class="boot-line">ssh jonathan@portfolio</div>
    <div class="boot-line">jonathan@portfolio's password: S3cr3t</div> 
    <div class="boot-line">[Warning: Weak password detected]</div>
    <div class="boot-line">Access granted anyway 😅</div>
    <div><span class="prompt">jonathan@portfolio</span>:~$ <span id="line1"></span></div>
  </div>
</div>

<h2 class="section-title">Career Timeline</h2>
<!-- Start of timeline -->
<!-- Practical HelpDesk Certification -->
<div class="main-timeline" id="timeline">
  <div class="timeline-block">
    <span class="timeline-date">📜 January 9th, 2024</span>
    <div class="timeline-marker certification"></div>
    <div class="timeline-content">
      <img src="assets/img/cert-logo.png" class="timeline-logo" alt="Logo">
      <h3>Practical HelpDesk</h3>
      <h4>TCM Security</h4>
      <p class="timeline-description">Completed the Practical HelpDesk Certification by TCM Security, focusing on troubleshooting, ticketing systems, and technical support fundamentals.</p>
    </div>
  </div>
  <!-- Arctic Wolf -->
  <div class="timeline-block">
    <span class="timeline-date">🧑‍💻 August 2024 – December 2024</span>
    <div class="timeline-marker experience"></div>
    <div class="timeline-content">
      <img src="assets\img\aw-logo.png" class="timeline-logo" alt="Arctic Wolf Logo">
      <h3>Endpoint Security Developer Co-op</h3>
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

<!-- Skills Section (Filterable Tags) -->
<section class="skills-section" id="skills">
  <h2 class="section-title">My Skills</h2>

  <!-- Filter buttons -->
  <div class="filter-buttons">
    <button class="filter-btn active" data-filter="all">All</button>
    <button class="filter-btn" data-filter="programming">Programming</button>
    <button class="filter-btn" data-filter="security">Security</button>
    <button class="filter-btn" data-filter="network">Networking & Monitoring</button>
    <button class="filter-btn" data-filter="tools">Tools</button>
    <button class="filter-btn" data-filter="os">Operating Systems</button>
  </div>

  <!-- Skills tag grid -->
  <div class="skills-tags">
  <!-- Programming -->
  <span class="tag" data-category="programming">
    <img src="assets/img/skills-icons/icons8-python.svg" alt="Python icon" class="tag-icon">
    Python
  </span>
  <span class="tag" data-category="programming">
    <img src="assets/img/skills-icons/icons8-powershell.svg" alt="PowerShell icon" class="tag-icon">
    PowerShell
  </span>
  <span class="tag" data-category="programming">
    <img src="assets/img/skills-icons/icons8-bash.svg" alt="Bash icon" class="tag-icon">
    Bash
  </span>
  <span class="tag" data-category="programming">
    <img src="assets\img\skills-icons\icons8-mysql.svg" alt="SQL icon" class="tag-icon">
    SQL
  </span>
  <span class="tag" data-category="programming">
    <img src="assets\img\skills-icons\icons8-kibana.svg" alt="KQL icon" class="tag-icon">
    KQL
  </span>

  <!-- Security -->
  <span class="tag" data-category="security">
    <img src="assets\img\skills-icons\mitre.png" alt="MITRE icon" class="tag-icon">
    MITRE ATT&CK
  </span>
  <span class="tag" data-category="security">
    <img src="assets\img\skills-icons\icons8-sniper-scope-48.png" alt="Threat Hunting icon" class="tag-icon">
    Threat Hunting
  </span>
  <span class="tag" data-category="security">
    <img src="assets\img\skills-icons\splunk.png" alt="Splunk icon" class="tag-icon">
    Splunk
  </span>
  <span class="tag" data-category="security">
    <img src="assets/img/skills-icons/icons8-kibana.svg" alt="Kibana icon" class="tag-icon">
    Kibana
  </span>
  <span class="tag" data-category="security">
    <img src="assets\img\skills-icons\icons8-windows-defender.svg" alt="Sysmon icon" class="tag-icon">
    Sysmon
  </span>
  <span class="tag" data-category="security">
    <img src="assets\img\skills-icons\icons8-logs-96.png" alt="Sysmon icon" class="tag-icon">
    Windows Event Logs
  </span>

  <!-- Network -->
  <span class="tag" data-category="network">
    <img src="assets\img\skills-icons\icons8-wireshark-64.png" alt="Wireshark icon" class="tag-icon">
    Wireshark
  </span>
  <span class="tag" data-category="network">
    <img src="assets\img\skills-icons\icons8-nmap.svg" alt="Nmap icon" class="tag-icon">
    Nmap
  </span>
  <span class="tag" data-category="network">
    <img src="assets\img\skills-icons\icons8-grafana.svg" alt="Grafana icon" class="tag-icon">
    Grafana
  </span>
  <span class="tag" data-category="network">
    <img src="assets\img\skills-icons\icons8-active-directory-50.png" alt="AD icon" class="tag-icon">
    Active Directory
  </span>

  <!-- Tools -->
  <span class="tag" data-category="tools">
    <img src="assets\img\skills-icons\icons8-git-48.png" alt="Git icon" class="tag-icon">
    Git
  </span>
  <span class="tag" data-category="tools">
    <img src="assets\img\skills-icons\icons8-vs-code-48.png" alt="VS Code icon" class="tag-icon">
    VS Code
  </span>
  <span class="tag" data-category="tools">
    <img src="assets\img\skills-icons\icons8-jira.svg" alt="Jira icon" class="tag-icon">
    Jira
  </span>
  <span class="tag" data-category="tools">
    <img src="assets\img\skills-icons\icons8-confluence.svg" alt="Confluence icon" class="tag-icon">
    Confluence
  </span>
  <span class="tag" data-category="tools">
  <img src="assets\img\skills-icons\icons8-vmware-50.png" alt="VMware icon" class="tag-icon">
    VMware
  </span>
  <span class="tag" data-category="tools">
    <img src="assets\img\skills-icons\shuffle.png" alt="Shuffle icon" class="tag-icon">
    Shuffle
  </span>
  <span class="tag" data-category="tools">
    <img src="assets\img\skills-icons\icons8-bee-64.png" alt="TheHive icon" class="tag-icon">
    TheHive
  </span>
  <span class="tag" data-category="tools">
    <img src="assets\img\skills-icons\wazuh.png" alt="Wazuh icon" class="tag-icon">
    Wazuh
  </span>

  <!-- OS -->
  <span class="tag" data-category="os">
    <img src="assets\img\skills-icons\icons8-windows.svg" alt="Windows icon" class="tag-icon">
    Windows
  </span>
  <span class="tag" data-category="os">
    <img src="assets\img\skills-icons\icons8-linux-48.png" alt="Linux icon" class="tag-icon">
    Linux (Ubuntu, Kali)
  </span>
  <span class="tag" data-category="os">
    <img src="assets\img\skills-icons\icons8-mac-48.png" alt="MacOS icon" class="tag-icon">
    MacOS
  </span>
</div>

<!-- End of Skills Section -->
