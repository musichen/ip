# ip

Simple web-based IP and location detector. Open the page and it shows the visitor information for the current connection, in the browser.

## Usage

Open `index.html` in a browser, or serve this folder with any static file server:

```bash
python3 -m http.server
# then open http://localhost:8000
```

## How it works

The page title is Visitor Information. On load it requests `https://ipapi.co/json/` and displays the returned IP and location information. There is no build step and no backend.

Note: because the lookup runs in the browser against the third-party ipapi.co service, that service sees the visitor IP, as with any IP-lookup page.

## License

GNU General Public License v3.0. See [LICENSE](LICENSE).
