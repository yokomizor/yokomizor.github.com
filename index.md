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

<h3>Professional</h3>

<ul>
  <li><a target="_blank" href="https://www.behance.net/yokomizor" rel="nofollow">Behance</a></li>
  <li><a target="_blank" href="https://coderwall.com/yokomizor" rel="nofollow">Coderwall</a></li>
  <li><a target="_blank" href="https://github.com/yokomizor" rel="nofollow">Github</a></li>
  <li><a target="_blank" href="https://www.linkedin.com/in/rogério-yokomizo-ab9b928a" rel="nofollow">Linkedin</a></li>
  <li><a target="_blank" href="/resume_rogerio_da_silva_yokomizo.pdf">Resume</a></li>
</ul>

<h3>Social</h3>

<ul>
  <li><a target="_blank" href="https://www.instagram.com/pobrejapa/" rel="nofollow">Instagram</a></li>
  <li><a target="_blank" href="https://www.facebook.com/rogerio.yokomizo.9" rel="nofollow">Facebook</a></li>
  <li><a target="_blank" href="https://twitter.com/yokomizor" rel="nofollow">Twitter</a></li>
</ul>

<h3>Gaming</h3>

<ul>
  <li><a target="_blank" href="https://playoverwatch.com/en-us/career/pc/eu/bonigota-2124" rel="nofollow">Overwatch</a> (<a target="_blank" href="https://playoverwatch.com/en-us/career/pc/eu/bonigota-2124" rel="nofollow">PC</a>, <a target="_blank" href="https://playoverwatch.com/en-us/career/psn/bonigota" rel="nofollow">PS4</a>)</li>
  <li><a target="_blank" href="http://br.playstation.com/publictrophy/?onlinename=yokomizor" rel="nofollow">PlayStation Network</a></li>
  <li><a target="_blank" href="http://steamcommunity.com/id/yokomizor" rel="nofollow">Steam</a></li>
  <li><a target="_blank" href="http://us.battle.net/wow/en/character/nemesis/Bonigota/advanced" rel="nofollow">World of Warcraft</a></li>
</ul>

<ul>
{% for post in site.posts %}
  <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a> <span class="date">{{ post.date | date_to_string }}</span></li>
{% endfor %}
</ul>
