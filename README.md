# sorrel-web

Public landing site for Sorrel, the agent-native version-control project.

This repository is intentionally static and easy to host. It uses plain HTML,
CSS, and a small JavaScript enhancement file. There is no backend, build step,
package manager, or framework runtime required.

## Files

- `index.html` - landing/product page content and links.
- `styles.css` - responsive visual design (Nord theme; dark default + light mode).
- `site.js` - progressive enhancement for the sticky header and the persisted dark/light theme toggle.

## Local preview

From this directory, run any static file server. For example:

```bash
python3 -m http.server 4173
```

Then open:

```text
http://localhost:4173
```

You can also open `index.html` directly in a browser, but a local server more
closely matches static hosting behavior.

## Deployment

Deploy the repository root as a static site. Suitable targets include GitHub
Pages, Netlify, Vercel, Cloudflare Pages, or any object storage/CDN host.

Recommended settings:

- Build command: none
- Publish directory: repository root (`.`)
- Node version: not required

The page links to:

- Architecture report:
  `https://github.com/MGRAFF2006/sorrel/blob/main/AGENT_NATIVE_VERSION_CONTROL_REPORT.md`
- GitHub repo:
  `https://github.com/MGRAFF2006/sorrel`
- Roadmap/progress dashboard:
  `https://github.com/MGRAFF2006/sorrel/blob/main/SORREL_PROGRESS.md`
