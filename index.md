---
layout: default
title: "Rogério da Silva Yokomizo"
tagline: "Lead Developer at Airu"
---
{% include JB/setup %}

<div class="page-header">
  <a href="/"><img alt="Rogério" src="http://www.gravatar.com/avatar/5dc63b0e1394be552daf2ad84418bb40?s=220" class="img-circle me"></a>
  <h1>Rogério da Silva Yokomizo <small>In love with `git commit` and my bike (:</small></h1>
</div>

<h2>Links</h2>

<ul>
  <li><a target="_blank" href="https://coderwall.com/yokomizor" rel="nofollow">Coderwall</a></li>
  <li><a href="mailto:me@ro.ger.io" rel="nofollow">Email</a></li>
  <li><a target="_blank" href="http://www.facebook.com/profile.php?id=100003300747026l" rel="nofollow">Facebook</a></li>
  <li><a target="_blank" href="https://github.com/yokomizor" rel="nofollow">Github</a></li>
  <li><a target="_blank" href="http://br.playstation.com/publictrophy/?onlinename=yokomizor" rel="nofollow">PlayStation Network</a></li>
  <li><a href="/resume.html">Resume</a></li>
  <li><a target="_blank" href="http://steamcommunity.com/id/yokomizor" rel="nofollow">Steam</a></li>
  <li><a target="_blank" href="https://twitter.com/yokomizor" rel="nofollow">Twitter</a></li>
  <li><a target="_blank" href="http://us.battle.net/wow/en/character/nemesis/Bonigota/advanced" rel="nofollow">World of Warcraft</a></li>
</ul>

<ul>
{% for post in site.posts %}
  <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a> <span class="date">{{ post.date | date_to_string }}</span></li>
{% endfor %}
</ul>
