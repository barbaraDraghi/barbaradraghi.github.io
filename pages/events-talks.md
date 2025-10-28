---
layout: page
title: "Events & Talks"
permalink: /pages/events-talks/
description: "Invited talks, panels, posters, and awards — with recordings, slides, and materials."
---

<section class="events-grid">
  {% assign items = site.data.events | sort: "date" | reverse %}
  {% for e in items %}
  <article class="event-card">
    <div class="event-meta">
      {% if e.date %}
        <span class="event-date">{{ e.date | date: "%b %Y" }}</span>
      {% endif %}
      {% if e.role %}
        <span class="event-role">{{ e.role }}</span>
      {% endif %}
    </div>

    {% if e.title %}
      <h3 class="event-title">{{ e.title }}</h3>
    {% endif %}
    {% if e.event %}
      <p class="event-event">{{ e.event }}</p>
    {% endif %}
    {% if e.description %}
      <p class="event-desc">{{ e.description }}</p>
    {% endif %}

    {% if e.tags %}
      <div class="event-tags">
        {% for t in e.tags %}
          <span class="tag">{{ t }}</span>
        {% endfor %}
      </div>
    {% endif %}

    {% if e.links %}
      <div class="event-links">
        {% for l in e.links %}
          {% if l.url and l.url != "" and l.url != "#" %}
            <a class="event-link" href="{{ l.url }}" target="_blank" rel="noopener">{{ l.text }}</a>
          {% else %}
            <span class="event-link disabled">{{ l.text }}</span>
          {% endif %}
        {% endfor %}
      </div>
    {% endif %}
  </article>
  {% endfor %}
</section>
