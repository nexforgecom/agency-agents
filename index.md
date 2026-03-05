---
title: The Agency Roster
layout: home
nav_order: 1
---
# The Agency

A complete AI agency at your fingertips. 55+ specialized agents with personality, processes, and deliverables.

## Quick Start
Copy any agent prompt from the roster below and paste into your AI tool (Claude, ChatGPT, etc.).

## The Agency Roster

{% for div in site.data.divisions %}
### {{ div.name }}

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
{% for agent in div.agents %}
| [{{ agent.title }}]({{ agent.url }}) | {{ agent.specialty }} | {{ agent.use }} |
{% endfor %}
{% endfor %}

See full agent details by clicking the names.

## Real-World Use Cases
- Full product launch team simulation
- Rapid prototyping sprints
- Social media campaign automation
- XR/VisionOS development support

MIT License • Fork & customize freely.
