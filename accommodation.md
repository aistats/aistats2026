---
title: Accommodation
layout: default
---

# Accommodation

{{ site.conference.short_name }} {{ site.conference.year }} will take place at
{% if site.conference.venue_url %}[{{ site.conference.venue }}]({{ site.conference.venue_url }}){% else %}**{{ site.conference.venue }}**{% endif %}{% if site.conference.location %} in {{ site.conference.location }}{% endif %}.
The conference dates are
**{{ site.conference.dates.first | date: "%B %-d" }}–{{ site.conference.dates.last | date: "%B %-d, %Y" }}**.

Room-block and booking notes for organisers belong on this page (or in `_doc/`). Link `conference.venue_url` in `_config.yml` to the hotel or booking page when you have one; do not treat virtual.aistats.org as the default accommodation source.
