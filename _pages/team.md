---
layout: page
title: team
permalink: /team/
description: Group members of the Heejung Shim Lab.
nav: true
nav_order: 2
---

<p><strong>We are looking for new PhD students, Postdocs, and Master/undergraduate students to join the team</strong> (<a href="{{ '/vacancies/' | relative_url }}">see openings</a>)!</p>

<p>Jump to <a href="#staff">current members</a>, <a href="#students">master and undergraduate students</a>, <a href="#alumni">alumni</a>.</p>

## Staff & PhD Students {#staff}
<div class="row row-cols-1 row-cols-md-2">
  {% for member in site.data.team_members %}
    {% include team_card.liquid member=member %}
  {% endfor %}
</div>

## Master and Undergraduate Students {#students}
<div class="row row-cols-1 row-cols-md-2">
  {% for member in site.data.students %}
    {% include team_card.liquid member=member %}
  {% endfor %}
</div>

## Alumni {#alumni}
<div class="row row-cols-1 row-cols-md-2">
  {% for member in site.data.alumni_members %}
    {% include team_card.liquid member=member %}
  {% endfor %}
</div>

### Former Visitors, Bachelor & Master Students
<div class="row">
  <div class="col-md-4">
    <h5>Visitors</h5>
    <ul>
      {% for member in site.data.alumni_visitors %}<li>{{ member.name }}</li>{% endfor %}
    </ul>
  </div>
  <div class="col-md-4">
    <h5>Master Students</h5>
    <ul>
      {% for member in site.data.alumni_msc %}<li>{{ member.name }}</li>{% endfor %}
    </ul>
  </div>
  <div class="col-md-4">
    <h5>Bachelor Students</h5>
    <ul>
      {% for member in site.data.alumni_bsc %}<li>{{ member.name }}</li>{% endfor %}
    </ul>
  </div>
</div>
