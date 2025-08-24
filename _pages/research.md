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
    color: #8191A6; /* Abstract button color */
  }
  .button-row button.talks-btn {
    color: #BFA084; /* Talks button color */
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
    font-style: normal;
  }
  
  /* ---------- R&R Status Banners ---------- */
  /* First Round R&R Banner */
  .status-banner-r1 {
    display: inline-block;
    background: linear-gradient(90deg, #f9fafb 0%, #e5e7eb 100%);
    border-left: 3px solid #10b981;
    color: #065f46;
    padding: 2px 10px;
    margin-left: 10px;
    font-size: 0.8rem;
    font-weight: 500;
    vertical-align: middle;
  }
  
  /* Second Round R&R Banner */
  .status-banner-r2 {
    display: inline-block;
    background: linear-gradient(90deg, #fffbeb 0%, #fef3c7 100%);
    border-left: 3px solid #f59e0b;
    color: #92400e;
    padding: 2px 10px;
    margin-left: 10px;
    font-size: 0.8rem;
    font-weight: 500;
    vertical-align: middle;
  }
  
  /* Under Review Banner (optional) */
  .status-banner-review {
    display: inline-block;
    background: linear-gradient(90deg, #f9fafb 0%, #e5e7eb 100%);
    border-left: 3px solid #6b7280;
    color: #374151;
    padding: 2px 10px;
    margin-left: 10px;
    font-size: 0.8rem;
    font-weight: 500;
    vertical-align: middle;
  }
  
  /* Accepted/Forthcoming Banner (optional) */
  .status-banner-accepted {
    display: inline-block;
    background: linear-gradient(90deg, #eff6ff 0%, #dbeafe 100%);
    border-left: 3px solid #3b82f6;
    color: #1e3a8a;
    padding: 2px 10px;
    margin-left: 10px;
    font-size: 0.8rem;
    font-weight: 500;
    vertical-align: middle;
  }

  /* ---------- Nominations ---------- */
  .nomination-link {
    color: #D99D8F;
    text-decoration: none;
    font-weight: 400; /* Normal weight, not bold */
    font-size: 50%;
    padding: 2px 6px;
    border-radius: 4px;
    transition: all 0.3s ease;
  }
  .nomination-link:hover {
    color: #C48B7D; /* Slightly darker shade for hover */
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
+ **From Cognitive to Social Tasks: How AI Transforms Organizational Demand for Human Capital in Professional Service Firms**.  
Working paper. 2025. Jia, N., Roh, A., Song, J & Wei, Y.  
  <div class="button-container">
    <div class="button-row">
      <button class="abstract-btn">Abstract +</button>
      <button class="talks-btn">Invited Talks & Presentations +</button>
    </div>
    <div class="content-area"></div>
    <div class="abstract-content" style="display:none;"><blockquote>Artificial intelligence (AI) technologies have been widely applied to tasks traditionally requiring human cognitive skills (“cognitive tasks”), yet their use in tasks requiring human social skills (“social tasks”)—particularly those involving relationship building—remains limited. We argue, however, that AI’s growing role in cognitive tasks reshapes organizational expectations of workers performing social tasks. We examine professional service firms (PSFs), which solve complex client problems by coordinating back-end functions focused on knowledge production with front-end functions centered on client interaction and relationship management. We argue that when PSFs adopt AI in back-end functions, the resulting gains in knowledge quality and speed increase the demands placed on front-end workers. Specifically, adoption of AI in back-end functions (1) requires greater time commitment, (2) raises the human capital needed, and (3) expands the number of front-end positions. To test these arguments, we analyze U.S. job postings from PSFs between 2010 and 2022, distinguishing between AI-related and non-AI-related roles as well as between back-end and front-end positions. We further leverage the 2015 launch of TensorFlow as a plausibly exogenous shock to the availability of AI applications in PSFs. Our findings strongly support our theoretical arguments. More broadly, this study suggests that through task interdependence and organizational design, AI adoption can reshape social tasks that currently make limited direct use of AI but rely heavily on AI-generated information.</blockquote></div>
    <div class="talks-content" style="display:none;"><blockquote>AIM 2025 (Marina Del Rey); WCRS 2025 (Seattle)*</blockquote></div>
  </div>

+ **Beyond Technology: How Organizations Shape Human-AI Collaboration**. <span class="status-banner-r1">1st Round R&R • Strategy Science</span>
Working paper. 2025. Jia, N., & Roh, A. 
  <div class="button-container">
    <div class="button-row">
      <button class="abstract-btn">Abstract +</button>
      <button class="talks-btn">Invited Talks & Presentations +</button>
    </div>
    <div class="content-area"></div>
    <div class="abstract-content" style="display:none;"><blockquote>The common competition-centric view of Artificial Intelligence (AI) suggests that AI and humans should be assigned to different tasks based on their respective strengths. However, there is an increasing interest in humans and AI collaborating on the same tasks, often referred to as the “ensemble” approach. Understanding and fostering this collaboration is crucial, not only to maximize AI’s impact but also to redefine human roles in the age of technology. We argue that organizations play a key role in shaping how this collaboration unfolds and the resulting outcomes. In our conceptual framework, we focus on the judgment calls that organizations and decision-makers must make when aggregating predictions from both AI and human sources on the same task. Various organizational elements can lead to deviations from optimal aggregation, influencing the effectiveness of human-AI collaboration. We contend that the success of this collaboration depends not only on the capabilities of the technology but also on the organizational structures and dynamics that guide its implementation. This study highlights that the sustained competitive advantage of AI adoption lies in an organization’s ability to foster effective human-AI collaboration.</blockquote></div>
    <div class="talks-content" style="display:none;"><blockquote>AOM 2025 (Session #10191, Copenhagen); ODC RIP (Online)</blockquote></div>
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
    <div class="talks-content" style="display:none;"><blockquote>SBE 2025 (Philadelphia); 2025 NMSRC Doctoral Conference (Online); AOM 2025 (Session #22289, Copenhagen)</blockquote></div>
  </div>

+ **Government Policy and Innovation Outcomes: Evidence from 2006 Chinese Indigenous Innovation Policy on Automation-AI Technologies**.  
Working paper. 2024. Roh, A., Miric, M., & Jia, N.
  + <a href="https://sites.google.com/view/aimanagement/aim2025?authuser=0" class="nomination-link">Finalist, AIM 2025</a>
  <div class="button-container">
    <div class="button-row">
      <button class="abstract-btn">Abstract +</button>
      <button class="talks-btn">Invited Talks & Presentations +</button>
    </div>
    <div class="content-area"></div>
    <div class="abstract-content" style="display:none;"><blockquote>To Be Updated.</blockquote></div>
    <div class="talks-content" style="display:none;"><blockquote>AIM 2025 (Marina Del Rey); The 2nd Lakeside Management Conference (Shenzhen); AOM 2025 (Session #10594, Copenhagen)</blockquote></div>
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
    <div class="talks-content" style="display:none;"><blockquote>AOM 2024 (Session #1311, Chicago); AOM 2025 (Session #11596, Copenhagen)</blockquote></div>
  </div>

# Works-in-progress
+ **Indirect Lobbying to FERC Commissioners**  
Work in progress. 2023. Hiatt, S., & Roh, A.

+ **The Differential Impact of Generative AI on Strategy Research and Researchers**  
Work in progress. 2024. Kang, H., & Roh, A.

# Pre-PhD Research
+ **Digital Ingratiation and the Strength of Weak Ties in a Digital Small World Network**.  
Working paper. 2019. Chen, S., Fan, X., Roh, A., Shi, W., & Tang, Y.
  + *Former title: Influence Activities through Social Media: Evidence from Academia*
  <div class="button-container">
    <div class="button-row">
      <button class="abstract-btn">Abstract +</button>
      <button class="talks-btn">Invited Talks & Presentations +</button>
    </div>
    <div class="content-area"></div>
    <div class="abstract-content" style="display:none;"><blockquote>To Be Updated.</blockquote></div>
    <div class="talks-content" style="display:none;"><blockquote>2021 Symposium on Contemporary Labor Economic (Online); The Asian and Australasian Society of Labour Economic (Online)</blockquote></div>
  </div>

<br><br><br><br>
