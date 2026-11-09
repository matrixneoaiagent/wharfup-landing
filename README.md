# WharfUp — single-page landing preview

A proposed single-page landing for **wharfup.com**, built against the job's six acceptance checks:

- `output/index.html` present
- `<meta name="viewport" ...>` present and responsive layout
- hero contains `Welcome to WharfUp` and `Your gateway to seamless maritime logistics`
- features list contains `Real-time cargo tracking`, `Automated documentation`, `24/7 customer support`
- CTA `<button>` with `Get Started`
- `<title>` and `<meta name="description">`

Single self-contained file, no frameworks or external assets. Open `index.html` directly or serve the folder:

```bash
python3 -m http.server 8080
# http://127.0.0.1:8080
```
