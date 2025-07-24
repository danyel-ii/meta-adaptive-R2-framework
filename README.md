# Meta-Adaptive Resilience in Recursive Self-Improvement
_A Simulation Framework for R² Learning in Noisy Environments_

(https://app.ens.domains/danyel-ii.eth)

## Overview

This repository contains the files required to compile the paper titled:

**"Meta-Adaptive Resilience in Recursive Self-Improvement: A Simulation Framework for R² Learning in Noisy Environments"**

It is formatted for LaTeX compilation via **Overleaf** or **arXiv**, including citations via BibTeX.

---

## File Structure


meta-adaptive-R2/
├── main.tex                 # Main LaTeX manuscript (converted from Markdown)
├── references.bib           # BibTeX bibliography file
├── figures/                 # Directory for conceptual diagrams and simulation plots
│   ├── R1_loop_diagram.pdf  # Placeholder for R¹ conceptual diagram
│   ├── R2_loop_diagram.pdf  # Placeholder for R² conceptual diagram
│   └── learning_trace_plot.pdf # Placeholder for simulation result figure
├── README.md                # This guide

---

## Instructions

### 📦 1. Prepare the Project

-   Download or clone this repository to your local machine.
-   If starting from scratch on Overleaf, create a new blank project and upload the files directly.

### ✍️ 2. `main.tex` (LaTeX manuscript)

-   This file contains the full text of the paper using LaTeX formatting.
-   The `\cite{}` commands are already inserted and will link to entries in `references.bib`.

### 📚 3. `references.bib`

-   Contains all citation metadata in BibTeX format.
-   Ensure this file is included in your Overleaf project (or in the same directory for local LaTeX compilation) and that `main.tex` contains the lines:
    ```latex
    \bibliographystyle{plainnat} % Or another style like unsrtnat, abbrvnat, etc.
    \bibliography{references}
    ```
    (These lines are already in the `main.tex` content I will provide.)

### 📊 4. Figures

You may export visual diagrams (e.g., `R1_loop_diagram.pdf`) using external tools such as draw.io, Inkscape, or Python's Matplotlib, and place them in the `figures/` folder.

In the LaTeX file (`main.tex`), include figures with commands like:

```latex
\begin{figure}[h]
  \centering
  \includegraphics[width=\linewidth]{figures/R1_loop_diagram.pdf}
  \caption{Conceptual overview of the Triadic Loop (R¹)}
  \label{fig:R1_diagram} % Add a label for cross-referencing
\end{figure}

(Placeholders for these are already in main.tex.)
Submission Targets
✅ Overleaf: Upload all files into a single project folder.
✅ arXiv: Zip the entire directory (meta-adaptive-R2-local/ including figures/ subfolder) and submit through arXiv’s upload interface.
Keywords
recursive self-improvement, meta-learning, cybernetics, AI alignment, AutoML, AI robustness, adaptive systems
Author Contributions
This paper was co-developed in a recursive simulation dialogue with a large language model. The conceptual design, implementation architecture, experiment structure, and manuscript drafting were all part of a real-time collaborative process intended to operationalize AI-driven recursive self-improvement.

---
