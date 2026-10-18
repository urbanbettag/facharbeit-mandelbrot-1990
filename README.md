# 📐 An Introduction to Fractal Geometry, Illustrated by the Mandelbrot Set

In 1990 I wrote my *Facharbeit* (a research paper in the advanced maths course, *Leistungskurs*)
on fractal geometry, at the Integrierte Gesamtschule Ernst Bloch in Ludwigshafen am Rhein. The
pictures came from a Pascal program I wrote for an Atari ST, some of them after hours of computing.

In 2026 I took the binder off the shelf and digitised it, with AI as a co-worker: photographed
every page, transcribed the original word for word, checked the sources, and produced a new,
corrected edition with redrawn and recomputed figures.

**Version 2.0** adds five new chapters that carry the 1990 paper forward to today's research.
They are written to bring mathematics alive for secondary-school students: each chapter builds on
the ones before, starts with *What you already know* and ends with *Try it yourself* tasks you can
do by hand or with a few lines of Python.

---

## 📄 Read it

**The 1990 paper, reworked** (chapters 1–4 and the appendix)

📘 [**English (PDF)**](facharbeit-1990-en.pdf) · 📗 [**Deutsch (PDF)**](facharbeit-1990-de.pdf)

**The 2026 edition with five new chapters** (Part I plus Part II)

📘 [**English (PDF)**](facharbeit-2026-en.pdf) · 📗 [**Deutsch (PDF)**](facharbeit-2026-de.pdf)

All four are also attached to the latest [release](../../releases/latest).

---

## 🧮 What's inside

**Part I: the 1990 paper**

🔢 **Complex numbers** - arithmetic, the Gaussian plane, polar form, why ℂ can't be ordered

📈 **Sequences and limits in ℂ** - convergence, limit theorems, a worked example

🍎 **The Mandelbrot set** - the iteration *z ↦ z² + c*, the escape-time algorithm, Julia sets

❄️ **Fractal dimension** - the Koch snowflake and why its dimension is log 4 / log 3 ≈ 1.26

**Part II: further topics (2026)**

🐇 **Julia sets and connectedness** - fix *c*, vary the starting point; why a Julia set is *not* a
subset of the Mandelbrot set, and how the Mandelbrot set catalogues all Julia sets

✨ **Mandelbrot, Julia and Cantor** - the Cantor set, and why every quadratic Julia set is either in
one piece or scattered dust

📏 **Hausdorff dimension** - how to measure the "size" of sets with length zero, and why the boundary
of the Mandelbrot set has dimension 2

🌀 **Beyond z² + c** - higher powers, Newton's method, and the Julia sets of eᶻ, sin, cos, tan and ln

❓ **Open questions** - what is still unsolved in 2026, from the MLC conjecture to the Kakeya problem

🖼️ **Appendix** - zooms into the boundary, a 3-D escape-time landscape, IFS fractals, the original
Pascal program

---

## 🕰️ 1990 → 2026

| | 1990 | 2026 |
|---|---|---|
| Computer | Atari ST, Pascal with GEM | LaTeX, TikZ, Python |
| Pictures | dot-matrix printouts, hours per image | recomputed at the original coordinates |
| Text | typewritten, with my teacher's red pen | corrected, the most important corrections explained |

The 2026 edition is a rewrite, not a transcription: it keeps the structure and line of thought of
the original, fixes what was mathematically wrong, and marks the most important corrections. The original
pages and a word-for-word transcription are kept in a private archive; the original Pascal
source is printed in the appendix.

---

## 🛠️ How it was made

Built with LaTeX (KOMA-Script, TikZ, biblatex) and a few Python scripts for the fractal images.
ChatGPT produced the first draft of the 2026 edition and the recomputed images; Claude helped
translate it into English, transcribe the scans, check the 1990 sources against library catalogues, redraw figures in TikZ
and review the new edition against the original. For version 2.0, Claude researched the new
topics, drafted chapters 5 to 9 and reviewed them; every source was checked against the publishers'
records. The judgement calls stayed mine.
