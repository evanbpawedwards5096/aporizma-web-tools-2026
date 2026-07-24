# Aporizma v2026 - web tools 2026

> **Aporizma is a browser-first set of privacy-respecting web utilities for GitHub Pages. The tools run locally in the browser, with the current release maintained at version 2026.**

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/evanbpawedwards5096/aporizma-web-tools-2026?style=flat-square)](https://github.com/evanbpawedwards5096/aporizma-web-tools-2026)

---

<p align="center">
  <a href="https://evanbpawedwards5096.github.io/aporizma-web-tools-2026/">
    <img src="https://img.shields.io/badge/Download-Aporizma%20Latest-brightgreen?style=for-the-badge" alt="Download Aporizma">
  </a>
</p>

> **[Download Aporizma v2026](https://evanbpawedwards5096.github.io/aporizma-web-tools-2026/)**

---

[Download Latest Build](https://evanbpawedwards5096.github.io/aporizma-web-tools-2026/)

---

## What is Aporizma?

Aporizma provides a collection of static web tools that operate directly in the browser instead of transferring information to a server. It is intended for fast, lightweight utility access through a static website that can be published or hosted with GitHub Pages.

The browser handles the work locally, so the project does not require uploads or account registration. Its bilingual strings also support presenting the interface in multiple languages while preserving a simple GitHub Pages workflow.

---

## Highlights

- Browser-only operation
- User data does not need to be uploaded
- No registration or sign-in
- No built-in tracking
- Delivered as a static website
- Ready for GitHub Pages hosting
- Bilingual string support
- Collection of lightweight browser tools

---

## Installation

Download the repository files or clone the project, then make them available through a static host.

1. Clone the repository:

   ```bash
   git clone https://github.com/evanbpawedwards5096/aporizma-web-tools-2026.git
   ```

2. Open the project through a local server, or deploy it to GitHub Pages.

3. For local testing, use any static web server to serve the project directory and open the entry page in a browser.

   Example:

   ```bash
   npx serve aporizma
   ```

---

## Using Aporizma

After the files are hosted, use Aporizma as you would any regular website. Visit the page, select a tool, and work with the results in the browser.

A standard session looks like this:

1. Navigate to the hosted site.
2. Select the required tool or page.
3. Provide input locally in the browser.
4. Inspect the result without communicating with a backend.
5. Reload the page or move to another tool whenever needed.

Project maintainers can change the static files and deploy the updated version to the existing hosting location.

---

## Configuration

Aporizma is configured through its static site files.

To change wording, labels, or language content, edit the relevant HTML files and associated assets in the repository. Bilingual interface text should be updated in the string resources where those values are defined.

Example structure:

```json
{
  "language": "bilingual",
  "hosting": "GitHub Pages",
  "mode": "static"
}
```

---

## Requirements

- A current modern web browser
- A host capable of serving static files
- GitHub Pages or another HTML-capable hosting service
- No backend runtime
- No account-based service configuration

---

## Frequently Asked Questions

**Is a server required to run Aporizma?**  
No. Aporizma is a static site intended to execute in the browser.

**Can I deploy it with GitHub Pages?**  
Yes. GitHub Pages is one of the hosting environments the project is designed to support.

**Does Aporizma send user data anywhere?**  
No uploads are included in the documented feature set.

**Where can I modify the available settings?**  
Settings are maintained in the static project files. This includes interface text and language-related content.

**How can I troubleshoot a page that does not display properly?**  
Confirm that the deployment is serving the project as a static site and that the browser can retrieve the HTML, CSS, and JavaScript assets.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
