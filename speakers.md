---
layout: page
title: Operations of People-Centric Systems
use-site-title: true
---

# Speakers and Panelists
<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  {% for p in site.data.speakers %}
  {% if forloop.index<8 %}
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
