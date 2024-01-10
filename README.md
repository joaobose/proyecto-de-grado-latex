# tesis-andres
Libro de tesis (LaTeX)

  
% Please add the following required packages to your document preamble:
% \usepackage{multirow}
% \usepackage{graphicx}
\begin{table}[H]
\centering
\resizebox{\textwidth}{!}{%
\begin{tabular}{cccc}
\hline
 & Porcentaje & \begin{tabular}[c]{@{}c@{}}Factor de \\ potencia\end{tabular} & \begin{tabular}[c]{@{}c@{}}Limite \\ dispositivos \\ Clase 2\end{tabular} \\ \hline
\multirow{3}{*}{\begin{tabular}[c]{@{}c@{}}Valor de \\ corriente\end{tabular}} & 5\% In & 1 & \multirow{3}{*}{±2,5\%} \\
 & \multirow{2}{*}{10\% In} & 0,8 ind &  \\
 &  & 0,5 cap &  \\
\multirow{3}{*}{\begin{tabular}[c]{@{}c@{}}Valor de voltaje\\ con\\ ±\%10 Fn\end{tabular}} & \multirow{2}{*}{10\% In} & 1 & ±1,5\% \\
 &  & 1 & ±1,0\% \\
 & In & 0,5 ind & ±1,5\% \\ \hline
\end{tabular}%
}
\end{table}

% Please add the following required packages to your document preamble:
% \usepackage{graphicx}
\begin{table}[H]
\centering
\resizebox{\textwidth}{!}{%
\begin{tabular}{cccc}
\hline
 & \multicolumn{3}{c}{Bombillo ahorrador} \\ \hline
Parametros & Medidor & Osciloscopio & Error \% \\ \hline
\begin{tabular}[c]{@{}c@{}}Frecuencia\\ fundamental (Hz)\end{tabular} & 60,001 & 60,002 & 0,0033 \\
Vrms (V) & 119,013 & 117,929 & 1,1081 \\
Irms (A) & 0,099 & 0,089 & 11,2360 \\
Desfase (grados) & 288,91 & 289,743 & 0,2875 \\
THD I\% & 30,2571 & 30,705 & 1,4590 \\
THD V\% & 0,363 & 0,214 & 69,6262 \\
\begin{tabular}[c]{@{}c@{}}Potencia\\ aparente (VA)\end{tabular} & 11,831 & 10,444 & 13,2804 \\
\begin{tabular}[c]{@{}c@{}}Potencia\\ activa (W)\end{tabular} & 3,48 & 3,245 & 7,2419 \\
\begin{tabular}[c]{@{}c@{}}Potencia\\ reactiva (VAR)\end{tabular} & 11,307 & 9,927 & 13,9015 \\
\begin{tabular}[c]{@{}c@{}}Factor de\\ potencia\end{tabular} & 0,294 & 0,311 & 5,4662 \\
Energia (W/Ciclo) & 0,696 & 0,649 & 7,2419 \\
Cuadrante & 1 & 1 & 0 \\ \hline
\end{tabular}%
}
\end{table}

% Please add the following required packages to your document preamble:
% \usepackage{graphicx}
\begin{table}[H]
\centering
\resizebox{\textwidth}{!}{%
\begin{tabular}{cccc}
\hline
 & \multicolumn{3}{c}{Rectificador de onda completa} \\ \hline
Parametros & Medidor & Osciloscopio & Error \% \\ \hline
\begin{tabular}[c]{@{}c@{}}Frecuencia\\ fundamental (Hz)\end{tabular} & 60,003 & 60,001 & 0,0033 \\
Vrms (V) & 118,879 & 120,214 & 1,1352 \\
Irms (A) & 13,013 & 12,603 & 3,2041 \\
Desfase (grados) & 5,502 & 309,382 & 117,0981 \\
THD I\% & 33,946 & 35,461 & 4,3075 \\
THD V\% & 0,608 & 0,687 & 10,4412 \\
\begin{tabular}[c]{@{}c@{}}Potencia\\ aparente (VA)\end{tabular} & 1546,935 & 1515,079 & 2,0350 \\
\begin{tabular}[c]{@{}c@{}}Potencia\\ activa (W)\end{tabular} & 7,092 & 8,704 & 17,0753 \\
\begin{tabular}[c]{@{}c@{}}Potencia\\ reactiva (VAR)\end{tabular} & 1546,919 & 1515,054 & 2,0355 \\
\begin{tabular}[c]{@{}c@{}}Factor de\\ potencia\end{tabular} & 0,005 & 0,009 & 44,4444 \\
Energia (W/Ciclo) & 1,4184 & 1,741 & 17,0753 \\
Cuadrante & - & - & - \\ \hline
\end{tabular}%
}
\end{table}

% Please add the following required packages to your document preamble:
% \usepackage{multirow}
% \usepackage{graphicx}
% \usepackage{lscape}
\begin{landscape}
\begin{table}[H]
\centering
\resizebox{\textwidth}{!}{%
\begin{tabular}{cccllllllllllllllll}
\cline{1-3} \cline{5-7} \cline{9-11} \cline{13-15} \cline{17-19}
\multirow{2}{*}{N} & \multicolumn{2}{c}{Error \%} &  & N & Error \% &  &  & N &  & Error \% &  & N &  & Error \% &  & N &  & Error \% \\ \cline{2-3} \cline{5-7} \cline{9-11} \cline{13-15} \cline{17-19} 
 & Voltaje & Corriente &  &  & Voltaje & Corriente &  &  & Voltaje & Corriente &  &  & Voltaje & Corriente &  & N & Voltaje & Corriente \\ \cline{1-3} \cline{6-7} \cline{10-11} \cline{14-15} \cline{18-19} 
0 & 58.99 & 3.02 &  & 10 & 196.15 & 4.48 &  & 20 & 49.11 & 20.70 &  & 30 & 32.04 & 33.85 &  & 40 & 60.81 & 47.92 \\
1 & 1.12 & 4.34 &  & 11 & 20.02 & 6.71 &  & 21 & 11.90 & 21.56 &  & 31 & 17.89 & 32.90 &  & 41 & 37.59 & 45.74 \\
2 & 57.39 & 2.21 &  & 12 & 59.51 & 7.57 &  & 22 & 15.97 & 21.89 &  & 32 & 27.88 & 33.55 &  & 42 & 13.04 & 47.12 \\
3 & 46.59 & 2.41 &  & 13 & 4.14 & 7.82 &  & 23 & 12.56 & 23.51 &  & 33 & 17.49 & 40.69 &  & 43 & 25.65 & 46.24 \\
4 & 14.81 & 1.62 &  & 14 & 11.80 & 9.94 &  & 24 & 27.22 & 23.11 &  & 34 & 66.67 & 41.29 &  & 44 & 47.50 & 49.37 \\
5 & 36.07 & 0.06 &  & 15 & 3.62 & 11.02 &  & 25 & 14.17 & 27.63 &  & 35 & 25.89 & 40.69 &  & 45 & 21.14 & 50.65 \\
6 & 13.64 & 0.70 &  & 16 & 307.41 & 13.14 &  & 26 & 11.73 & 30.71 &  & 36 & 37.84 & 39.42 &  & 46 & 45.45 & 52.38 \\
7 & 2.52 & 1.80 &  & 17 & 7.71 & 17.43 &  & 27 & 16.33 & 35.57 &  & 37 & 29.79 & 40.65 &  & 47 & 34.66 & 46.51 \\
8 & 159.46 & 2.91 &  & 18 & 47.95 & 17.74 &  & 28 & 10.42 & 33.71 &  & 38 & 72.80 & 44.44 &  & 48 & 90.79 & 41.67 \\
9 & 2.89 & 3.93 &  & 19 & 9.72 & 17.97 &  & 29 & 16.80 & 34.98 &  & 39 & 23.83 & 46.81 &  & 49 & 36.64 & 61.54 \\ \cline{1-3} \cline{5-7} \cline{9-11} \cline{13-15} \cline{17-19} 
\end{tabular}%
}
\end{table}
\end{landscape}