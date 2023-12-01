# Tugas Mata Kuliah Aplikasi Komputer
## Menggabungkan Beberapa File Notebook EMT Menjadi Satu Dokumen Sederhana dengan Bantuan Software Overleaf

Umi Nurkhasanah (22305141032) Matematika E 2022
##
1. [file notebook (.en).zip](https://github.com/uminrr/Aplikasi-Komputerr/files/13523724/file.notebook.en.zip) merupakan file notebook EMT.
2. [file notebook (.en).zip](https://github.com/uminrr/Aplikasi-Komputerr/files/13523803/file.notebook.en.zip) ketika di-extras
 akan menghasilkan [File Latex  (.Tex).zip](https://github.com/uminrr/Aplikasi-Komputerr/files/13523778/File.Latex.Tex.zip) beserta [images.zip](https://github.com/uminrr/Aplikasi-Komputerr/files/13524230/images.zip)
 dan [file markdown (.md).zip](https://github.com/uminrr/Aplikasi-Komputerr/files/13523815/file.markdown.md.zip)
3. Dengan bantuan Overleaf, [File Latex  (.Tex).zip](https://github.com/uminrr/Aplikasi-Komputerr/files/13523788/File.Latex.Tex.zip) dapat diubah menjadi [Dokumen Gabungan.pdf](https://github.com/uminrr/Aplikasi-Komputerr/files/13523793/Dokumen.Gabungan.pdf)

\usepackage[utf8]{inputenc}

\usepackage{color}
\usepackage[pdftex]{graphicx}
\usepackage[space]{grffile}
\usepackage{enumerate}
\usepackage{array}
\usepackage{amsmath}
\usepackage{amsfonts}
\usepackage{alltt}
\usepackage{framed}

\usepackage[paperwidth=24cm,paperheight=18cm]{geometry}

\pagestyle{empty}

\definecolor{red}{rgb}{0.4,0.0,0.0}
\definecolor{green}{rgb}{0.0,0.3,0.0}
\definecolor{black}{rgb}{0.0,0.0,0.0}
\definecolor{blue}{rgb}{0.0,0.0,0.4}
\definecolor{shadecolor}{rgb}{0.94,0.94,0.94}

\setlength{\oddsidemargin}{3cm} 
\setlength{\evensidemargin}{3cm}
\setlength{\topmargin}{0cm}
\setlength{\headsep}{0cm}
\setlength{\voffset}{-1cm}
\setlength{\textwidth}{16cm}
\setlength{\textheight}{15cm}

\newenvironment{eulernotebook}{}{}

\newenvironment{eulercomment}
{\color{green}\vspace{10pt plus 30pt}\parskip=5pt plus 3pt%
\goodbreak}%
{\vspace{5pt}}

\newenvironment{eulerttcomment}
{\color{green}\parskip=0pt%
\goodbreak\begin{alltt}}%
{\end{alltt}\vspace{5pt}}

\newenvironment{eulerprompt}
{\color{red}\vspace{5pt}%
\begin{shaded}\parskip=0pt\parsep=0pt\topsep=0pt%
\begin{alltt}\ignorespaces}
{\end{alltt}\end{shaded}\vspace{5pt}}

\newenvironment{eulerudf}
{\color{blue}\parskip=0pt\parsep=0pt\topsep=0pt%
\begin{alltt}\ignorespaces}
{\end{alltt}\vspace{5pt}}

\newenvironment{euleroutput}
{\color{black}\vspace{5pt}%
\parskip=0pt\parsep=0pt\topsep=0pt%
\begin{alltt}\ignorespaces}
{\end{alltt}\vspace{5pt}}

\newcommand\eulerheading[1]{%
\begin{samepage}%
\color{green}\pagebreak{\Large\bf\hfill#1}\\[-5pt]%
\rule{\linewidth}{1pt}\nopagebreak\vspace{16pt}%
\end{samepage}\nopagebreak}

\newcommand\eulersubheading[1]{%
\begin{samepage}%
\color{green}\vspace{12pt plus 20pt}\goodbreak{\large\bf\hfill#1}\\[-5pt]%
\rule{\linewidth}{1pt}\vspace{16pt}
\end{samepage}\nopagebreak}

\newlength{\eulerline}
\setlength{\eulerline}{11pt}
\newcommand\eulerimg[2]{%
\begin{center}\includegraphics[height=#1\eulerline]{#2}\end{center}}

\newenvironment{eulerformula}
{\color{green}\belowdisplayskip=0pt\belowdisplayshortskip=0pt%
\abovedisplayskip=0pt\abovedisplayshortskip=0pt}{}

\setlength\parindent{0pt}
\setlength\parskip{0pt}

