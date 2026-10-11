---
layout: default
title: Hidden Berkeley
---

# Explore UC Berkeley

This guide helps students who are new to UC Berkeley find useful places and services around campus. It includes libraries, student support, and places to explore, with official links for more information.

<!-- Edit the heading and introduction above. The supplied loop below displays each row of the CSV. -->
{% for resource in site.data.locations %}

### {{ resource.name | escape }}

**Category:** {{ resource.category | escape }}  
**Area:** {{ resource.area | escape }}  
**Access note:** {{ resource.access_note | escape }}  
<a href="{{ resource.source_url | escape }}">Official source</a>

{% endfor %}

---

The entries come from this project's CSV. Confirm current details using the official links.
