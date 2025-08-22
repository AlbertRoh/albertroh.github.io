---
title: 
layout: single
classes: wide
author-profile: false
permalink: /research/
sidebar:
  title: "Research"
  nav: sidebar-research
---
<style>
  .button-container {
    display: block;
    margin-top: 8px;
    margin-left: 2em;
  }
  .button-row {
    display: block;
    margin-bottom: 10px;
  }
  .button-row button {
    background: none;
    border: none;
    cursor: pointer;
    padding: 0;
    margin-right: 20px;
    font-family: inherit;
    font-size: inherit;
    text-decoration: none;
    outline: none; /* Remove the focus outline */
  }
  .button-row button:focus {
    outline: none; /* Remove focus outline */
  }
  .button-row button.abstract-btn {
    color: #80990000; /* Abstract button color */
  }
  .button-row button.talks-btn {
    color: #804169e1; /* Talks button color */
  }
  .button-row button:hover {
    text-decoration: underline;
  }
  .content-area {
    display: block;
    min-height: 0;
  }
  .content-area blockquote {
    margin: 10px 0;
    padding: 10px;
    background-color: #f9f9f9;
    border-left: 3px solid #ddd;
  }
</style>
<script>
document.addEventListener('DOMContentLoaded', function() {
  const containers = document.querySelectorAll('.button-container');
  
  containers.forEach(container => {
    const abstractBtn = container.querySelector('.abstract-btn');
    const talksBtn = container.querySelector('.talks-btn');
    const contentArea = container.querySelector('.content-area');
    const abstractContent = container.querySelector('.abstract-content').innerHTML;
    const talksContent = container.querySelector('.talks-content').innerHTML;
    
    let currentContent = null; // Track which content is currently shown
    
    abstractBtn.addEventListener('click', function() {
      if (currentContent === 'abstract') {
        // If abstract is already showing, close it
        contentArea.innerHTML = '';
        currentContent = null;
      } else {
        // Show abstract content (whether nothing was showing or talks was showing)
        contentArea.innerHTML = abstractContent;
        currentContent = 'abstract';
      }
    });
    
    talksBtn.addEventListener('click', function() {
      if (currentContent === 'talks') {
        // If talks is already showing, close it
        contentArea.innerHTML = '';
        currentContent = null;
      } else {
        // Show talks content (whether nothing was showing or abstract was showing)
        contentArea.innerHTML = talksContent;
        currentContent = 'talks';
      }
    });
  });
});
</script>
<div style="margin-top:10px;"></div> <!-- -30px -->
# Publications
# Working Papers
+ **How AI Shapes Non-AI Positions: Evidence from Professional Service Firms**.  
Working paper. 2025. Jia, N., Roh, A., Song, J & Wei, Y.  
  <div class="button-container">
    <div class="button-row">
      <button class="abstract-btn">Abstract +</button>
      <button class="talks-btn">Invited Talks & Presentations +</button>
    </div>
    <div class="content-area"></div>
    <div class="abstract-content" style="display:none;"><blockquote>To Be Updated.</blockquote></div>
    <div class="talks-content" style="display:none;"><blockquote>To Be Updated.</blockquote></div>
  </div>

+ **Beyond Technology: How Organizations Shape Human-AI Collaboration**.  
Working paper. 2025. Jia, N., & Roh, A. 
  <div class="button-container">
    <div class="button-row">
      <button class="abstract-btn">Abstract +</button>
      <button class="talks-btn">Invited Talks & Presentations +</button>
    </div>
    <div class="content-area"></div>
    <div class="abstract-content" style="display:none;"><blockquote>The common competition-centric view of Artificial Intelligence (AI) suggests that AI and humans should be assigned to different tasks based on their respective strengths. However, there is an increasing interest in humans and AI collaborating on the same tasks, often referred to as the “ensemble” approach. Understanding and fostering this collaboration is crucial, not only to maximize AI’s impact but also to redefine human roles in the age of technology. We argue that organizations play a key role in shaping how this collaboration unfolds and the resulting outcomes. In our conceptual framework, we focus on the judgment calls that organizations and decision-makers must make when aggregating predictions from both AI and human sources on the same task. Various organizational elements can lead to deviations from optimal aggregation, influencing the effectiveness of human-AI collaboration. We contend that the success of this collaboration depends not only on the capabilities of the technology but also on the organizational structures and dynamics that guide its implementation. This study highlights that the sustained competitive advantage of AI adoption lies in an organization’s ability to foster effective human-AI collaboration.</blockquote></div>
    <div class="talks-content" style="display:none;"><blockquote>AOM 2025 (Session #10191)</blockquote></div>
  </div>

+ **Substitution Over Compliance? Strategic Innovation between Data Privacy and Security Under Regulatory Scrutiny**.  
Working paper. 2024. Roh, A., Jia, N., & Miric, M. 
  <div class="button-container">
    <div class="button-row">
      <button class="abstract-btn">Abstract +</button>
      <button class="talks-btn">Invited Talks & Presentations +</button>
    </div>
    <div class="content-area"></div>
    <div class="abstract-content" style="display:none;"><blockquote>To Be Updated.</blockquote></div>
    <div class="talks-content" style="display:none;"><blockquote>To Be Updated.</blockquote></div>
  </div>

+ **Government Policy and Innovation Outcomes: Evidence from 2006 Chinese Indigenous Innovation Policy on Automation-AI Technologies**.  
Working paper. 2024. Roh, A., Miric, M., & Jia, N.
  <div class="button-container">
    <div class="button-row">
      <button class="abstract-btn">Abstract +</button>
      <button class="talks-btn">Invited Talks & Presentations +</button>
    </div>
    <div class="content-area"></div>
    <div class="abstract-content" style="display:none;"><blockquote>To Be Updated.</blockquote></div>
    <div class="talks-content" style="display:none;"><blockquote>To Be Updated.</blockquote></div>
  </div>

+ **Generative AI for Enhanced Management Research: Analyzing Policy Environment for Firms' Technology Development Based on Congressional Hearings**.  
Working paper. 2023. Roh, A., Miric, M., & Jia, N.
  <div class="button-container">
    <div class="button-row">
      <button class="abstract-btn">Abstract +</button>
      <button class="talks-btn">Invited Talks & Presentations +</button>
    </div>
    <div class="content-area"></div>
    <div class="abstract-content" style="display:none;"><blockquote>To Be Updated.</blockquote></div>
    <div class="talks-content" style="display:none;"><blockquote>To Be Updated.</blockquote></div>
  </div>

# Works-in-progress
+ **Indirect Lobbying to FERC Commissioners**  
Work in progress. 2023. Hiatt, S., & Roh, A.

+ **The Differential Impact of Generative AI on Strategy Research and Researchers**  
Work in progress. 2024. Kang, H., & Roh, A.

# Pre-PhD research
+ **Digital Ingratiation and the Strength of Weak Ties in a Digital Small World Network**.  
Working paper. 2019. Chen, S., Fan, X., Roh, A., Shi, W., & Tang, Y.
  <div class="button-container">
    <div class="button-row">
      <button class="abstract-btn">Abstract +</button>
      <button class="talks-btn">Invited Talks & Presentations +</button>
    </div>
    <div class="content-area"></div>
    <div class="abstract-content" style="display:none;"><blockquote>To Be Updated.</blockquote></div>
    <div class="talks-content" style="display:none;"><blockquote>To Be Updated.</blockquote></div>
  </div>

<br><br><br><br>
