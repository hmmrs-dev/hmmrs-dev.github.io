---
lang: de
title: hmmrs.dev
description: Apps von hmmrs.dev.
theme: home
hide_brand: true
translations:
  en: /
  it: /it/
stylesheets: [/turno/assets/tavola.css]
google_play_notice: Google Play und das Google Play-Logo sind Marken von Google LLC.
---

<section class="hero">
  <h1 class="wordmark">hmmrs<span>.dev</span></h1>
  <p class="lede">Kleine Apps für die Momente, die du mit anderen teilst, mit Sorgfalt gemacht von {{ site.developer }}.</p>
</section>

<h2 class="label">Apps</h2>

<ul class="apps">
  <li class="app tavola">
    <div class="app-art">
      <img src="{{ '/turno/assets/icon-192.png' | relative_url }}" alt="" width="96" height="96">
    </div>
    <div class="app-body">
      <h3 class="app-name"><a href="{{ '/turno/de/' | relative_url }}">Turno</a></h3>
      <p>Dein Begleiter am Spieltisch, um bei Gesellschaftsspielen die Punkte zu zählen.</p>
      <p class="google-play">
        <a href="{{ site.google_play.turno }}"><img src="{{ '/assets/google-play/de.svg' | relative_url }}" alt="Jetzt bei Google Play" width="239" height="71"></a>
      </p>
      <a class="app-secondary" href="{{ '/turno/de/privacy/' | relative_url }}">Datenschutzerklärung</a>
    </div>
  </li>
  <li class="app app-placeholder">
    <p>Weitere Apps folgen.</p>
  </li>
</ul>
