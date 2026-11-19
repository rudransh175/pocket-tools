# 🧰 Pocket Tools

**100 useful tools. Each one is a single HTML file. No install. No internet. No signup. No ads. Free forever.**

Every tool site on the internet wants something from you — an account, your email, your files uploaded to their server, a subscription after the free trial. Pocket Tools is the opposite:

> **Download one `.html` file. Double-click it. It works.** On any phone or laptop, on a plane, in a village with no signal, today and in 10 years. Nothing you type or upload ever leaves your device, because there is no server — the file *is* the tool.

## ▶️ Use them right now (no download needed)

**Live demo:** open the GitHub Pages site for this repo — every tool runs in your browser.

## 📥 Keep a tool forever

1. Open the tool from [`tools/`](tools/)
2. Save the file (or download the raw `.html` from this repo)
3. Put it anywhere — phone, laptop, pen drive
4. Double-click to use it. Offline, forever.

## 🛠️ The tools — v2: 30 live

### Image
| Tool | What it does |
|---|---|
| [Image Compressor](tools/image-compressor.html) | Shrink photo file size, quality slider, before/after KB |
| [Compress to Exact Size](tools/compress-to-size.html) | Type an exact target (KB/MB) — binary-search quality, then dimensions, to hit it |
| [Exam Photo Resizer](tools/exam-photo-resizer.html) | Fit photo/signature to JEE · NEET · SSC · UPSC form KB limits |
| [Passport Photo Sheet](tools/passport-photo-sheet.html) | One photo → printable 4×6 sheet with 8 passport copies |
| [Image Converter](tools/image-converter.html) | PNG · JPG · WebP · BMP · ICO · AVIF, SVG input with scale, batch mode |
| [Image Cropper](tools/image-cropper.html) | Drag crop box, aspect presets incl. passport ratio, rotate & flip |
| [Images to PDF](tools/images-to-pdf.html) | Many images → one hand-built PDF (A4 / Letter / fit), no libraries |
| [SVG to PNG](tools/svg-to-png.html) | Paste or upload SVG → PNG at any width/scale, background of your choice |
| [Meme Maker](tools/meme-maker.html) | Top/bottom text on any image, download PNG |
| [Signature Pad](tools/signature-pad.html) | Draw a signature, download transparent PNG |
| [Color Picker](tools/color-picker.html) | HEX/RGB/HSL + shade palette, click to copy |

### Media
| Tool | What it does |
|---|---|
| [Audio Converter & Trimmer](tools/audio-converter.html) | Decode any browser-playable audio, trim, export lossless WAV |
| [Video Frame Grabber](tools/video-frame-grabber.html) | Scrub a video and grab full-resolution frames as PNG/JPEG |

### Calculators
| Tool | What it does |
|---|---|
| [EMI Calculator](tools/emi-calculator.html) | Loan EMI, total interest, year-wise table |
| [SIP Calculator](tools/sip-calculator.html) | SIP growth, invested vs gains, year by year |
| [GST Calculator](tools/gst-calculator.html) | Add/remove GST with CGST/SGST split |
| [Age Calculator](tools/age-calculator.html) | Exact age + days to next birthday |
| [Percentage Calculator](tools/percentage-calculator.html) | % of, % change, marks % |
| [CGPA Converter](tools/cgpa-converter.html) | CGPA ↔ % (CBSE ×9.5), SGPA average |
| [Unit Converter](tools/unit-converter.html) | Length, weight, temperature, data, speed, area, volume |

### Text & utility
| Tool | What it does |
|---|---|
| [Word Counter](tools/word-counter.html) | Words, chars, reading time, top words |
| [Case Converter](tools/case-converter.html) | UPPER/Title/camel/snake, sort + dedupe lines |
| [Password Generator](tools/password-generator.html) | Crypto-secure generator + strength checker |
| [JSON Tools](tools/json-tools.html) | Format, minify, validate JSON |
| [JSON ↔ CSV Converter](tools/json-csv-converter.html) | JSON array ↔ CSV both ways, quoted-field parser, preview table |
| [Markdown to HTML](tools/markdown-to-html.html) | Hand-rolled Markdown → clean HTML, live preview, safe (raw HTML escaped) |
| [Base64 / URL / Hex](tools/base64-url-tools.html) | Encode/decode, Unicode-safe |
| [Stopwatch + Timer](tools/stopwatch-timer.html) | Laps + countdown with beep |
| [Typing Test](tools/typing-test.html) | 60-second WPM + accuracy test |

## 🗺️ Roadmap to 100

v1 shipped 21; v2 adds the image/media/data batch (cropper, exact-size compressor, a much bigger converter, images-to-PDF, SVG→PNG, audio trimmer, video frame grabber, JSON↔CSV, Markdown→HTML) for 30. Coming next, in rough order: QR code generator, PDF merge, resume builder, invoice generator, screen recorder, voice recorder, file hash checker, duplicate line finder at scale, diff checker, regex tester, cron explainer, loan comparison, income-tax estimator (India, old vs new regime), attendance calculator, Pomodoro timer, dice/coin/team picker, BMI + BMR, interest (SI/CI) calculator, discount calculator, split-bill calculator, and more exam-form tools for other boards and government job forms.

**The rules never change, for every tool, forever:**
1. One tool = one `.html` file
2. Zero external requests — no CDN, no fonts, no analytics, nothing (verify it yourself: search any file for `http`)
3. No server, no accounts, no tracking — your data stays in your browser
4. Works by double-clicking the file, offline
5. Free. No premium tier is planned, ever.

## 🤝 Contributing

Found a bug, or want tool #22? Open an issue or a PR. A new tool is accepted if it follows the 5 rules above — keep it small, dependency-free, and genuinely useful to a real person.

## Why?

Tools should be *things you own*, not services you rent. A file can't shut down, can't add a paywall, can't leak your data, and can't show you an ad. Pocket Tools is a small attempt to bring that back.

---
*v1 built 2026-11-17 · 21 tools · v2 built 2026-11-19 · 29 tools · every file verified: zero external references, all scripts syntax-checked.*
