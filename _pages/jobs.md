---
layout: archive
title: "JOBS"
permalink: /jobs/
author_profile: true
redirect_from:
  - /wordpress/jobs/
---

{% include base_path %}
{% capture written_label %}'None'{% endcapture %}

<style>
@import url('https://fonts.googleapis.com/css2?family=Jost:wght@200;300;400&display=swap');

body {
    font-family: 'Jost', sans-serif;
    background-color: #f0f0f0;
}

.design-section {
    width: 80%;
    max-width: 1200px;
    margin: auto;
    padding: 20px;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
}

.timeline {
    display: flex;
    flex-direction: column;
    position: relative;
}

.timeline-empty {
    height: 50px;
}

.timeline-middle {
    position: relative;
    width: 20px;
    flex-shrink: 0;
}

.timeline-circle {
    width: 20px;
    height: 20px;
    background-color: #3498db;
    border-radius: 50%;
    position: absolute;
    left: -10px;
    top: 0;
}

.timeline-component {
    padding: 20px;
    border-left: 2px solid #3498db;
    margin-bottom: 20px;
    position: relative;
}

.timeline-component::before {
    content: "";
    position: absolute;
    left: -10px;
    top: 20px;
    width: 20px;
    height: 20px;
    background-color: #3498db;
    border-radius: 50%;
}

.timeline-content h3 {
    margin: 0;
    font-size: 1.5em;
    color: #333;
}

.timeline-content p {
    margin: 0;
    font-size: 1em;
    color: #666;
}
</style>

<section class="design-section">
    <div class="timeline">
        {% for item in site.data.timeline %}
        <div class="timeline-empty"></div>
        <div class="timeline-middle">
            <div class="timeline-circle"></div>
        </div>
        <div class="timeline-component timeline-content">
            <h3>{{ item.title }}</h3>
            <p>{{ item.description }}</p>
        </div>
        {% endfor %}
    </div>
</section>
