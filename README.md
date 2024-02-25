# DFA illustration

$$
\documentclass[12pt]{article}
\usepackage{tikz}

\begin{document}
    \begin{center}
        \begin{tikzpicture}[scale=0.2]
            \tikzstyle{every node}+=[inner sep=0pt]
                \draw [black] (4,-7.9) circle (3);
                \draw (4,-7.9) node {$q1$};
                \draw [black] (14.3,-7.9) circle (3);
                \draw (14.3,-7.9) node {$q2$};
                \draw [black] (30.1,-7.9) circle (3);
                \draw (30.1,-7.9) node {$q3$};
                \draw [black] (49.8,-7.9) circle (3);
                \draw (49.8,-7.9) node {$q4$};
                \draw [black] (11.4,-27.7) circle (3);
                \draw (11.4,-27.7) node {$q5$};
                \draw [black] (33.2,-37.3) circle (3);
                \draw (33.2,-37.3) node {$q6$};
                \draw [black] (47,-39.2) circle (3);
                \draw (47,-39.2) node {$q7$};
                \draw [black] (63.6,-36.6) circle (3);
                \draw (63.6,-36.6) node {$q9$};
                \draw [black] (63.6,-36.6) circle (2.4);
                \draw [black] (47,-52.1) circle (3);
                \draw (47,-52.1) node {$q8$};
                \draw [black] (47,-52.1) circle (2.4);
                \draw [black] (75.6,-4.2) circle (3);
                \draw (75.6,-4.2) node {$q10$};
                \draw [black] (5.787,-5.536) arc (127.39795:52.60205:5.537);
                \fill [black] (12.51,-5.54) -- (12.18,-4.65) -- (11.57,-5.45);
                \draw (9.15,-3.9) node [above] {$Psi$};
                \draw [black] (12.694,-10.388) arc (-48.80323:-131.19677:5.381);
                \fill [black] (5.61,-10.39) -- (5.88,-11.29) -- (6.54,-10.54);
                \draw (9.15,-12.22) node [below] {$Pi$};
                \draw [black] (17.3,-7.9) -- (27.1,-7.9);
                \fill [black] (27.1,-7.9) -- (26.3,-7.4) -- (26.3,-8.4);
                \draw (22.2,-7.4) node [above] {$Phi$};
                \draw [black] (15.255,-5.068) arc (189.10041:-98.89959:2.25);
                \draw (20.81,-2.64) node [above] {$Psi$};
                \fill [black] (17.13,-6.94) -- (18,-7.3) -- (17.84,-6.32);
                \draw [black] (33.1,-7.9) -- (46.8,-7.9);
                \fill [black] (46.8,-7.9) -- (46,-7.4) -- (46,-8.4);
                \draw (39.95,-7.4) node [above] {$Psi$};
                \draw [black] (50.416,-4.976) arc (195.84522:-92.15478:2.25);
                \draw (55.7,-2.1) node [above] {$Psi$};
                \fill [black] (52.5,-6.61) -- (53.4,-6.87) -- (53.13,-5.91);
                \draw [black] (13.777,-25.869) arc (126.83753:107.716:112.291);
                \fill [black] (46.93,-8.77) -- (46.02,-8.54) -- (46.32,-9.49);
                \draw (26.15,-15.42) node [above] {$Psi-{g}$};
                \draw [black] (47.409,-9.712) arc (-53.57623:-71.87024:117.298);
                \fill [black] (14.26,-26.8) -- (15.18,-27.03) -- (14.87,-26.08);
                \draw (32.84,-20.09) node [below] {$Pi$};
                \draw [black] (34.68,-34.69) -- (48.32,-10.51);
                \fill [black] (48.32,-10.51) -- (47.5,-10.96) -- (48.37,-11.45);
                \draw (42.16,-23.81) node [right] {$Psi-{o,r}$};
                \draw [black] (14.338,-28.306) arc (76.62318:55.8426:49.777);
                \fill [black] (14.34,-28.31) -- (15,-28.98) -- (15.23,-28);
                \draw (24.18,-30.66) node [above] {$Pi$};
                \draw [black] (44.124,-40.034) arc (-80.04324:-115.63529:13.84);
                \fill [black] (44.12,-40.03) -- (43.25,-39.68) -- (43.42,-40.66);
                \draw (39.52,-40.71) node [below] {$o$};
                \draw [black] (49.881,-38.366) arc (104.57342:93.23001:54.898);
                \fill [black] (60.6,-36.69) -- (59.77,-36.23) -- (59.83,-37.23);
                \draw (54.8,-36.67) node [above] {$v$};
                \draw [black] (44.327,-53.439) arc (-71.80012:-202.20495:10.217);
                \fill [black] (44.33,-53.44) -- (43.41,-53.21) -- (43.72,-54.16);
                \draw (33.13,-52.17) node [left] {$r$};
                \draw [black] (50.386,-10.842) arc (9.56591:-19.7897:50.653);
                \fill [black] (50.39,-10.84) -- (50.03,-11.71) -- (51.01,-11.55);
                \draw (51.52,-23.84) node [right] {$Psi-{v}$};
                \draw [black] (14.386,-27.418) arc (93.42669:50.7689:43.854);
                \fill [black] (14.39,-27.42) -- (15.21,-27.87) -- (15.15,-26.87);
                \draw (31.66,-28.91) node [above] {$Pi$};
                \draw [black] (52.754,-8.409) arc (76.35059:-83.60009:22.162);
                \fill [black] (52.75,-8.41) -- (53.41,-9.08) -- (53.65,-8.11);
                \draw (70.23,-31.38) node [right] {$Psi$};
                \draw [black] (44.482,-53.728) arc (-60.88558:-187.96737:22.813);
                \fill [black] (10.79,-30.64) -- (10.18,-31.36) -- (11.17,-31.5);
                \draw (19.15,-53.11) node [below] {$Pi$};
                \draw [black] (61.371,-38.606) arc (-50.64991:-148.70165:32.604);
                \fill [black] (12.84,-30.33) -- (12.83,-31.27) -- (13.68,-30.76);
                \draw (34.61,-46.16) node [below] {$Pi$};
                \draw [black] (52.073,-9.857) arc (46.9162:4.44367:36.372);
                \fill [black] (52.07,-9.86) -- (52.32,-10.77) -- (53,-10.04);
                \draw (60.72,-19.59) node [right] {$Psi$};
                \draw [black] (30.229,-36.888) arc (-100.13179:-127.40242:38.285);
                \fill [black] (30.23,-36.89) -- (29.53,-36.26) -- (29.35,-37.24);
                \draw (20.56,-34.75) node [below] {$g$};
                \draw [black] (76.923,-6.88) arc (54:-234:2.25);
                \draw (75.6,-11.45) node [below] {$Sigma$};
                \fill [black] (74.28,-6.88) -- (73.4,-7.23) -- (74.21,-7.82);
        \end{tikzpicture}
    \end{center}
\end{document}
$$