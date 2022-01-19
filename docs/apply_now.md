---
layout: default
title: Apply Now!
---

## Apply Now

Jump to our recruitment site to apply for one of the following positions:

 * [Developer](./roles/developer.md) -
    You deploy, test, program, design, analyze and/or support running our software.
 * [Team Coach](./roles/team_coach.md) -
    You coach the people in and around our software teams to grow individually and as a team.

<ul>
{% for page in site.pages %} 
{% if page.layout == "role" %}
<li> <a href="{{ page.url | absolute_url }}">{{ page.role }}</a> - You love {{ page.specialization }}.</li>
{% endif %} 
{% endfor %}
</ul>


Or:
 
 * [Open application](https://recruitment.logiqs.nl/open-application/) -
    You do what you do, we just don't have a role for it yet.
