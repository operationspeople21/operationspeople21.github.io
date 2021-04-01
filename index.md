---
layout: page
title: Operations of People-Centric Systems
use-site-title: true
---

# Overview



| ------------- |:-------------:|
| **Submission** | XX, 2021   |
| **Notification** | XX, 2021 |
| **Workshop** | XX, 2021 |


<hr>

# Speakers and Panelists
<div class="container" style="margin-top: 20px;margin-bottom: 10px;">
  <div class="row">
  {% for p in site.data.speakers %}
  {% if forloop.index<=4 %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% include profile.html p=p %}
  {% endif %}
  {% endfor %}
  </div>
  <div class="row">
  {% for p in site.data.speakers %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% if forloop.index>4 and forloop.index<=10%}
  {% include profile.html p=p %}
  {% endif %}
  {% endfor %}
  </div>
  <div class="row">
  {% for p in site.data.speakers %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% if forloop.index>10%}
  {% include profile.html p=p %}
  {% endif %}
  {% endfor %}
 </div>
</div>

<div class="container" style="margin-top: 40px;margin-bottom: 10px;">
<a href="speakers">More Info</a>
</div>


<hr>

<!-- # Organizing Committee -->

<!-- prettier-ignore -->
<!-- <div class="container" style="margin-top: 25px;margin-bottom: 20px;">
  <div class="row">
    {% for p in site.data.organizers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endfor %}
  </div>
</div>

\*primary contact: nkgar6@gmail.com -->



<div class="container" style="margin-bottom: 10px;"></div>

<hr>
