# SZTU Official Cover Letter Template 🎓

> A minimalist, highly customized LaTeX cover letter template designed for Shenzhen Technology University (SZTU) researchers and students.

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Compiler: XeLaTeX](https://img.shields.io/badge/Compiler-XeLaTeX-success.svg)

This repository provides an elegant and official LaTeX letterhead template for academic manuscript submissions, official correspondence, and formal applications. 

## 🌟 Visual Preview

*(Note to author: Make sure to upload your compiled PDF screenshot to `preview/preview_full.png` so it displays here!)*

<p align="center">
  <img src="preview/preview_full.jpg" alt="Cover Letter Preview" width="700">
</p>

## ✨ Key Features

- **Official Letterhead**: Accurately reproduces the SZTU branding with a vector-friendly layout and dynamic gradient split-lines.
- **Modern Typography**: Utilizes a clean block-paragraph style (`\parskip`) for excellent readability without manual spacing.
- **Space-Saving Signature Block**: Features a dual-column layout at the bottom to horizontally align your digital signature and text details, ensuring your letter fits perfectly on a single page.
- **Easy Customization**: Built with `minipage` and `fancyhdr`, making it extremely easy to tweak widths, heights, and margins.

## 📂 Repository Structure

```text
SZTU-CoverLetter-Template/
├── assets/                    # Static image resources
│   ├── SZTU.png               # Official SZTU Logo (Transparent PNG recommended)
│   └── signature.png          # Your digital signature image, not including in the template now
├── preview/                   
│   └── preview_full.jpg       # High-res screenshot for this README
├── .gitignore                 # Ignores LaTeX build files (*.log, *.aux, etc.)
├── LICENSE                    # MIT License
├── README.md                  # Project documentation
└── SZTU_CoverLetter.tex       # The main LaTeX source code