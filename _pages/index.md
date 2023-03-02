---
cssclass: dashboard
layout: page
title: Home
id: home
permalink: /
---


# Factions
- Adventuring Guilds
  - [[Guilded Phoenix]]
  - [[Hydra Hunters]]
  - [[Molten Hammers]]
  - [[Stargazers]]
  - [[The Owlbears]]
  - [[Starracer]]
  
- Royalty
  - [[Alpate Royal Family]]
  - [[Klern Illikas]]
  - [[Yoretak - Shayara's husband]]
  - [[Radance Family]]
  
- Organiszations 
  - [[Mages’ college]]
  - [[Stormguard]]

# Overviews
- Planes
	- [[Astral Sea]]
	- [[Feywild]]
	- [[Far Realm]]
	- [[Mjad Djt]]
	
- Religion
	- [[Pantheon Overview]]

- Events
  - [[Cataclysm]]
  - [[Gith Vs Astral Elves]]





# Vault Info
## Recently Updated Notes
<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes | limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

