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
.evaluation-dropdown {
  margin: 10px 0;
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
  width: 100%;
  border-collapse: collapse;
  margin-top: 10px;
}

.evaluation-table th,
.evaluation-table td {
  padding: 8px 12px;
  text-align: left;
  border-bottom: 1px solid #ddd;
}

.evaluation-table th {
  background-color: #495057;
  color: white;
  font-weight: bold;
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
  + Schedule: <a href="https://classes.usc.edu/term/20252/catalogue/course/BUAD497/" class="btn btn--info btn--small">Summer 2025</a>
  + Syllabi: <a href="/assets/pdf/BUAD497_Syllabus_Summer_2025_Final.pdf" class="btn btn--danger btn--small">PDF</a>
  + Teaching Evaluation: 
    <div class="evaluation-dropdown">
      <button id="evaluationButton" onclick="toggleEvaluation()" class="btn btn--success btn--small">
        Show Teaching Evaluation ▼
      </button>
      <div id="evaluationContent" class="evaluation-content">
        <h4 style="color: #4a90e2; text-align: center; margin-bottom: 15px;">LEARNING EXPERIENCE SUBSCALE ANALYSIS</h4>
        <p><strong>Learning Experience Subscale Average Score</strong></p>
        
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
        
        <p style="margin-top: 15px; font-size: 0.9em; color: #666;">
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
