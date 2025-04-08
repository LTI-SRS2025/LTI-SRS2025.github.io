---
layout: page
title: LTI-SRS
subtitle: "The 2025 LTI Student Research Symposium"
use-site-title: true
---
<div class="venue" style="font-size: 27px; display: block; font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif; font-weight: 300; color: #404040; text-align: center;">
  (Gates & Hillman Centers (GHC) 6115, Carnegie Mellon University, April 18, 2025)
</div>

# Speaker
<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  {% for p in site.data.speakers %}
  {% if forloop.index<15 %}
  <div class="row">
    <div class="col-sm">
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    </div>
    <div class="col">
    {% capture id %}{{ p[1] }}{% endcapture %}
    {% include profile_detail.html p=p %}
    </div>
  </div>
  <br>
  {% endif %}
  {% endfor %}
</div>

# Talk Description

<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  {% for p in site.data.speakers %}
  {% if forloop.index<15 %}
  <div class="row talk-description">
    <div class="col">
      <h3>{{ p[1].name }}</h3>
      <p><strong>Title:</strong> {{ p[1].talk_title }}</p>
      <p><strong>Abstract:</strong> {{ p[1].abstract }}</p>
      {% if p[1].time %}
      <p><strong>Time:</strong> {{ p[1].time }}</p>
      {% endif %}
    </div>
  </div>
  <hr>
  {% endif %}
  {% endfor %}
</div>