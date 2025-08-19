---
marp: true
theme: default
paginate: true
class: lead
# Custom theme CSS injected for Marp (keeps presentation maintainable)
style: |
  section {
    font-family: "Inter", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
  }
  /* Header styling */
  h1 { font-size: 48px; letter-spacing: -1px; }
  /* Footer for page number + email */
  footer.marp-footer {
    position: absolute;
    bottom: 12px;
    left: 24px;
    font-size: 12px;
    opacity: 0.85;
  }
  /* Custom accent color */
  :root { --accent: #0b63ff; }
  h2 { color: var(--accent); }
  /* Small callout box style */
  .callout {
    border-left: 4px solid var(--accent);
    padding: 12px;
    background: rgba(11,99,255,0.05);
    border-radius: 6px;
  }
---

<style>
  blockquote {
    font-style: italic;
  }
  section {
    background-image: url('qr-code.png');
    background-repeat: no-repeat;
    background-position: top 20px right 20px;
    background-size: 80px auto;
  }
</style>

<!--
  Product Documentation — Marp
  Author: Technical Writer
  Contact: 24f2007963@ds.study.iitm.ac.in
-->

# Product: AtlasDB
Comprehensive documentation — quick overview

<div class="callout">
**Contact**: <code>24f2007963@ds.study.iitm.ac.in</code>
</div>

<footer class="marp-footer">© AtlasDB • <span>{{page}} / {{total}}</span></footer>

---

<!-- slide: class="center" -->

## Why Marp?
- Maintainable Markdown in git
- Easy conversion: HTML, PDF, PPTX
- Lightweight, versionable docs

<footer class="marp-footer">Contact: <code>24f2007963@ds.study.iitm.ac.in</code> • <span>{{page}} / {{total}}</span></footer>

---

<!-- _backgroundImage: url('https://picsum.photos/200/300') -->
<!-- _color: white -->
# Product Demo
This slide has a background image!
<!-- You can also use your own image hosted in the repo (relative path). -->
# Visual Overview
This slide uses a **background image** to show architecture.

<footer class="marp-footer">24f2007963@ds.study.iitm.ac.in • <span>{{page}} / {{total}}</span></footer>

---

## Installation (code sample)

```bash
# Install CLI
npm i -g @atlasdb/cli
# Initialize project
atlas init my-project
