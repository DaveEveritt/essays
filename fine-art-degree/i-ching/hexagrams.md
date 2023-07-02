# Hexagrams


https://en.wikipedia.org/wiki/List_of_hexagrams_of_the_I_Ching

01 ䷀	02 ䷁	03 ䷂	04 ䷃	05 ䷄	06 ䷅	07 ䷆	08 ䷇	 
09 ䷈	10 ䷉	11 ䷊	12 ䷋	13 ䷌	14 ䷍	15 ䷎	16 ䷏  
17 ䷐	18 ䷑	19 ䷒	20 ䷓	21 ䷔	22 ䷕	23 ䷖	24 ䷗	 
25 ䷘	26 ䷙	27 ䷚	28 ䷛	29 ䷜	30 ䷝	31 ䷞	32 ䷟  
33 ䷠	34 ䷡	35 ䷢	36 ䷣	37 ䷤	38 ䷥	39 ䷦	40 ䷧	 
41 ䷨	42 ䷩	43 ䷪	44 ䷫	45 ䷬	46 ䷭	47 ䷮	48 ䷯  
49 ䷰	50 ䷱	51 ䷲	52 ䷳	53 ䷴	54 ䷵	55 ䷶	56 ䷷	 
57 ䷸	58 ䷹	59 ䷺	60 ䷻	61 ䷼	62 ䷽	63 ䷾	64 ䷿



⚊ ⚋ ⚌ ⚍ ⚎ ⚏
☰ ☱ ☲ ☳ ☴ ☵ ☶ ☷ 
☯


\trigram{0} \trigram{1} \trigram{2} \trigram{3}
\trigram{4} \trigram{5} \trigram{6} \trigram{7}


\iching{0}
\iching{1}
\iching{2}
\iching{3}
\iching{4}
\iching{5}
\iching{6}
\iching{7}

\iching{8}
\iching{9}
\iching{10}
\iching{11}
\iching{12}
\iching{13}
\iching{14}
\iching{15}

\iching{16}
\iching{17}
\iching{18}
\iching{19}
\iching{20}
\iching{21}
\iching{22}
\iching{23}

\iching{24}
\iching{25}
\iching{26}
\iching{27}
\iching{28}
\iching{29}
\iching{20}
\iching{31}

\iching{32}
\iching{33}
\iching{34}
\iching{35}
\iching{36}
\iching{37}
\iching{38}
\iching{39}

\iching{40}
\iching{41}
\iching{42}
\iching{43}
\iching{44}
\iching{45}
\iching{46}
\iching{47}

\iching{48}
\iching{49}
\iching{50}
\iching{51}
\iching{52}
\iching{53}
\iching{54}
\iching{55}

\iching{56}
\iching{57}
\iching{58}
\iching{59}
\iching{60}
\iching{61}
\iching{62}
\iching{63}

% I-Ching stuff
\usepackage{fontspec}
\usepackage{xeCJK}
% \setCJKmainfont{LiSong Pro}
\setCJKmainfont{SimSun}
\newCJKfontfamily{\dejavusanszh}{DejaVu Sans} % this font has the required glyphs
\newfontface{\dejavusans}{DejaVu Sans} % this font has the required glyphs
\newcommand{\iching}[1]{{\dejavusanszh\char\numexpr"4DC0+#1}}
\newcommand{\trigram}[1]{{\dejavusans\char\numexpr"2630+#1}}




MOVING LINES: 
YANG to YIN:
\begin{tikzpicture}[baseline=+1ex]\draw(0,0.325)--(0.3,0.325);\draw[line width=.02cm](0.15,0.325)circle[line width=.02cm,radius=0.035cm];\end{tikzpicture}

YIN to YANG:
\begin{tikzpicture}[baseline=+0.2ex]\draw(0,0.13)--(0.12,0.13);\draw(0.18,0.13)--(0.3,0.13);\draw[line width=.02cm](0.13,0.165)--(0.17,0.0925);\draw[line width=.02cm](0.17,0.165)--(0.13,0.0925);\end{tikzpicture}


\begin{tikzpicture}[baseline=+0.1ex]\draw(0,0.325)--(0.3,0.325);\draw[line width=.02cm](0.15,0.325)circle[line width=.02cm,radius=0.035cm];\draw(0,0.26)--(0.12,0.26);\draw(0.18,0.26)--(0.3,0.26);\draw(0,0.195)--(0.3,0.195);\draw(0,0.13)--(0.12,0.13);\draw(0.18,0.13)--(0.3,0.13);\draw[line width=.02cm](0.13,0.165)--(0.17,0.0925);\draw[line width=.02cm](0.17,0.165)--(0.13,0.0925);\draw(0,0.065)--(0.3,0.065);\draw(0,0)--(0.3,0);\end{tikzpicture}





% \begin{tikzpicture}\draw[thick](0,0)--(0.3,0);\end{tikzpicture}
% \begin{tikzpicture}\draw[thick](0,0)--(0.13,0);\draw[thick](0.17,0)--(0.3,0);\end{tikzpicture}

% \tikz \draw (-1.5,0) -- (1.5,0) -- (0,-1.5) -- (0,1.5);
\tikz\draw[very thick](0,0)--(0.3,0);
\tikz\draw[very thick](0,0)--(0.13,0);\tikz\draw[very thick](0.17,0)--(0.3,0);

\begin{tikzpicture}[baseline=-0.5ex]\draw[very thick](0,0.1)--(0.13,0.1);\draw[very thick](0.17,0.1)--(0.3,0.1);\draw[very thick](0,0)--(0.3,0);\end{tikzpicture}

\begin{tikzpicture}\draw[very thick](0,0.2)--(0.3,0.2);\end{tikzpicture}


\begin{tikzpicture}[baseline=-0.5ex]\draw[very thick](0,0.1)--(0.13,0.1);\draw[very thick](0.17,0.1)--(0.3,0.1);\draw[very thick](0,0)--(0.3,0);\end{tikzpicture}


\begin{tikzpicture}[baseline=-0.5ex]
  \draw[very thick](0,0.1)--(0.3,0.1);
  \draw[very thick](0,0)--(0.13,0);
  \draw[very thick](0.17,0)--(0.3,0);
\end{tikzpicture}


\begin{tikzpicture}[baseline=-0.5ex]\draw[very thick](0,0.1)--(0.3,0.1);\draw[very thick](0,0)--(0.13,0);\draw[very thick](0.17,0)--(0.3,0);\end{tikzpicture}


\begin{tikzpicture}[baseline=-0.5ex]
  \draw[very thick](0,0.1)--(0.3,0.1);
  \draw[very thick](0,0)--(0.3,0);
\end{tikzpicture}

\begin{tikzpicture}[baseline=-0.5ex]\draw[very thick](0,0.1)--(0.3,0.1);\draw[very thick](0,0)--(0.3,0);\end{tikzpicture}

\begin{tikzpicture}[baseline=-0.5ex]
  \draw[very thick](0,0.1)--(0.13,0.1);
  \draw[very thick](0.17,0.1)--(0.3,0.1);
  \draw[very thick](0,0)--(0.13,0);
  \draw[very thick](0.17,0)--(0.3,0);
\end{tikzpicture}

\begin{tikzpicture}[baseline=-0.5ex]\draw[very thick](0,0.1)--(0.13,0.1);\draw[very thick](0.17,0.1)--(0.3,0.1);\draw[very thick](0,0)--(0.13,0);\draw[very thick](0.17,0)--(0.3,0);\end{tikzpicture}


\begin{tikzpicture}[baseline=-0.5ex]
  \draw(0,0.325)--(0.3,0.325);\draw[line width=.02cm](0.15,0.325)circle[line width=.02cm,radius=0.035cm];
\end{tikzpicture}

\begin{tikzpicture}[baseline=-0.5ex]
  \draw(0,0.13)--(0.12,0.13);\draw(0.18,0.13)--(0.3,0.13);
  \draw[line width=.02cm](0.13,0.165)--(0.17,0.0925);\draw[line width=.02cm](0.17,0.165)--(0.13,0.0925);
\end{tikzpicture}

\begin{tikzpicture}[baseline=-0.5ex]
  \draw(0,0.325)--(0.3,0.325);\draw[line width=.02cm](0.15,0.325)circle[line width=.02cm,radius=0.035cm];
  \draw(0,0.26)--(0.12,0.26);\draw(0.18,0.26)--(0.3,0.26);
  \draw(0,0.195)--(0.3,0.195);
  \draw(0,0.13)--(0.12,0.13);\draw(0.18,0.13)--(0.3,0.13);
  \draw[line width=.02cm](0.13,0.165)--(0.17,0.0925);\draw[line width=.02cm](0.17,0.165)--(0.13,0.0925);
  \draw(0,0.065)--(0.3,0.065);
  \draw(0,0)--(0.3,0);
\end{tikzpicture}

\begin{tikzpicture}[baseline=-0.5ex]\draw(0,0.325)--(0.3,0.325);\draw[line width=.02cm](0.15,0.325)circle[line width=.02cm,radius=0.035cm];\end{tikzpicture}

\begin{tikzpicture}[baseline=-0.5ex]\draw(0,0.13)--(0.12,0.13);\draw(0.18,0.13)--(0.3,0.13);\draw[line width=.02cm](0.13,0.165)--(0.17,0.0925);\draw[line width=.02cm](0.17,0.165)--(0.13,0.0925);\end{tikzpicture}

\begin{tikzpicture}[baseline=-0.5ex]\draw(0,0.325)--(0.3,0.325);\draw[line width=.02cm](0.15,0.325)circle[line width=.02cm,radius=0.035cm];\draw(0,0.26)--(0.12,0.26);\draw(0.18,0.26)--(0.3,0.26);\draw(0,0.195)--(0.3,0.195);\draw(0,0.13)--(0.12,0.13);\draw(0.18,0.13)--(0.3,0.13);\draw[line width=.02cm](0.13,0.165)--(0.17,0.0925);\draw[line width=.02cm](0.17,0.165)--(0.13,0.0925);\draw(0,0.065)--(0.3,0.065);\draw(0,0)--(0.3,0);\end{tikzpicture}


\tikzset{%
    line width=2mm
}

\begin{tikzpicture}[line width=10mm] % overwrites the above
  % will have width of 10mm
  \draw (0,0) -- (1,0);
  % will have width of 3mm, will override the above
  \draw[line width=3mm] (0,0) -- (1,0);
\end{tikzpicture}

\begin{tikzpicture}
  % will have width of 2mm, due to the globally defined style.
  \draw (0,0) -- (1,0);
  % will have width of 7mm, overrides the global set style.
  \draw[line width=7mm] (0,0) -- (1,0);
\end{tikzpicture}