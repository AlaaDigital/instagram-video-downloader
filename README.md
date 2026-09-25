# Instagram Video Downloader (Cloudflare Worker)

A lightweight, lightning-fast, and serverless Instagram video and reel downloader built using **Cloudflare Workers** and vanilla **JavaScript**. No heavy backend infrastructure or database required!

## 🚀 Features

* **Serverless Architecture:** Powered by Cloudflare Workers for instant global response times.
* **No Watermark:** Download Instagram videos, reels, and stories in high definition (HD / Full HD).
* **Metadata Extraction:** Automatically fetches likes, views, comments, captions, and audio info.
* **Pure Frontend:** Clean, responsive UI built with vanilla HTML/CSS/JS without heavy frameworks.

---

## 🛠️ Tech Stack

* **Backend:** Cloudflare Workers (JavaScript)
* **Frontend:** HTML5, CSS3, JavaScript (Single-file architecture)

---

## 🌐 Live Demo & Tool

Try the live version of the tool here:
👉 **[Instagram Video Downloader](https://tools.afdalbot.com/instagram-video-download/)**

---

## ⚙️ How It Works

1. The user pastes an Instagram post or reel link.
2. The Cloudflare Worker fetches the target URL with custom mobile User-Agents and headers.
3. The internal regex-based extractor parses media streams, likes, views, and captions.
4. The frontend renders the media preview and direct download buttons.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
