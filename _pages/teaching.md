---
title: 
layout: single
classes: wide
author-profile: false
permalink: /teaching/
sidebar:
  title: "Teaching"
  nav: sidebar-teaching
---

<style>
/* Custom button colors */
.btn--custom1 {
  background-color: #8191A6;
  color: white;
}

.btn--custom1:hover {
  background-color: #6b7a91;
}

.btn--custom2 {
  background-color: #CEE1F2;
  color: #333;
}

.btn--custom2:hover {
  background-color: #b8d4ea;
}

.btn--custom3 {
  background-color: #BFA084;
  color: white;
}

.btn--custom3:hover {
  background-color: #a88c6f;
}

.evaluation-dropdown {
  margin: 0;
  display: inline-block;
  margin-left: 10px;
}

.evaluation-content {
  display: none;
  margin-top: 15px;
  padding: 15px;
  background-color: #f8f9fa;
  border-radius: 5px;
  border: 1px solid #dee2e6;
}

.evaluation-content.show {
  display: block;
}

.evaluation-table {
  width: 80%;
  border-collapse: collapse;
  margin: 10px auto;
  text-align: center;
}

.evaluation-table th,
.evaluation-table td {
  padding: 8px 12px;
  border-bottom: 1px solid #ddd;
}

.evaluation-table th {
  background-color: #495057;
  color: white;
  font-weight: bold;
  text-align: center;
}

.evaluation-table td:first-child {
  text-align: left;
}

.evaluation-table td:nth-child(2),
.evaluation-table td:nth-child(3) {
  text-align: center;
}

.score-highlight {
  font-weight: bold;
  color: #007bff;
}
</style>

<script>
function toggleEvaluation() {
  var content = document.getElementById("evaluationContent");
  var button = document.getElementById("evaluationButton");
  
  if (content.classList.contains("show")) {
    content.classList.remove("show");
    button.textContent = "Show Teaching Evaluation ▼";
  } else {
    content.classList.add("show");
    button.textContent = "Hide Teaching Evaluation ▲";
  }
}
</script>

<div style="margin-top:10px;"></div>

# University of Southern California
+ **Strategic Management**, *Instructor* (BUAD497; UG)
  + Schedule: <a href="https://classes.usc.edu/term/20252/catalogue/course/BUAD497/" class="btn btn--custom1 btn--small">Summer 2025</a>
  + Syllabi: <a href="/assets/pdf/BUAD497_Syllabus_Summer_2025_Final.pdf" class="btn btn--custom2 btn--small">PDF</a>
  + Teaching Evaluation: <div class="evaluation-dropdown">
      <button id="evaluationButton" onclick="toggleEvaluation()" class="btn btn--custom3 btn--small">
        Show Teaching Evaluation ▼
      </button>
      <div id="evaluationContent" class="evaluation-content">
        <h4 style="color: #4a90e2; text-align: center; margin-bottom: 15px;">LEARNING EXPERIENCE SUBSCALE ANALYSIS</h4>
        <p style="text-align: center;"><strong>Learning Experience Subscale Average Score</strong></p>
        
        <table class="evaluation-table">
          <thead>
            <tr>
              <th>Competency</th>
              <th>Course-instructor</th>
              <th>Standard Deviation</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>Course Design</td>
              <td class="score-highlight">3.72</td>
              <td>+/-0.45</td>
            </tr>
            <tr>
              <td>Instructional Practices</td>
              <td class="score-highlight">3.68</td>
              <td>+/-0.47</td>
            </tr>
            <tr>
              <td>Inclusion Practices</td>
              <td class="score-highlight">3.62</td>
              <td>+/-0.51</td>
            </tr>
            <tr>
              <td>Assessment Practices</td>
              <td class="score-highlight">3.59</td>
              <td>+/-0.52</td>
            </tr>
            <tr>
              <td>Course Impact</td>
              <td class="score-highlight">3.63</td>
              <td>+/-0.52</td>
            </tr>
          </tbody>
        </table>
        
        <p style="margin-top: 15px; font-size: 0.9em; color: #666; text-align: center;">
          <em>Scores based on 4-point scale. Data represents student feedback on learning experience subscales.</em>
        </p>
      </div>
    </div>

+ **Strategic Management**, *Teaching Assistant* (BUAD497; UG)
  + Spring 2025
+ **Essentials and Digital Frontiers of Big Data**, *Guest Speaker* (DSO-428, UG)<br />  
  + Spring 2025
  + Content: Class on transformers architecture, attention model & application of large language models with coding session
+ **Applied Product Management**, *Guest Speaker* (MOR-531, MBA)
  + Spring 2025
  + Content: Class on introduction to large language models and their applications for managers
+ **Seminar in Strategic Management**, *Guest Speaker* (MOR-603, Ph.D.)
  + Fall 2024
  + Content: Class on transformers architecture, attention model & application of large language models in management science studies
