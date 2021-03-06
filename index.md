---
layout: page
title: Operations of People-Centric Systems
use-site-title: true
---

Operations has traditionally considered decision-making (including queuing, scheduling, pricing, routing) from the perspective of a single firm. However, in several recent socio-economic developments -- for example, modern online platforms, decentralized energy generation, and decentralized ledgers -- the requisite decisions are instead distributed among many independent people. While these crowd-based operations disrupt centrally controlled practices, they empower individuals and enable new applications. Whether intermediated by a centralized platform or wholly decentralized, the operations of these systems are complicated by the underlying complex network structures, the challenges of large-scale alignment of incentives, and of learning from data. Moreover, the decentralized and people-centric nature of processes on these platforms entails working with “indirect” operational levers such as recommendations, signaling, information design, and user interface design. They further pose additional constraints pertaining to fairness and ethics.

This workshop will bring together researchers from across operations
management, computer science, and economics to explore new challenges and research directions of such crowd-based systems.

Potential areas include:

<ul>
<li>Operations with crowds and volunteers</li>
<li>Distributed ledgers and payment systems</li>
<li>Decentralized energy markets and cloud energy storage</li>
<li>Crowdfunding and micro-investing</li>
<li>Decentralized decision-making and crowdsourced democracy</li>
<li>Operational challenges in sharing economy and online labor platforms</li>
<li>Achieving operational goals through information design, recommendations, and other new levers</li>
</ul>

<!-- <br/> -->

Please see the [call](/cfp/) for submission information.


| ------------- |:-------------:|
| **Submission** | May 21, 2021, **Anywhere on Earth**   |
| **Notification** | June 28, 2021 |
| **Workshop** | July 23, 2021 |


<hr>

# Keynote Speakers
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

# Panelists
<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  {% for p in site.data.panelists %}
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

<!-- <hr> -->






<div class="container" style="margin-bottom: 10px;"></div>

<hr>
