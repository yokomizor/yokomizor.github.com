---
layout: default
title: "Rogério&#39;s Home Page (:"
---
{% include JB/setup %}

<div class="page-header">
  <a href="/"><img alt="Rogério" src="http://www.gravatar.com/avatar/5dc63b0e1394be552daf2ad84418bb40?s=220" class="img-circle me"></a>
  <h1>Rogério&#39;s Home Page (:</h1>
</div>

<div class="row">
  <div class="span12">
    <p>Hi! My name is Rogério. I am a software developer who enjoys cycling and playing games. From São Paulo.</p>
  </div>
</div>

<h2>Links</h2>

<ul>
  <li><a href="mailto:me@ro.ger.io">Email</a></li>
  <li><a target="_blank" href="http://www.facebook.com/profile.php?id=100003300747026l">Facebook</a></li>
  <li><a target="_blank" href="https://github.com/yokomizor">Github</a></li>
  <li><a target="_blank" href="http://br.playstation.com/publictrophy/?onlinename=yokomizor">PlayStation Network</a></li>
  <li><a href="/resume.html">Resume</a></li>
  <li><a target="_blank" href="https://twitter.com/yokomizor">Twitter</a></li>
  <li><a target="_blank" href="http://us.battle.net/wow/pt/character/nemesis/Ezek/advanced">World of Warcraft</a></li>
</ul>

<h2>Posts</h2>

<ul>
{% for post in site.posts %}
  <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a> <span class="date">{{ post.date | date_to_string }}</span></li>
{% endfor %}
</ul>
