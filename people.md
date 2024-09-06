---
layout: page
title: People
permalink: /people/
---

<div style="text-align: center;">
  <p><strong style="font-size: 2em;">Principal Investigator</strong></p>
</div>

<div style="display: flex; align-items: center; justify-content: center; text-align: left;">
  <!-- Image and Links Section -->
  <div style="margin-right: 25px; text-align: center;">
    <img src="https://raw.githubusercontent.com/Advay2803/advay2803.github.io/master/assets/img/James.jpg" alt="James R. McKone" style="width: 850px; height: auto; margin-bottom: 0px;">
    <p>
      <a href="https://linkedin.com/in/pi_linkedin" style="font-size: 0.7em;">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/01/LinkedIn_Logo.svg" alt="LinkedIn" style="width: 18px; height: 18px; margin-right: 5px;">
      </a> | 
      <a href="https://scholar.google.com/citations?user=pi_scholar_id" style="font-size: 0.7em;">
        <img src="https://upload.wikimedia.org/wikipedia/commons/c/c7/Google_Scholar_logo.svg" alt="Google Scholar" style="width: 18px; height: 18px; margin-right: 5px;">
      </a>
    </p>
  </div>

  <!-- Text Section -->
  <div style="margin-top: -100px;">
    <p style="font-size: 1.5em;margin-bottom: 5px;"><strong>Dr. James R. McKone</strong></p>
    <p style="font-size: 0.8em; margin-top: 5px;">Associate Professor, Department of Chemical Engineering and Chemistry</p>
    <p style="text-align: justify;">Dr. James R. McKone’s research focuses on advancing fundamental understanding and technology in the fields of electrochemical energy systems, including fuel cells and batteries. His work aims to develop efficient, sustainable, and scalable solutions for clean energy applications.</p>
  </div>
</div>

<hr>

<!-- Current Members Section -->
<div style="text-align: center;">
  <p><strong style="font-size: 2em;">Current Members</strong></p>
</div>

<!-- Dropdown Menu for Students -->
<div style="text-align: center;">
  <button onclick="toggleDropdown()" style="font-size: 1.5em; background-color: #f1f1f1; border: none; padding: 10px 20px; cursor: pointer;">Graduate Researchers</button>
</div>

<!-- Dropdown Content (hidden by default) -->
<div id="studentsDropdown" style="display: none; text-align: center; margin-top: 20px;">
  <!-- First Student -->
  <div style="display: flex; align-items: center; justify-content: center; text-align: left;">
    <div style="margin-right: 25px; text-align: center;">
      <img src="https://raw.githubusercontent.com/Advay2803/advay2803.github.io/master/assets/img/Becca.jpg" alt="Rebecca Segel" style="width: 850px; height: auto; margin-bottom: 0px;">
      <p>
        <a href="https://linkedin.com/in/student1_linkedin" style="font-size: 0.7em;">
          <img src="https://upload.wikimedia.org/wikipedia/commons/0/01/LinkedIn_Logo.svg" alt="LinkedIn" style="width: 18px; height: 18px; margin-right: 5px;">
        </a> | 
        <a href="https://scholar.google.com/citations?user=student1_scholar_id" style="font-size: 0.7em;">
          <img src="https://upload.wikimedia.org/wikipedia/commons/c/c7/Google_Scholar_logo.svg" alt="Google Scholar" style="width: 18px; height: 18px; margin-right: 5px;">
        </a>
      </p>
    </div>
    <div style="margin-top: -70px;">
      <p style="font-size: 1.5em;margin-bottom: 5px;"><strong>Rebecca Segel</strong></p>
      <p style="font-size: 0.8em; margin-top: 5px;">BS in Chemical Engineering, Case Western University, OH</p>
      <p style="text-align: justify;">Research focuses on fundamental electrochemical processes in fuel cells and batteries.</p>
    </div>
  </div>

  <!-- Add more students similarly here -->
</div>

<script>
  function toggleDropdown() {
    var dropdown = document.getElementById("studentsDropdown");
    if (dropdown.style.display === "none") {
      dropdown.style.display = "block";
    } else {
      dropdown.style.display = "none";
    }
  }
</script>
