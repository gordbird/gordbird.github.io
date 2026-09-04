# Gordon Bird portfolio

A small, dependency-free personal portfolio built with plain HTML and CSS.

## Local preview

From this directory, run a local static server:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## GitHub Pages

Create the public repository `gordbird/gordbird.github.io`, push the `main` branch, and enable Pages from **Settings -> Pages -> Deploy from a branch**. Select `main` and `/ (root)`.

The user site will be available at <https://gordbird.github.io/> after the first deployment.

## Custom domain

When a domain is chosen, add a `CNAME` file containing the domain name, then configure DNS with the registrar. GitHub's Pages settings will provide the final HTTPS status after the DNS record has propagated.
