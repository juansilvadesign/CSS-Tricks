<div align="center">

# CSS Tricks ✨

Small, focused CSS micro-experiments – each folder is a self‑contained demo exploring a single visual idea or technique.

![Project cover showing gradient animation and 1px line demo](https://i.ibb.co/t7fVQSF/iphone-X-06.webp)

![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) ![Github Pages](https://img.shields.io/badge/github%20pages-121013?style=for-the-badge&logo=github&logoColor=white)

</div>

## 🚀 Live Demos

| Demo | Link | What it Shows |
|------|------|---------------|
| 1Pixel | [Click here](https://juansilvadesign.github.io/CSS-Tricks/CSS-1Pixel/) | Sub‑pixel crisp lines / hairline technique |
| Gradient Color Animation | [Click here](https://juansilvadesign.github.io/CSS-Tricks/CSS-Gradient-Color-Animation/) | Animated multi‑stop gradient background |

> Each demo is intentionally minimal so you can focus on one concept at a time.

## 💡 Overview

This repository is a personal learning lab: short, digestible CSS “tricks” collected while practicing layout, animation, rendering performance, and visual polish. Rather than large examples, the goal is: one idea, clean markup, clear styles.

## ✨ What You Can Learn

* Hairline / 1px techniques across devices
* Gradient animation timing & layering
* Modern CSS features (custom properties, layering, filters, etc.)
* File / folder organization for tiny experiments
* Progressive enhancement mindset

## 🗂 Project Structure

```
CSS-Tricks/
	CSS-1Pixel/                  # Demo: ultra-thin line technique
		index.html
		style.css
		README.md (demo-specific notes)
	CSS-Gradient-Color-Animation/ # Demo: animated gradient background
		index.html
		style.css
		README.md (demo-specific notes)
	LICENSE
	README.md (this file)
```

Each trick lives in its own directory so you can open it standalone or deploy selectively.

## 🛠 Tech Stack

* Pure HTML & CSS (no frameworks)
* GitHub Pages for hosting
* VS Code for editing

## 🧪 Running Locally

You only need a browser. Clone and open any `index.html` file directly, or serve the root for nicer relative paths:

Windows PowerShell example:

```powershell
git clone https://github.com/juansilvadesign/CSS-Tricks.git
cd CSS-Tricks
# Option A: Open a file directly
start CSS-Gradient-Color-Animation/index.html

# Option B: Spin up a quick local static server (Python required)
python -m http.server 8080
# Then visit: http://localhost:8080/CSS-Gradient-Color-Animation/
```

Alternatively use the VS Code Live Server extension.

## ➕ Adding a New Trick

1. Create a new folder: `CSS-New-Trick-Name/`
2. Add `index.html` + `style.css`
3. Keep markup semantic & minimal (avoid unnecessary wrappers)
4. Document any key idea in a `README.md` inside that folder
5. Test on both light & dark backgrounds (if relevant)
6. Add the link to the main table above

Naming Suggestion: Use descriptive, Title-Cased, hyphen separated folder names for clarity.

## 🧭 Philosophy

Keep it tiny. One concept. Readable CSS. Resist over‑engineering. Favor clarity over cleverness.

## 🗺 Roadmap / Ideas Queue

- Glassmorphism card
- Fluid typography clamp() demo
- Layered parallax scroll effect (CSS only)
- Accent-color form controls
- CSS @property custom animatable value demo
- Container queries example

## 🙌 Inspiration & Credits

These experiments are inspired by the excellent teaching of Kevin Powell’s YouTube channel. His clear explanations encouraged me to translate lessons into focused micro-examples (this repo). If you’re learning CSS, his channel is a must‑watch.

## 🤝 Contributing

Suggestions or small improvements are welcome:
1. Fork
2. Create a branch (`feat/add-new-demo`)
3. Commit with clear messages
4. Open a Pull Request

Please keep examples minimal and accessible (reduced motion friendly, semantic HTML, good contrast).

## 📄 License

This project is released under the MIT License – see `LICENSE` for full text. You can reuse or modify these examples freely (attribution appreciated but not required).

## ✍️ Author

Made with 💜 by **Juan Pablo**.

## 📜 Quote

> “Small, consistent practice compounds into deep skill.”

---

If this helped you, a ⭐ on the repository motivates more tiny CSS experiments. Enjoy exploring!
