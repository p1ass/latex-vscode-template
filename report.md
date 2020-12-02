---
title: ''
author: 岸 直輝
eauthor: Jiro Denki
professor: 電気 太郎 教授
# course: 京都大学大学院情報学研究科
# department: 知能情報学専攻
date: 令和2年4月14日
header-includes:
    - \title{\LaTeX を用いた修論$\cdot$卒論の執筆}
    - \etitle{Usage of The \LaTeX{} Style File for KUEE}
    - \eauthor{Jiro Denki}
    - \professor{電気 太郎 教授}
    # - \course{京都大学大学院情報学研究科}
    # - \department{知能情報学専攻}
include-before:
    - \begin{eabstract}Abstract\end{eabstract}
    - \def\lstlistingname{ソースコード}
documentclass: kuee
classoption: sotsuron
bibliography:
    - sample.bib
---

#  hoge

\cite{GuideBook}

adfa [@GuideBook, pp]

あいうえお[^1]

[^1]: あいうえおあ

## fuga

あいうえおかきくけこさいっすせそhogehoge

|hoge|fuga|
|-|-|
|a|i|

![iamge](image/syokuji_computer.png){width=50mm}

# ほげ

\bibliographystyle{kueethesis}
\bibliography{sample}
