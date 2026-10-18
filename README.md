# 📐 An Introduction to Fractal Geometry: the Mandelbrot Set

In 1990 I wrote my *Facharbeit* (a research paper in the advanced maths course, *Leistungskurs*)
on fractal geometry, at the Integrierte Gesamtschule Ernst Bloch in Ludwigshafen am Rhein. The
pictures came from a Pascal program I wrote for an Atari ST, some of them after hours of computing.

In 2026 I took the binder off the shelf and digitised it, with AI as a co-worker: photographed
every page, transcribed the original word for word, checked the sources, and produced a new,
corrected edition with redrawn and recomputed figures.

---

## 📄 Read it

📘 [**English edition (PDF)**](facharbeit-mandelbrot-en.pdf) - *New edition 2026*, translated from the German

📗 [**Deutsche Fassung (PDF)**](facharbeit-mandelbrot.pdf) - *Neufassung 2026*

Both are also attached to the latest [release](../../releases/latest).

---

## 🧮 What's inside

🔢 **Complex numbers** - arithmetic, the Gaussian plane, polar form, why ℂ can't be ordered

📈 **Sequences and limits in ℂ** - convergence, limit theorems, a worked example

🍎 **The Mandelbrot set** - the iteration *z ↦ z² + c*, the escape-time algorithm, Julia sets

❄️ **Fractal dimension** - the Koch snowflake and why its dimension is log 4 / log 3 ≈ 1.26

🖼️ **Plates** - zooms into the boundary, a 3-D escape-time landscape, IFS fractals

---

## 🕰️ 1990 → 2026

| | 1990 | 2026 |
|---|---|---|
| Computer | Atari ST, Pascal with GEM | LaTeX, TikZ, Python |
| Pictures | dot-matrix printouts, hours per image | recomputed at the original coordinates |
| Text | typewritten, with my teacher's red pen | corrected, with each correction explained |

The 2026 edition is a rewrite, not a transcription: it keeps the structure and line of thought of
the original, fixes what was mathematically wrong, and marks the most important corrections. The original
pages and a word-for-word transcription are kept in a private archive; the original Pascal
source is printed in the appendix.

---

## 🛠️ How it was made

Built with LaTeX (KOMA-Script, TikZ, biblatex) and a few Python scripts for the fractal images.
ChatGPT produced the first draft of the 2026 edition and the recomputed images; Claude helped
translate it into English, transcribe the scans, check the 1990 sources against library catalogues, redraw figures in TikZ
and review the new edition against the original. The judgement calls stayed mine.
