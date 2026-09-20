---
---
## We have a great team!
Our team members:

{% assign people = site.data.team | sample: site.data.team.size %}
{% for person in people %}
  {% assign side = forloop.index0 | modulo: 2 %}
    {% if side == 1 %}
      {% include team-card.html %}
    {% else %}
      {% include team-card.html %}
    {% endif %}
{% endfor %}

## Become Part of our Team!
If you want to get more actively involved, we are happy to share tasks and responsibilities! 

Currently open positions:
- Moderation committee
- Public Relations committee
- Finance committee
- EDI committee

If you are interested, please reach out to us :)