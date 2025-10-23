# Resume Generator (LaTeX)

This repository contains **`resume_generator.tex`**, a LaTeX source for generating a polished PDF resume.

## What you need
- A LaTeX distribution:
  - **Windows:** [MiKTeX] or [TeX Live]
  - **macOS:** MacTeX
  - **Linux:** TeX Live
- (Optional) `latexmk` for one-command builds

> If you use custom fonts or Unicode-heavy content, prefer **XeLaTeX** or **LuaLaTeX**.

## Build (quick start)

### Option A — latexmk (recommended)
```bash
latexmk -pdf resume_generator.tex
# or:
latexmk -xelatex resume_generator.tex
