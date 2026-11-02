---
title:
layout: single
classes: wide research-page
author-profile: false
permalink: /research/
sidebar:
  title: "Research"
  nav: sidebar-research
---
{% for section in site.data.research.sections %}
<h1 id="{{ section.id | escape }}">{{ section.title | escape }}</h1>
<ul class="research-papers">
  {% for paper in section.papers %}
  {% assign paper_id = section.id | append: '-' | append: forloop.index %}
  <li class="research-paper">
    <div class="paper-title"><strong>{{ paper.title | escape }}</strong></div>
    <div class="paper-citation">{{ paper.authors | escape }} ({{ paper.year }}).</div>
    <div class="paper-meta" aria-label="Paper details">
      {% if paper.github %}
      <a class="paper-github" href="{{ paper.github | escape }}" target="_blank" rel="noopener noreferrer">Accompanied GitHub Page</a>
      {% endif %}
      <span class="paper-status"><span class="paper-meta-label">Status:</span> {{ paper.status | escape }}</span>
      {% if paper.distinction %}
      <span class="paper-distinction"><span class="paper-meta-label">Distinction:</span> {{ paper.distinction | escape }}</span>
      {% endif %}
    </div>
    {% if paper.abstract or paper.presentations %}
    <div class="button-container">
      <div class="button-row">
        {% if paper.abstract %}
        <button type="button" class="abstract-btn" aria-expanded="false" aria-controls="{{ paper_id }}-abstract">Abstract <span class="toggle-indicator" aria-hidden="true">+</span></button>
        {% endif %}
        {% if paper.presentations %}
        <button type="button" class="talks-btn" aria-expanded="false" aria-controls="{{ paper_id }}-presentations">Invited Talks &amp; Presentations <span class="toggle-indicator" aria-hidden="true">+</span></button>
        {% endif %}
      </div>
      <div class="content-area">
        {% if paper.abstract %}
        <div id="{{ paper_id }}-abstract" hidden><blockquote>{{ paper.abstract | escape }}</blockquote></div>
        {% endif %}
        {% if paper.presentations %}
        <div id="{{ paper_id }}-presentations" hidden>
          <blockquote><ul>{% for presentation in paper.presentations %}<li>{{ presentation | escape }}</li>{% endfor %}</ul></blockquote>
        </div>
        {% endif %}
      </div>
    </div>
    {% endif %}
  </li>
  {% endfor %}
</ul>
{% endfor %}

<script>
document.addEventListener('DOMContentLoaded', function() {
  document.querySelectorAll('.research-paper .button-container').forEach(function(container) {
    const buttons = container.querySelectorAll('button[aria-controls]');
    buttons.forEach(function(button) {
      button.addEventListener('click', function() {
        const wasExpanded = button.getAttribute('aria-expanded') === 'true';
        buttons.forEach(function(otherButton) {
          const expanded = otherButton === button && !wasExpanded;
          const panel = document.getElementById(otherButton.getAttribute('aria-controls'));
          otherButton.setAttribute('aria-expanded', String(expanded));
          otherButton.querySelector('.toggle-indicator').textContent = expanded ? '−' : '+';
          panel.hidden = !expanded;
        });
      });
    });
  });
});
</script>
