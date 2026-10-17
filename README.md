# gezik.app

The website of [Gezik](https://github.com/wenlar/gezik), a fast, light file manager.

One static page: `index.html` and `assets/`. No build step.

## Deploying

Coolify serves the repository as a static site (build pack "Static", base directory `/`,
domain `https://gezik.app`). DNS is on Cloudflare: `gezik.app` and `www` point at the
Coolify server, not proxied, so Coolify gets its own certificate.

## Updating

- The download links and the version come from the GitHub API at page load: the newest
  published release, pre-releases included. Nothing to change when a release ships.
- Screenshots in `assets/shots/` are 1280 px wide JPEGs of a demo folder (light and dark
  list, dark grid, two panes at 1500 px). Keep the performance numbers in step with
  `docs/performance.md` in the Gezik repository.
