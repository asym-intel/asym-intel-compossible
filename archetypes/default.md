---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
slug: "{{ .Name }}"
description: ""
categories: []
tags: []
featured_image: ""
monitors_referenced: []        # e.g. ["fimi-cognitive-warfare", "democratic-integrity"]
graph_tags: []                 # thematic tags for graph clustering e.g. ["european-autonomy", "hybrid-warfare"]
post_type: "essay"             # essay | analysis | poetry | fiction | series-part
series: ""                     # e.g. "european-reckoning" — links parts together
series_part: null              # integer
related_posts: []              # slug references to other Compossible posts this builds on
---
