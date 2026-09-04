---
title: Accommodation
layout: default
---

# Accommodation

{{ site.conference.short_name }} {{ site.conference.year }} will take place at
{% if site.conference.venue_url %}[{{ site.conference.venue }}]({{ site.conference.venue_url }}){% else %}**{{ site.conference.venue }}**{% endif %}{% if site.conference.location %} in {{ site.conference.location }}{% endif %}.
The conference dates are
**{{ site.conference.dates.first | date: "%B %-d" }}–{{ site.conference.dates.last | date: "%B %-d, %Y" }}**.

Add room-block and booking details here as they are confirmed. Set `conference.venue_url` in `_config.yml` when there is a hotel or booking link to publish.
