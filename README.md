# MAT4167-Group-project
\documentclass[a4paper,12pt]{article}
% This fixes a bug so its staying i guess
\setlength{\headheight}{14.49998pt}
\addtolength{\topmargin}{-2.49998pt}
% Package to make citations superscrit with brackets
\usepackage[super,square]{natbib}
% Package to change margin size
\usepackage{anysize}
\marginsize{2cm}{2cm}{1cm}{2cm}
% Package to make headers
\usepackage{fancyhdr}
\renewcommand{\headrulewidth}{0pt}
% Package for highligths
\usepackage{soul}
\usepackage[dvipsnames]{xcolor}
\usepackage{hyperref}
\hypersetup{
    colorlinks=true,
    linkcolor=black,
    citecolor=CadetBlue,
    filecolor=CadetBlue,      
    urlcolor=CadetBlue,
}
\usepackage{lipsum}
\usepackage{parskip}
\setlength\columnsep{18pt}

\usepackage{amsfonts,amsmath,amssymb}

% Math Shortcuts
\newcommand{\N}{\mathbb{N}}
\newcommand{\Z}{\mathbb{Z}}
\newcommand{\Q}{\mathbb{Q}}
\newcommand{\R}{\mathbb{R}}
\newcommand{\C}{\mathbb{C}}
\newcommand{\F}{\mathbb{F}}
\newcommand{\bH}{\mathbb{H}}
\newcommand{\e}{\varepsilon}
\newcommand{\bb}[1]{\mathbb{#1}}
\newcommand{\be}{\mathbf{e}}
\newcommand{\x}{\mathbf{x}}
\newcommand{\y}{\mathbf{y}}
\newcommand{\z}{\mathbf{z}}
\newcommand{\bu}{\mathbf{u}}
\newcommand{\bv}{\mathbf{v}}
\newcommand{\w}{\mathbf{w}}
\newcommand{\p}{\mathbf{p}}
\newcommand{\q}{\mathbf{q}}
\newcommand{\zero}{\mathbf{0}}
\newcommand{\one}{\mathbf{1}}
\newcommand{\op}{\mathrm{op}}
\newcommand{\g}{\mathfrak{g}}
\newcommand{\gl}{\mathfrak{gl}}

\DeclareMathOperator{\End}{End}
\DeclareMathOperator{\Aut}{Aut}
\DeclareMathOperator{\Span}{Span}
\DeclareMathOperator{\im}{im}
\DeclareMathOperator{\diag}{diag}
\DeclareMathOperator{\tr}{tr}
\DeclareMathOperator{\ad}{ad}
\DeclareMathOperator{\Ad}{Ad}
\DeclareMathOperator{\SL}{SL}
\DeclareMathOperator{\PSL}{PSL}

 
\begin{document}
% Makes header
\pagestyle{fancy}
\thispagestyle{empty}
\fancyhead[R]{\textit{MAT3743 - Hiver 2025}}
\fancyhead[L]{}
% Makes footnotes with an asterisk
\renewcommand*{\thefootnote}{\fnsymbol{footnote}}
\begin{center}
\Large{\textbf{Monstrous moonshine}}
\vspace{0.4cm}
\normalsize
\\ Amélie Boucher, Kiera Hutton, Justin Thériault \\
\vspace{0.1cm}
\textit{dans le cadre du cours MAT3743 - Algèbre appliquée}
\medskip
\normalsize
\end{center}
{\color{gray}\hrule}
\medskip
\input{./sections/1_intro.tex}
\medskip
\input{./sections/2_section.tex}
\medskip
\input{./sections/3_section.tex}
\medskip
\input{./sections/4_section.tex}
\medskip
\input{./sections/conclusion.tex}
\bibliographystyle{plain}
\bibliography{references}
\end{document}