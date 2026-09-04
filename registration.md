---
title: Registration
layout: default
weight: 3
---

# Registration

Registration and payment are handled on the [virtual conference site](https://virtual.aistats.org/Conferences/2026). Prefer that portal for checkout rather than rebuilding registration here.

## Meeting dates

{{ site.conference.short_name }} {{ site.conference.year }} meets
{{ site.conference.dates.first | date: "%B %-d" }}–{{ site.conference.dates.last | date: "%B %-d, %Y" }}
{% if site.conference.location %} in {{ site.conference.location }}{% endif %}
{% if site.conference.venue %} at {{ site.conference.venue }}{% endif %}.

See [Key Dates]({{ "dates.html" | relative_url }}) for registration-related deadlines from `_config.yml`.
