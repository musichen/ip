# Contributing to ip

This is a single-page static IP and location detector (`index.html`) with no build step and no backend. The page fetches `https://ipapi.co/json/` in the browser.

## Test locally

```bash
python3 -m http.server
# then open http://localhost:8000
```

Confirm the page shows your IP and location. Note that a VPN or proxy changes what you will see, and ipapi.co must be reachable from your network.

## Pull requests

Create a branch from `main`, keep the change inside `index.html`, and say what the page displayed when you tested it (you can redact your real IP in screenshots).
