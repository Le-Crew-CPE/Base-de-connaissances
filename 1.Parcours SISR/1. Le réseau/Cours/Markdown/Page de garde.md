---
lang: fr-FR
geometry: margin=2.5cm
pdf-engine: xelatex
pandoc-include-attributes: true
header-includes:
  - \usepackage{titling}
  - \usepackage{graphicx}
  - \usepackage{fontspec}
  - \usepackage{xcolor}
  - \usepackage{float}
  - \usepackage{caption}
  - \color{black}
---

\newcommand{\smalllogo}[2][12mm]{\includegraphics[height=#1,keepaspectratio]{#2}}

\begin{titlepage}
    \centering
    \vspace*{0.2cm}

    \includegraphics[width=0.5\textwidth]{PdG.png}
    \vspace*{0.2cm}

    {\Huge\textbf{Titre du document}\par}
    \vspace{0.5cm}
    {\Large Documentation\par}

    \includegraphics[width=0.5\textwidth]{PdG2.png}
    \vspace*{0.2cm}

    \vspace{1.5cm}

    \smalllogo[20mm]{logo_chartreux.png} \hspace{6mm} \smalllogo[20mm]{cpe_logo.jpg}

    \vfill

    {\large\textbf{Alexandre FAUBLADIER--ANETTE}\par}
    \vspace{0.2cm}
    {\large Institution des Chartreux\par}
    \vspace{0.2cm}
    {\large Date du document\par}
\end{titlepage}
