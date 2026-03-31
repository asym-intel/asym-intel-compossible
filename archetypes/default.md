---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
slug: "{{ .Name }}"
description: ""
categories: []
tags: []
featured_image: ""

# ── Cross-site graph fields ───────────────────────────────────────────────────
#
# monitors_referenced: declare which of the 7 Asymmetric Intelligence monitors
# this post connects to. Use the exact slugs below. One or many.
#
#   ai-governance               — AI capability, regulation, governance
#   conflict-escalation         — Armed conflict trajectories, military escalation
#   democratic-integrity        — Democratic erosion, state capture, resilience
#   environmental-risks         — Earth system risk, planetary boundaries
#   european-strategic-autonomy — European defence, hybrid threats, sovereignty
#   fimi-cognitive-warfare      — Foreign information manipulation, influence ops
#   macro-monitor               — Financial crisis, debt, systemic risk
#
monitors_referenced: []

# graph_tags: thematic clusters for the cross-site network graph.
# Use existing tags where possible — add new ones sparingly.
#
#   ai-governance           creative-writing        democratic-integrity
#   ecological-crisis       european-autonomy       far-right-networks
#   geopolitical-competition  hybrid-warfare        israel-palestine
#   philosophy-ethics       systems-physics         tech-power-concentration
#   ukraine-conflict        wealth-inequality
#
graph_tags: []

# post_type: essay | analysis | poetry | fiction | series-part
post_type: "essay"

# series + series_part: link parts of a multi-post series together.
# series is a slug e.g. "european-reckoning". series_part is an integer.
series: ""
series_part: null

# related_posts: slug references to other Compossible posts this explicitly
# builds on or responds to. Use the post slug, not the full URL.
related_posts: []
# ─────────────────────────────────────────────────────────────────────────────
---
