# Client Template Chooser

[![License: MIT](https://img.shields.io/badge/License-MIT-orange.svg)](LICENSE)
[![pages-build-deployment](https://img.shields.io/github/deployments/Nick73/website-tester/github-pages?label=GitHub%20Pages&logo=github)](https://Nick73.github.io/wesbite-tester/)

A lightweight way to showcase multiple website templates so clients can preview and pick their favorite design.

## 🚀 Features

- Instant preview of different website layouts.
- Simple folder-based structure — add or remove templates easily.
- Works with GitHub Pages for quick sharing.

## 🛠️ How to Use

1. **Add Templates**Each folder represents a separate website template.

   - Place an `index.html` inside each folder (`sample1`, `sample2`, etc.).
   - You can add as many samples as you want.
2. **Update the Picker**
   Edit the main `index.html` in the repo root to include links to your new template folders.
3. **Publish**

   - Push your changes to GitHub.
   - Enable GitHub Pages on the repository.
   - Share the Pages URL — the template picker will be the landing page.

> 💡 The picker loads your chosen template directly in the preview window, making it easy for clients to explore your designs.

---

### Example Structure

```
repo/ 
│── index.html  ← Template picker 
|
├── sample1/ 
│   └── index.html 
├── sample2/ 
│   └── index.html 
└── sample3/
    └── index.html
```

---
