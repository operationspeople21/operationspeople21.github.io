---
layout: page
title: Operations of People-Centric Systems
use-site-title: true
---

# Organizing Committee

<!-- # Organizing Committee -->

<!-- prettier-ignore -->
<div class="container" style="margin-top: 25px;margin-bottom: 20px;">
  <div class="row">
    {% for p in site.data.organizers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endfor %}
  </div>
</div>

\*primary contact: ngarg@cornell.edu

# Program Committee

<ul>
{% for thing in site.data.pc.pc %}
<li>{{thing}}</li>
{% endfor %}
</ul>
