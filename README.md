# browser-tools-core

A curated index of free, browser-based tools that **never upload your files**.

Most "free" online converters send your file to a server, keep it for some retention window, and gate the download behind a sign-up. The tools listed here do the work on your own device (WebAssembly / Canvas / JavaScript), so the file never leaves the browser tab.

## Tools

| Tool | What it does |
| --- | --- |
| [Image Converter](https://img.17maopao.com/) | PNG / JPG / WebP / HEIC conversion, cropping, compression, PDF output |
| [File Converter](https://conv.17maopao.com/) | AVIF, SVG, ICO, BMP and DXF conversions |
| [QR Code Generator](https://qr.17maopao.com/) | WiFi QR codes with an optional logo, printable PNG |
| [Invoice Generator](https://invoice.17maopao.com/) | 20+ invoice templates, clean PDF download |
| [Fancy Text](https://text.17maopao.com/) | 40+ Unicode text styles for social profiles and captions |
| [Personal Documents](https://personal.17maopao.com/) | Resume builder, business card, name badge and signature generator |

## Why this exists

Privacy claims in this category are usually about the *policy*, not the *architecture*. A converter that uploads your file can change its retention policy; a converter that runs locally cannot leak a file it never received.

All six tools above share the same constraint: no account, no upload, no server-side processing of the file you drop in.

## Contributing

Found a browser-based tool that genuinely processes files locally? Open an issue with the URL and a short note on how you verified that no upload happens (for example: DevTools → Network tab stays quiet during conversion).

## License

MIT — see [LICENSE](LICENSE).
