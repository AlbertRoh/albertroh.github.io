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
/* ---------- Button color overrides ---------- */
.btn.btn--info {
  background-color: #8191A6 !important;
  border-color: #8191A6 !important;
  color: #ffffff !important;
}
.btn.btn--danger {
  background-color: #BFA084 !important;
  border-color: #BFA084 !important;
  color: #ffffff !important;
}
.btn.btn--success {
  background-color: #8C6F5E !important;
  border-color: #8C6F5E !important;
  color: #ffffff !important;
}
.btn:hover { filter: brightness(0.92); }

/* ---------- Evaluation section layout ---------- */
.evaluation-inline {
  display: inline-block;   /* keep button on same line as label */
  margin-left: 8px;
  vertical-align: middle;
}

.evaluation-content {
  display: none;
  margin-top: 15px;
  padding: 15px;
  background-color: #f8f9fa;
  border-radius: 5px;
  border: 1px solid #dee2e6;
}
.evaluation-content.show { display: block; }

/* ---------- Table formatting (full width) ---------- */
.evaluation-table {
  width: 100%;               /* fill available width */
  margin: 0;                 /* no centering margin */
  border-collapse: collapse;
}
.evaluation-table th,
.evaluation-table td {
  padding: 10px 12px;
  border-bottom: 1px solid #ddd;
}
.evaluation-table th {
  background-color: #495057;
  color: #ffffff;
  font-weight: bold;
}
/* column alignment: 1st left, 2nd & 3rd centered */
.evaluation-table th:nth-child(1),
.evaluation-table td:nth-child(1) { text-align: left; }
.evaluation-table th:nth-child(2),
.evaluation-table td:nth-child(2),
.evaluation-table th:nth-child(3),
.evaluation-table td:nth-child(3) { text-align: center; }

/* optional emphasis for the numeric scores */
.score-highlight { font-weight: bold; }
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
  + Teaching Evaluation: <span class="evaluation-inline">
      <button id="evaluationButton" onclick="toggleEvaluation()" class="btn btn--success btn--small">
        Show Teaching Evaluation ▼
      </button>
    </span>
    <div id="evaluationContent" class="evaluation-content">

      <table class="evaluation-table">
        <!-- control column proportions so the table doesn't look skewed -->
        <colgroup>
          <col style="width:60%">
          <col style="width:20%">
          <col style="width:20%">
        </colgroup>
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

      <p style="margin-top: 12px; font-size: 0.9em; color: #666;">
        <em>Scores based on a 4-point scale. Data represent student feedback on learning experience subscales.</em>
      </p>
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
