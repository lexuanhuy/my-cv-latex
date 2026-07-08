# Le Xuan Huy — CV (LaTeX)

This repository contains my professional CV written in **LaTeX**.  

---

## Features

- Simple one-column LaTeX layout (no heavy templates)
- FontAwesome icons for a professional look
- Section dividers and consistent spacing
- Works on both **MiKTeX** and **TeX Live**
- Ideal for software engineers, developers, and tech resumes

---

## Folder Structure

```
src/
├── [file name].tex # Main LaTeX source
├── [file name].pdf # Compiled PDF output
├── .gitignore # Ignore build files
└── README.md # This file
```

---

## How to Build

### **Option 1 — Build using VS Code**

#### Requirements:

1. Install [VS Code](https://code.visualstudio.com/)
2. Install the extension **LaTeX Workshop** by James Yu
3. Install a LaTeX distribution:
   - Windows → [MiKTeX](https://miktex.org/download)
   - macOS → [MacTeX](https://tug.org/mactex/)
   - Linux → [TeX Live](https://tug.org/texlive/)

#### Steps:

1. Open this folder in VS Code
2. Open `[name].tex`
3. Press **Ctrl + Alt + B** (or click “Build LaTeX project” from the VS Code command palette)
4. The generated file `[name].pdf` will appear in the same folder

> If LaTeX Workshop asks to install missing packages, just click **Install** — it’s safe.

---

### **Option 2 — Build from terminal**

```bash
pdflatex [name].tex
# or
latexmk -pdf [name].tex
```

 <!-- pdflatex LeXuanHuy_Frontend_CV.tex -jobname=LeXuanHuy_SoftwareEngineer_CV -->

---

Created by Le Xuan Huy — built in LaTeX using VS Code.

---

[[Download PDF]](https://github.com/lexuanhuy/my-cv-latex/blob/main/LeXuanHuy_Frontend_CV.pdf)
