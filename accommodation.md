---
title: Accommodation
layout: default
---

# Accommodation

{{ site.conference.short_name }} {{ site.conference.year }} will take place at
**{{ site.conference.venue }}**{% if site.conference.location %} in {{ site.conference.location }}{% endif %}.
The conference dates are
**{{ site.conference.dates.first | date: "%B %-d" }}–{{ site.conference.dates.last | date: "%B %-d, %Y" }}**.

Hotel booking and live room-block details are on the virtual Hotels page:

{% if site.conference.venue_url %}[{{ site.conference.venue_url }}]({{ site.conference.venue_url }}){% else %}[virtual.aistats.org Hotels](https://virtual.aistats.org/Conferences/2026/Hotels){% endif %}
