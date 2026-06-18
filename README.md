# 🧪 DevBox

> A private, offline-first developer toolbox that lives in a single HTML file.

DevBox bundles the small utilities developers reach for every day into one fast, dependency-free page. Open it in any browser — **everything runs locally**, so nothing you paste ever leaves your machine.

![DevBox](./screenshot.png)

## ✨ Tools included

- **JSON** — format, minify and validate with clear error messages and key counts
- **Base64** — Unicode-safe encode / decode
- **URL** — percent-encode / decode
- **JWT Decoder** — inspect header & payload (with expiry detection)
- **Hash** — SHA-1 / SHA-256 / SHA-512 via the Web Crypto API
- **UUID** — generate batches of RFC 4122 v4 IDs
- **Timestamp** — convert between Unix epoch and human dates (with relative time)
- **Color** — HEX ↔ RGB ↔ HSL with a live preview
- **Text Tools** — live char/word/line counts + case transforms (camel, snake, kebab…)

## 🚀 Usage

No build, no install:

```bash
open index.html          # macOS
xdg-open index.html      # Linux
start index.html         # Windows
```

Or just double-click the file. You can host it anywhere static (GitHub Pages, Netlify, an S3 bucket) — it's a single file.

## 🔒 Privacy

DevBox is 100% client-side vanilla JavaScript. There are no network requests, no analytics, and no dependencies. Read the source — it's all in one file.

## License

[MIT](./LICENSE)
