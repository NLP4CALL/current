---
title: This year's edition of the Workshop
permalink: /current/
alias: /current/current/
---

{% capture current %}{{site.data.editions.first.year}}{% endcapture %}
{% capture title %}{{site.data.editions.first.long_name}}{% endcapture %}
# {{title}}
{% include editions/{{current | append:".md"}} %}
{{current}}
