---
usefancy: false
theme: OPERAHPC
fonttheme: default
fontsize: 12pt
aspectratio: 169
csl: chicago-author-date.csl
author: Tommaso Barani, Bruno Michel
shortauthor: T. Barani, B. Michel
date: 19-23/01/2026
shortdate: 22/01/2026
institute: "CEA DEs, IRESNE, DEC, SESC, Building 151, Cadarache Center, Saint Paul Les Durance, France."
title: " "
header-includes:
 - \title[Short title]{The \texttt{title} of the talk}
# - \author[T. Barani, B. Michel]{Tommaso Barani, Bruno Michel}
# - \date[19-23/01/2026]{19-23/01/2026}
 - \graphicspath{{./logos/}}
 - \def\BottomLogo{LOGO_CEA_ORIGINAL.png}
 - \def\eulogo{logo_eu.png}
 - \def\secondlogo{logo_operahpc.png}
 - \def\operalogo{logo_operahpc.png}
 - \RequirePackage{fontspec}
 - \setmainfont{Ebrima}
 - \setsansfont{Ebrima}
 - \usepackage{fvextra}
 - \DefineVerbatimEnvironment{Highlighting}{Verbatim}{breaklines,breakanywhere,fontsize=\footnotesize,commandchars=\\\{\}}
titlepage: false
include-before: |
 \begin{frame}[operatitle]
  \titlepage
 \end{frame}
include-after: |
 \begin{frame}[closing]
 \end{frame}
---

# Introduction

## A slide title

Study of fuel fine fragmentation risk assessment

| Condition | Reactor | Fuel element | Code | Type of code   | Partner |
|-----------|---------|--------------|------|----------------|---------|
| LOCA      | VVER    | Something    | sROM | Improved model | CEA     |
---

## Another slide title

1. **Learning data base from MMM**

2. **Input data**

- Selection of the HBS zone to consider
  - Microstructure at the beginning of the transient
  - Bubbles pressure loading during the transient
- External loading (macroscopic \(\sigma\) or \(\varepsilon\))

## Some code

Some python
```python
def hello_world():
    print("Hello from Beamer!")
    return True
```
Some C++
```cpp
template <bool parallel>
static void calculateAverageHydrostaticStress(
    std::ostream& os,
    const mfem_mgis::NonLinearEvolutionProblemImplementation<parallel>& prob,
    const mfem_mgis::ImmutablePartialQuadratureFunctionView& f) 
```

## An image

![OperaHPC LOGO](logos/logo_operahpc.png){width=50%}