# README

simple pdf:

(pandoc iching-essay.md -f markdown --pdf-engine=xelatex -o ichingTEST.pdf) 


but better to use:
AFTER making BACKUP of old file!!

pandoc iching-essay.md -f markdown+footnotes -t latex --wrap=none --top-level-division=chapter -s -o iching.tex

and then:

xelatex iching










==========================
frontmatter for tex file:



% Options for packages loaded elsewhere
\PassOptionsToPackage{unicode}{hyperref}
\PassOptionsToPackage{hyphens}{url}
%
\documentclass[11pt]{book}
\author{Fania Everitt}
\date{15/09/2021}

\usepackage{amsmath,amssymb}
\usepackage{lmodern}
\usepackage{iftex}


\usepackage{geometry}
\geometry{
 a4paper,
 total={170mm,257mm},
 left=20mm,
 top=20mm,
 }



% I-Ching stuff
\usepackage{fontspec}
\usepackage{xeCJK}
% \setCJKmainfont{LiSong Pro}
\setCJKmainfont{SimSun}
\newCJKfontfamily{\dejavusanszh}{DejaVu Sans} % this font has the required glyphs
\newfontface{\dejavusans}{DejaVu Sans} % this font has the required glyphs
\newcommand{\iching}[1]{{\dejavusanszh\char\numexpr"4DC0+#1}}
\newcommand{\trigram}[1]{{\dejavusans\char\numexpr"2630+#1}}


\usepackage{marvosym} % for yinyang symbol

% trigrams
\usepackage{newunicodechar}
\newfontfamily\miscsymfont{DejaVu Sans}
\newunicodechar{：}{\foreignlanguage{chinese-simplified}{：}}
\newunicodechar{☯}{{\miscsymfont\symbol{"262F}}}
\newunicodechar{⚊}{{\miscsymfont\symbol{"268A}}}
\newunicodechar{⚋}{{\miscsymfont\symbol{"268B}}}
\newunicodechar{⚌}{{\miscsymfont\symbol{"268C}}}
\newunicodechar{⚍}{{\miscsymfont\symbol{"268D}}}
\newunicodechar{⚎}{{\miscsymfont\symbol{"268E}}}
\newunicodechar{⚏}{{\miscsymfont\symbol{"268F}}}
\newunicodechar{☰}{{\miscsymfont\symbol{"2630}}}
\newunicodechar{☱}{{\miscsymfont\symbol{"2631}}}
\newunicodechar{☲}{{\miscsymfont\symbol{"2632}}}
\newunicodechar{☳}{{\miscsymfont\symbol{"2633}}}
\newunicodechar{☴}{{\miscsymfont\symbol{"2634}}}
\newunicodechar{☵}{{\miscsymfont\symbol{"2635}}}
\newunicodechar{☶}{{\miscsymfont\symbol{"2636}}}
\newunicodechar{☷}{{\miscsymfont\symbol{"2637}}}
% Also define U+4DC0-U+4DFF.


% \ifPDFTeX
%   \usepackage[T1]{fontenc}
%   % \usepackage[utf8]{inputenc}
%   \usepackage{textcomp} % provide euro and other symbols
% \else % if luatex or xetex
%   \usepackage{unicode-math}
%   \defaultfontfeatures{Scale=MatchLowercase}
%   \defaultfontfeatures[\rmfamily]{Ligatures=TeX,Scale=1}
% \fi
% Use upquote if available, for straight quotes in verbatim environments
\IfFileExists{upquote.sty}{\usepackage{upquote}}{}
\IfFileExists{microtype.sty}{% use microtype if available
  \usepackage[]{microtype}
  \UseMicrotypeSet[protrusion]{basicmath} % disable protrusion for tt fonts
}{}
\makeatletter
\@ifundefined{KOMAClassName}{% if non-KOMA class
  \IfFileExists{parskip.sty}{%
    \usepackage{parskip}
  }{% else
    \setlength{\parindent}{0pt}
    \setlength{\parskip}{6pt plus 2pt minus 1pt}}
}{% if KOMA class
  \KOMAoptions{parskip=half}}
\makeatother
\usepackage{xcolor}
\IfFileExists{xurl.sty}{\usepackage{xurl}}{} % add URL line breaks if available
\IfFileExists{bookmark.sty}{\usepackage{bookmark}}{\usepackage{hyperref}}
\hypersetup{
  hidelinks,
  pdfcreator={LaTeX via pandoc}}
\urlstyle{same} % disable monospaced font for URLs
\usepackage{longtable,booktabs,array}
\usepackage{calc} % for calculating minipage widths
% Correct order of tables after \paragraph or \subparagraph
\usepackage{etoolbox}
\makeatletter
\patchcmd\longtable{\par}{\if@noskipsec\mbox{}\fi\par}{}{}
\makeatother
% Allow footnotes in longtable head/foot
\IfFileExists{footnotehyper.sty}{\usepackage{footnotehyper}}{\usepackage{footnote}}
\makesavenoteenv{longtable}
\setlength{\emergencystretch}{3em} % prevent overfull lines
\providecommand{\tightlist}{%
  \setlength{\itemsep}{0pt}\setlength{\parskip}{0pt}}
\setcounter{secnumdepth}{-\maxdimen} % remove section numbering
\ifLuaTeX
  \usepackage{selnolig}  % disable illegal ligatures
\fi


% for drawing extra Trigrams / Hexagrams
\usepackage{tikz}
\usetikzlibrary{arrows}
\usetikzlibrary{arrows.meta}

\tikzset{%
    % ->-/.default=.5%
  baseline=-0.5ex,
  % line width=.04cm,
  line cap=butt,%
  every picture/.style={line width=.04cm}
}





\begin{document}
\frontmatter

% \tableofcontents


\mainmatter