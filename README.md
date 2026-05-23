# chepherd.org

Static landing page for [chepherd](https://github.com/chepherd/chepherd).

Served via GitHub Pages from `chepherd/chepherd.github.io`, fronted by the apex domain `chepherd.org` (CNAME).

## Files

- `index.html` — single-file landing page; mirrors the k9s palette + the W1 dashboard mockup
- `install.sh` — universal installer fetched via `curl -fsSL https://chepherd.org/install.sh | sh`
- `favicon.svg` — single-letter `c` mark on the brand background
- `CNAME` — `chepherd.org` for GitHub Pages

## Development

This is a single static HTML file. No build step. Edit `index.html`, push to main, GitHub Pages serves the update within ~1 minute.

## DNS

apex `chepherd.org` → GitHub Pages (`185.199.108.153`, `109`, `110`, `111`).

## Badges

The GitHub stats badges in the header pull live data from `img.shields.io` at page-load time + on tab-visibility-change. No server needed.

## License

Same as the main project — MIT.
