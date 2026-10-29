---
lang: it
title: hmmrs.dev
description: App di hmmrs.dev.
theme: home
hide_brand: true
translations:
  en: /
  de: /de/
stylesheets: [/turno/assets/tavola.css]
google_play_notice: Google Play e il logo Google Play sono marchi di Google LLC.
---

<section class="hero">
  <h1 class="wordmark">hmmrs<span>.dev</span></h1>
  <p class="lede">Piccole app per i momenti che condividi con gli altri, fatte con cura da {{ site.developer }}.</p>
</section>

<h2 class="label">App</h2>

<ul class="apps">
  <li class="app tavola">
    <div class="app-art">
      <img src="{{ '/turno/assets/icon-192.png' | relative_url }}" alt="" width="96" height="96">
    </div>
    <div class="app-body">
      <h3 class="app-name"><a href="{{ '/turno/it/' | relative_url }}">Turno</a></h3>
      <p>Il tuo compagno al tavolo da gioco, per tenere il punteggio nei giochi da tavolo.</p>
      <p class="google-play">
        <a href="{{ site.google_play.turno }}"><img src="{{ '/assets/google-play/it.svg' | relative_url }}" alt="Disponibile su Google Play" width="239" height="71"></a>
      </p>
      <a class="app-secondary" href="{{ '/turno/it/privacy/' | relative_url }}">Informativa sulla privacy</a>
    </div>
  </li>
  <li class="app app-placeholder">
    <p>Altre app in arrivo.</p>
  </li>
</ul>
