# hmrs-tech.github.io

Public pages of hmmrs.dev apps, published with GitHub Pages at https://hmmrs.dev/ (the custom domain is set in [`CNAME`](CNAME)).

Each app has its own folder:

| App | Page | English | Italian |
| --- | --- | --- | --- |
| Turno | Home | [`pointbuddy/index.md`](pointbuddy/index.md) | [`pointbuddy/it/index.md`](pointbuddy/it/index.md) |
| Turno | Privacy policy | [`pointbuddy/privacy/index.md`](pointbuddy/privacy/index.md) | [`pointbuddy/it/privacy/index.md`](pointbuddy/it/privacy/index.md) |

Turno is a working name (the app was called PointBuddy), so its pages stay in the `pointbuddy`
folder until the name is final. The app opens its privacy policy in its current language, so the URLs
of the two privacy pages (`/pointbuddy/privacy/` and `/pointbuddy/it/privacy/`) must not change
without updating the app. When a policy changes, update both languages and the "last updated" date
at the top of each.

The contact email and the developer name are set once, in [`_config.yml`](_config.yml), which also
sets the name, icons and stylesheet shared by all the pages of each app. Turno's pages use the
app's *Tavola* theme ([`pointbuddy/assets/tavola.css`](pointbuddy/assets/tavola.css)), with its
fonts, Fraunces and Figtree, taken from the app and licensed under the SIL Open Font License (see
`pointbuddy/assets/fonts`). The icons are exported from the app's icon generator.
