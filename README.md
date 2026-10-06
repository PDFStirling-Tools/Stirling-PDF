<p align="center">
  <img src="docs/logo.svg" width="120" alt="Stirling PDF logo">
</p>

<h1 align="center">Stirling PDF</h1>

<p align="center">
  <b>Your all-in-one PDF toolkit that works anywhere: browser, phone or desktop.</b><br>
  Edit, convert, sign and protect documents. Self-hosted, private, free.
</p>

<p align="center">
  <a href="https://github.com/mitshelshzo/REPO_NAME/releases/latest"><img src="https://img.shields.io/github/v/release/mitshelshzo/REPO_NAME?style=for-the-badge&color=7C3AED&label=release" alt="Release"></a>
  <a href="https://github.com/mitshelshzo/REPO_NAME/stargazers"><img src="https://img.shields.io/github/stars/mitshelshzo/REPO_NAME?style=for-the-badge&color=7C3AED" alt="Stars"></a>
  <a href="https://github.com/mitshelshzo/REPO_NAME/blob/main/LICENSE"><img src="https://img.shields.io/github/license/mitshelshzo/REPO_NAME?style=for-the-badge&color=06B6D4" alt="License"></a>
  <a href="https://github.com/mitshelshzo/REPO_NAME/commits/main"><img src="https://img.shields.io/github/last-commit/mitshelshzo/REPO_NAME?style=for-the-badge&color=06B6D4" alt="Last commit"></a>
</p>

<p align="center">
  <a href="#-quick-start">Quick start</a> •
  <a href="#-features">Features</a> •
  <a href="#-why-project_name">Why us</a> •
  <a href="#%EF%B8%8F-roadmap">Roadmap</a> •
  <a href="#-contributing">Contributing</a>
</p>

<p align="center">
  <img src="docs/screenshot.png" width="85%" alt="PROJECT_NAME screenshot">
</p>

---

## ✨ Features

<table>
<tr>
<td width="50%" valign="top">

### 📝 Edit
- Add, move and edit text and images
- Rotate, reorder and delete pages
- Annotate, highlight and draw

### 🔄 Convert
- PDF ⇄ Word, Excel, PowerPoint
- PDF ⇄ images (PNG, JPG, WebP)
- HTML and Markdown to PDF

</td>
<td width="50%" valign="top">

### 🧩 Organize
- Merge many files into one
- Split by pages, ranges or size
- Compress without visible quality loss

### 🔐 Secure
- Password protection and removal
- Digital signatures
- Redaction of sensitive data
- Watermarks

</td>
</tr>
</table>

> 🔍 **OCR included:** turn scanned documents into searchable, selectable text.

---

## 🚀 Quick start

### Docker (recommended)

```bash
docker run -d \
  --name PROJECT_NAME \
  -p 8080:8080 \
  -v ./data:/app/data \
  ghcr.io/mitshelshzo/REPO_NAME:latest
```

Then open **http://localhost:8080** in your browser.

<details>
<summary><b>🐳 Docker Compose</b></summary>

```yaml
services:
  app:
    image: ghcr.io/mitshelshzo/REPO_NAME:latest
    container_name: Stirling PDF
    ports:
      - "8080:8080"
    volumes:
      - ./data:/app/data
    restart: unless-stopped
```

```bash
docker compose up -d
```
</details>

<details>
<summary><b>💻 Desktop app</b></summary>

Download the installer for your system from the
[latest release](https://github.com/mitshelshzo/REPO_NAME/releases/latest):

| System  | File |
|---------|------|
| Windows | `Stirling PDFE-setup.exe` |
| macOS   | `Stirling PDF.dmg` |
| Linux   | `Stirling PDF.AppImage` |
</details>

<details>
<summary><b>🛠 Build from source</b></summary>

```bash
git clone https://github.com/mitshelshzo/REPO_NAME.git
cd REPO_NAME
# install & run commands here
```
</details>

---

## 💡 Why Stirling PDF?

| | **Stirling PDF** | Online PDF services |
|---|:---:|:---:|
| Files stay on your machine | ✅ | ❌ |
| Free, no page limits | ✅ | ⚠️ |
| Works offline | ✅ | ❌ |
| No account needed | ✅ | ⚠️ |
| Open source | ✅ | ❌ |

---

## ⚙️ Configuration

| Variable | Default | Description |
|----------|---------|-------------|
| `PORT` | `8080` | Port the app listens on |
| `LANG` | `en` | Interface language |
| `MAX_FILE_SIZE` | `100MB` | Upload size limit |

---

## 🗺️ Roadmap

- [x] Core editing tools
- [x] Docker image
- [ ] Mobile-friendly interface
- [ ] Batch processing
- [ ] Plugin system
- [ ] More interface languages

Have an idea? [Open an issue](https://github.com/mitshelshzo/REPO_NAME/issues/new) 💬

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a branch: `git checkout -b feature/my-idea`
3. Commit your changes: `git commit -m "Add my idea"`
4. Push and open a Pull Request

Found a bug? [Report it here](https://github.com/mitshelshzo/REPO_NAME/issues).

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

<p align="center">
  Made with 💜 by <a href="https://github.com/mitshelshzo">@mitshelshzo</a><br>
  <sub>If you like the project, give it a ⭐, it really helps!</sub>
</p>

