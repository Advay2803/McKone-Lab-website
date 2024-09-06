---
layout: page
title: People
permalink: /people/
---
<style>
  .toggle-content {
    display: none;
    margin-top: 10px;
  }

  .toggle-button {
    cursor: pointer;
    color: #007BFF;
    font-size: 1.2em;
    font-weight: bold;
  }

  .toggle-button:hover {
    text-decoration: underline;
  }
</style>

<script>
  function toggleSection(id) {
    var content = document.getElementById(id);
    if (content.style.display === "none" || content.style.display === "") {
      content.style.display = "block";
    } else {
      content.style.display = "none";
    }
  }
</script>
<div style="text-align: center;">
  <p><strong style="font-size: 2em;">Principal Investigator</strong></p>
</div>

<div style="display: flex; align-items: center; justify-content: center; text-align: left;">
  <div style="margin-right: 25px; text-align: center;">
    <img src="https://raw.githubusercontent.com/Advay2803/advay2803.github.io/master/assets/img/James.jpg" alt="James R. McKone" style="width: 850px; height: auto;">
    <p>
      <a href="https://linkedin.com/in/pi_linkedin">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/01/LinkedIn_Logo.svg" alt="LinkedIn" style="width: 18px; height: 18px;">
      </a> |
      <a href="https://scholar.google.com/citations?user=pi_scholar_id">
        <img src="https://upload.wikimedia.org/wikipedia/commons/c/c7/Google_Scholar_logo.svg" alt="Google Scholar" style="width: 18px; height: 18px;">
      </a>
    </p>
  </div>
  <div>
    <p style="font-size: 1.5em;"><strong>Dr. James R. McKone</strong></p>
    <p>Associate Professor, Department of Chemical Engineering and Chemistry</p>
    <p style="text-align: justify;">Dr. McKone’s research focuses on advancing fundamental understanding and technology in electrochemical energy systems.</p>
  </div>
</div>

<!-- Current Members Section -->
<div style="text-align: center;">
  <p class="toggle-button" onclick="toggleSection('current-members')">Current Members &#9662;</p>
</div>
<div id="current-members" class="toggle-content">

  <!-- Current Post-Doctoral Researchers -->
  <div style="text-align: center;">
    <p class="toggle-button" onclick="toggleSection('current-postdoc')">Post-Doctoral Researchers &#9662;</p>
  </div>
  <div id="current-postdoc" class="toggle-content">
    <div style="display: flex; align-items: center; justify-content: center;">
      <div style="margin-right: 25px; text-align: center;">
        <img src="https://raw.githubusercontent.com/Advay2803/advay2803.github.io/master/assets/img/Payman.jpeg" alt="Payman Sharifi Abdar" style="width: 850px; height: auto;">
        <p>
          <a href="https://linkedin.com/in/pi_linkedin">
            <img src="https://upload.wikimedia.org/wikipedia/commons/0/01/LinkedIn_Logo.svg" alt="LinkedIn" style="width: 18px; height: 18px;">
          </a> |
          <a href="https://scholar.google.com/citations?user=pi_scholar_id">
            <img src="https://upload.wikimedia.org/wikipedia/commons/c/c7/Google_Scholar_logo.svg" alt="Google Scholar" style="width: 18px; height: 18px;">
          </a>
        </p>
      </div>
      <div>
        <p style="font-size: 1.5em;"><strong>Dr. Payman Sharifi Abdar</strong></p>
        <p>PhD, Ohio University</p>
        <p style="text-align: justify;">Dr. Payman’s research focuses on electrochemical energy systems and sustainable solutions for clean energy applications.</p>
      </div>
    </div>
  </div>

  <!-- Current Graduate Researchers -->
  <div style="text-align: center;">
    <p class="toggle-button" onclick="toggleSection('current-grad')">Graduate Researchers &#9662;</p>
  </div>
  <div id="current-grad" class="toggle-content">
    <div style="display: flex; align-items: center; justify-content: center;">
      <div style="margin-right: 25px; text-align: center;">
        <img src="https://raw.githubusercontent.com/Advay2803/advay2803.github.io/master/assets/img/Becca.jpg" alt="Rebecca Segel" style="width: 850px; height: auto;">
        <p>
          <a href="https://linkedin.com/in/pi_linkedin">
            <img src="https://upload.wikimedia.org/wikipedia/commons/0/01/LinkedIn_Logo.svg" alt="LinkedIn" style="width: 18px; height: 18px;">
          </a> |
          <a href="https://scholar.google.com/citations?user=pi_scholar_id">
            <img src="https://upload.wikimedia.org/wikipedia/commons/c/c7/Google_Scholar_logo.svg" alt="Google Scholar" style="width: 18px; height: 18px;">
          </a>
        </p>
      </div>
      <div>
        <p style="font-size: 1.5em;"><strong>Rebecca Segel</strong></p>
        <p>BS in Chemical Engineering, Case Western Reserve University</p>
        <p style="text-align: justify;">Rebecca’s research focuses on electrochemical systems and sustainable energy technologies.</p>
      </div>
    </div>
  </div>

  <!-- Current Undergraduate Researchers -->
  <div style="text-align: center;">
    <p class="toggle-button" onclick="toggleSection('current-undergrad')">Undergraduate Researchers &#9662;</p>
  </div>
  <div id="current-undergrad" class="toggle-content">
    <div style="display: flex; align-items: center; justify-content: center;">
      <div style="margin-right: 25px; text-align: center;">
        <img src="https://raw.githubusercontent.com/Advay2803/advay2803.github.io/master/assets/img/sample.jpg" alt="Undergrad Student" style="width: 850px; height: auto;">
      </div>
      <div>
        <p style="font-size: 1.5em;"><strong>Student Name</strong></p>
        <p>BS in Chemical Engineering, University Name</p>
        <p style="text-align: justify;">Research interests in electrochemical energy systems and clean energy technology.</p>
      </div>
    </div>
  </div>
</div>

<!-- Alumni Section -->
<div style="text-align: center;">
  <p class="toggle-button" onclick="toggleSection('alumni')">Alumni &#9662;</p>
</div>
<div id="alumni" class="toggle-content">

  <!-- Alumni Post-Doctoral Researchers -->
  <div style="text-align: center;">
    <p class="toggle-button" onclick="toggleSection('alumni-postdoc')">Post-Doctoral Researchers &#9662;</p>
  </div>
  <div id="alumni-postdoc" class="toggle-content">
    <div style="display: flex; align-items: center; justify-content: center;">
      <div style="margin-right: 25px; text-align: center;">
        <img src="https://raw.githubusercontent.com/Advay2803/advay2803.github.io/master/assets/img/sample.jpg" alt="Alumni Postdoc" style="width: 850px; height: auto;">
      </div>
      <div>
        <p style="font-size: 1.5em;"><strong>Dr. Alumni Name</strong></p>
        <p>PhD, University Name</p>
        <p style="text-align: justify;">Worked on electrochemical energy systems and clean energy technology.</p>
      </div>
    </div>
  </div>

  <!-- Alumni Graduate Researchers -->
  <div style="text-align: center;">
    <p class="toggle-button" onclick="toggleSection('alumni-grad')">Graduate Researchers &#9662;</p>
  </div>
  <div id="alumni-grad" class="toggle-content">
    <div style="display: flex; align-items: center; justify-content: center;">
      <div style="margin-right: 25px; text-align: center;">
        <img src="https://raw.githubusercontent.com/Advay2803/advay2803.github.io/master/assets/img/sample.jpg" alt="Alumni Graduate" style="width: 850px; height: auto;">
      </div>
      <div>
        <p style="font-size: 1.5em;"><strong>Alumni Name</strong></p>
        <p>BS in Chemical Engineering, University Name</p>
        <p style="text-align: justify;">Focused on electrochemical energy systems and clean energy technology.</p>
      </div>
    </div>
  </div>

  <!-- Alumni Undergraduate Researchers -->
  <div style="text-align: center;">
    <p class="toggle-button" onclick="toggleSection('alumni-undergrad')">Undergraduate Researchers &#9662;</p>
  </div>
  <div id="alumni-undergrad" class="toggle-content">
    <div style="display: flex; align-items: center; justify-content: center;">
      <div style="margin-right: 25px; text-align: center;">
        <img src="https://raw.githubusercontent.com/Advay2803/advay2803.github.io/master/assets/img/sample.jpg" alt="Alumni Undergraduate" style="width: 850px; height: auto;">
      </div>
      <div>
        <p style="font-size: 1.5em;"><strong>Alumni Name</strong></p>
        <p>BS in Chemical Engineering, University Name</p>
        <p style="text-align: justify;">Focused on electrochemical energy systems and clean energy technology.</p>
      </div>
    </div>
  </div>

</div>
