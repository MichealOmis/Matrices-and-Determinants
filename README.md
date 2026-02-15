# WAEC General Mathematics Lecture Notes: Matrices, Game Theory & Calculus

## Project Overview

This repository contains the LaTeX source code for a comprehensive set of lecture notes designed for the **WAEC General Mathematics** syllabus. The document covers advanced mathematical topics including Matrix Algebra, Game Theory strategies, Implicit Differentiation, and Integral Calculus. It is formatted for a specific large-paper layout (Ledger size, 11in x 17in) suitable for broadsheets, study posters, or handouts.

## Features

* **Specialized Formatting:** Optimized for Ledger paper (11x17 in) with a two-column layout for maximum content density.
* **Visual Aids:** Uses `TikZ` and custom tables to visualize matrices, payoff tables, and game theory strategies.
* **Custom Environments:** specialized boxes for `Key Point`, `Important Formula`, `Common Mistake`, and `Worked Example` to aid student retention.
* **Mathematical Typesetting:** Clear presentation of complex notations such as matrix inverses (), determinants (), definite integrals (), and implicit derivatives ().
* **Educational Content:** Includes definitions, step-by-step solved examples, and practice exercises with selected solutions.

## Prerequisites

To compile this project, you need a standard TeX distribution (like TeX Live, MiKTeX, or MacTeX) with the following packages installed:

* `geometry`
* `amsmath`, `amssymb`, `amsthm`
* `multicol`
* `enumitem`
* `fancyhdr`
* `tcolorbox`
* `xcolor`
* `tikz` (libraries: `shapes`, `arrows`, `positioning`, `calc`, `matrix`)
* `array`, `booktabs`

## Compilation

You can compile the `matrices_game_calculus.tex` file using `pdflatex`.

**Using Terminal/Command Line:**

```bash
pdflatex matrices_game_calculus.tex

```

*Note: Run the command twice to ensure the internal cross-references and table formatting are rendered correctly.*

## File Structure

* `matrices_game_calculus.tex`: The main source file containing all mathematical logic, text, and TikZ code.
* `matrices_game_calculus.pdf`: (Optional) The compiled output file.

## Content Sections

1. **Matrices and Determinants:**
* Matrix operations (Addition, Scalar Multiplication, Matrix Multiplication).
* Determinants of  and  matrices.
* Matrix Inverses and solving systems of linear equations ().


2. **Game Theory:**
* Two-player zero-sum games and Payoff Matrices.
* Identification of Saddle Points and Pure Strategies.
* The principle of Dominance to simplify games.


3. **Implicit Differentiation:**
* Techniques for differentiating equations where  is not explicitly defined (e.g., ).
* Chain rule applications for terms involving .


4. **Integral Calculus:**
* Indefinite integrals using the Power Rule and basic integration formulas.
* Definite integrals and the Fundamental Theorem of Calculus.
* Calculation of Area under a Curve.



## License

This project is intended for educational use. Please check the repository license file for specific usage rights.
