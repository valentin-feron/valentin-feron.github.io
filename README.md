# valentin-feron.github.io

Website of Valone IT, served by GitHub Pages at https://valone-it.fr.
Plain HTML and one stylesheet: no build step, no JavaScript, no external resources.

| Path | Page |
| --- | --- |
| `/` · `/fr/` | Home |
| `/caravan-and-crown/privacy/` · `/fr/caravan-and-crown/privacy/` | Caravan & Crown privacy policy (data deletion: `#delete-data`) |
| `/legal-notice/` · `/fr/mentions-legales/` | Legal notice / mentions légales |
| `/app-ads.txt` | AdMob authorized sellers |
| `/404.html` | Not-found page |

`.nojekyll` keeps GitHub Pages from running Jekyll. `CNAME` holds the custom domain.

## To do

- `app-ads.txt`: replace `pub-XXXXXXXXXXXXXXXX` with the real AdMob publisher ID.
- `index.html`, `fr/index.html`: replace the "Coming soon" badge with the Play Store link (see the HTML comment).
- Privacy policy: update the "last updated" date in both languages whenever it changes.

## Preview locally

```sh
python3 -m http.server 8000
```
