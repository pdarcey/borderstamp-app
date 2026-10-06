# borderstamp.app

Redirects `borderstamp.app` to <https://xerodonia.com/apps/borderstamp/>.

- `index.html` redirects the home page; `404.html` is an identical copy, so every other path redirects too.
- `CNAME` sets the GitHub Pages custom domain.
- The redirect is a meta refresh plus a canonical link, with no JavaScript.

DNS for `borderstamp.app` points the apex A/AAAA records at GitHub Pages and `www` at `pdarcey.github.io`. Leave the MX records alone.
