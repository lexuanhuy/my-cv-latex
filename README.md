# 🧑‍💻 Le Xuan Huy — CV (LaTeX)

This repository contains my professional CV written in **LaTeX**.  
It is a clean, single-column layout inspired by minimalist modern templates,  
designed for developers and technical professionals.

---

## 📘 Features

- ✨ Simple one-column LaTeX layout (no heavy templates)
- 🔹 FontAwesome icons for a professional look
- 🔹 Section dividers and consistent spacing
- 🔹 Works on both **MiKTeX** and **TeX Live**
- 💼 Ideal for software engineers, developers, and tech resumes

---

## 🧩 Folder Structure

```
cv-latex/
├── cv.tex # Main LaTeX source
├── cv.pdf # Compiled PDF output
├── .gitignore # Ignore build files
└── README.md # This file
```

---

## ⚙️ How to Build the CV

### 🧰 **Option 1 — Build using VS Code**

#### Requirements:

1. Install [VS Code](https://code.visualstudio.com/)
2. Install the extension **LaTeX Workshop** by James Yu
3. Install a LaTeX distribution:
   - 🪟 Windows → [MiKTeX](https://miktex.org/download)
   - 🍎 macOS → [MacTeX](https://tug.org/mactex/)
   - 🐧 Linux → [TeX Live](https://tug.org/texlive/)

#### Steps:

1. Open this folder in VS Code
2. Open `cv.tex`
3. Press **Ctrl + Alt + B** (or click “Build LaTeX project” from the VS Code command palette)
4. The generated file `cv.pdf` will appear in the same folder

> ⚡ If LaTeX Workshop asks to install missing packages, just click **Install** — it’s safe.

---

### 🧮 **Option 2 — Build from terminal**

```bash
pdflatex cv.tex
#or
latexmk -pdf cv.tex
```

---

💬 Created with ❤️ by Le Xuan Huy — built in LaTeX using VS Code.

---

[[Download PDF]](https://github.com/lexuanhuy/my-cv-latex/blob/main/cv.pdf)
