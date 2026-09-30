---
title: hmmrs.dev
theme: home
hide_header: true
stylesheets: [/turno/assets/tavola.css]
---

<section class="hero">
  <h1 class="wordmark">hmmrs<span>.dev</span></h1>
  <p class="lede">Small apps for the moments you share with people, made with care by {{ site.developer }}.</p>
</section>

<h2 class="label">Apps</h2>

<ul class="apps">
  <li class="app tavola">
    <div class="app-art">
      <img src="{{ '/turno/assets/icon-192.png' | relative_url }}" alt="" width="96" height="96">
    </div>
    <div class="app-body">
      <h3 class="app-name"><a href="{{ '/turno/' | relative_url }}">Turno</a></h3>
      <p>Your companion at the game table, to keep score in tabletop games.</p>
      <p class="app-meta">Android · Coming soon to Google Play</p>
      <a class="app-secondary" href="{{ '/turno/privacy/' | relative_url }}">Privacy policy</a>
    </div>
  </li>
  <li class="app app-placeholder">
    <p>More apps on the way.</p>
  </li>
</ul>
