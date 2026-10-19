# hmmrs-dev.github.io

Public pages of hmmrs.dev apps, published with GitHub Pages at https://hmmrs.dev/ (the custom domain is set in [`CNAME`](CNAME)).

Each app has its own folder:

| App | Page | English | Italian | German |
| --- | --- | --- | --- | --- |
| Turno | Home | [`turno/index.md`](turno/index.md) | [`turno/it/index.md`](turno/it/index.md) | [`turno/de/index.md`](turno/de/index.md) |
| Turno | Privacy policy | [`turno/privacy/index.md`](turno/privacy/index.md) | [`turno/it/privacy/index.md`](turno/it/privacy/index.md) | [`turno/de/privacy/index.md`](turno/de/privacy/index.md) |

The app opens its privacy policy in its current language, so the URLs of the privacy pages
(`/turno/privacy/`, `/turno/it/privacy/` and `/turno/de/privacy/`) must not change without updating
the app. When a policy changes, update every language and the "last updated" date at the top of each.

The contact email and the developer name are set once, in [`_config.yml`](_config.yml), which also
sets the name, icons and theme shared by all the pages of each app.

Every page has a theme switch (same as the browser, light or dark), which saves the chosen theme in
the browser, and a language switch to its translations, which each page lists under `translations`
in its front matter: a new translation is added to the `translations` of the pages it translates. The
names of the languages, in the order the switch shows them, and the switches' words are in
[`_data/languages.yml`](_data/languages.yml). The colors of each theme are written as
`light-dark(light, dark)`, so that they follow the chosen one.

Each app's page and its tile link to its Google Play listing, set under `google_play` in
[`_config.yml`](_config.yml), with Google's *Get it on Google Play* badge in the page's language
([`assets/google-play`](assets/google-play)). The badges are downloaded as they are from Google's
[Partner Marketing Hub](https://partnermarketinghub.withgoogle.com/brands/google-play/google-play/lockups-icons-badges/#badges),
whose guidelines ask not to change them and to leave a quarter of their height of clear space around
them. A page with a badge sets `google_play_notice` to Google's trademark notice, in its language,
and the layout shows it in the footer.

The home page, in English ([`index.md`](index.md)) and Italian ([`it/index.md`](it/index.md)), links
to each app's pages in the same language. It is black and white, and shows each app as a tile in the
app's own theme, so it's easy to recognize: the top of the tile shows the icon on the theme's `--art`
color. A theme is a stylesheet that restyles the elements with its class: Turno's pages and its
tile use the app's *Tavola* theme ([`turno/assets/tavola.css`](turno/assets/tavola.css)), with its
fonts, Fraunces and Figtree, taken from the app and licensed under the SIL Open Font License (see
`turno/assets/fonts`). The icons are exported from the app's icon generator.
