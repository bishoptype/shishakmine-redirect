# ShiShak Mine redirect

`shishakmine.ru` redirects to <https://shishakmine.easydonate.ru/>.

Hosted on GitHub Pages from the `main` branch, `/ (root)`.
The destination is set in `index.html` using JavaScript and an HTML meta refresh, with a clickable fallback link.
The `CNAME` file binds the site to `shishakmine.ru`.

DNS is managed in Timeweb:

| Type | Host | Value |
| --- | --- | --- |
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | bishoptype.github.io |

Minecraft SRV and the `api` subdomain have separate records.

To change the destination, update all EasyDonate URLs in `index.html` and commit to `main`.
