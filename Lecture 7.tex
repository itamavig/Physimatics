\documentclass[12pt]{article}

% --- Language and Font Setup (Arial Style) ---
\usepackage{polyglossia}        
\setdefaultlanguage{hebrew}     
\setotherlanguage{english}      

\usepackage{fontspec}
% "FreeSans" is the standard Linux equivalent of Arial
\setmainfont{FreeSans}
\newfontfamily\hebrewfont{FreeSans}[Script=Hebrew]
\newfontfamily\englishfont{FreeSans}

\usepackage{amsmath, amssymb, amsthm}
\usepackage{geometry}
\geometry{a4paper, margin=1in}

% --- Hebrew Theorem Environments ---
\newtheorem{theorem}{משפט}
\newtheorem{definition}{הגדרה}
\newtheorem{claim}{טענה}
\newtheorem{example}{דוגמה}
\newtheorem{proof_he}{הוכחה}

% Custom command for sets
\newcommand{\N}{\mathbb{N}}

\title{הרצאה 7: המספרים הטבעיים ואינדוקציה}
\author{סיכום הרצאה - טקסט מלא}
\date{}

\begin{document}

\maketitle

\section{בניית המספרים הטבעיים (\textenglish{Von Neumann})}


נגדיר את המספרים הטבעיים באופן רקורסיבי:
\begin{align*}
    0 &= \emptyset \\
    1 &= \{0\} = \{\emptyset\} \\
    2 &= \{0, 1\} = \{\emptyset, \{\emptyset\}\} \\
    3 &= \{0, 1, 2\} \\
    &\vdots \\
    n+1 &= n \cup \{n\} = \{0, 1, \dots, n\}
\end{align*}

\begin{definition}[סדר]
לכל שני מספרים טבעיים $m, n$ נגדיר:
$$ m < n \iff m \in n $$
כמו כן:
$$ m \le n \iff m \in n \lor m = n \iff m \subseteq n $$
\end{definition}

\section{קבוצות אינדוקטיביות והגדרת $\N$}


\begin{definition}[קבוצה אינדוקטיבית]
קבוצה $X$ נקראת \textbf{קבוצה אינדוקטיבית} אם מתקיימים שני התנאים הבאים:
\begin{enumerate}
    \item $\emptyset \in X$
    \item לכל $a \in X$ מתקיים $a \cup \{a\} \in X$ (כלומר $a+1 \in X$).
\end{enumerate}
\end{definition}

\begin{definition}[המספרים הטבעיים]
נגדיר את $\N$ כחיתוך כל הקבוצות האינדוקטיביות. 
תהי $\mathcal{A}$ משפחת כל הקבוצות האינדוקטיביות. אזי:
$$ \N = \bigcap_{A \in \mathcal{A}} A $$
\end{definition}
מכאן נובע ש-$\N$ היא הקבוצה האינדוקטיבית הקטנה ביותר (ביחס להכלה). כלומר, אם $A$ קבוצה אינדוקטיבית, אז $\N \subseteq A$.

\section{עקרון האינדוקציה המתמטית}


מתוך ההגדרה של $\N$ כקבוצה האינדוקטיבית המינימלית, נובע משפט האינדוקציה:

\begin{theorem}
תהי $A \subseteq \N$ תת-קבוצה המקיימת:
\begin{enumerate}
    \item $0 \in A$
    \item לכל $n \in \N$, אם $n \in A$ אז $n+1 \in A$.
\end{enumerate}
אזי $A = \N$.
\end{theorem}

\section{תכונות בסיסיות של הטבעיים (הוכחות מלאות)}

\subsection{תכונה 1: אפס או עוקב}


\begin{claim}
לכל $n \in \N$ מתקיים: $n=0$ או $0 < n$ (כלומר $0 \in n$).
\end{claim}

\begin{proof}
נגדיר את קבוצת האמת של הטענה $A$:
$$ A = \{ n \in \N \mid n=0 \lor n > 0 \} $$
נוכיח ש-$A = \N$ באינדוקציה:
\begin{enumerate}
    \item \textbf{בסיס האינדוקציה:} עבור $n=0$, הטענה $0=0$ היא אמת. לכן $0 \in A$.
    \item \textbf{צעד האינדוקציה:} נניח ש-$n \in A$. עלינו להוכיח ש-$n+1 \in A$.
    נפריד למקרים לגבי $n$:
    \begin{itemize}
        \item אם $n=0$: אזי $n+1 = \{0\}$. כיוון ש-$\emptyset \in \{0\}$, מתקיים $0 \in n+1$, כלומר $n+1 > 0$.
        \item אם $n > 0$: אזי $0 \in n$. כיוון ש-$n \subseteq n \cup \{n\} = n+1$, נובע מטרנזיטיביות ההכלה ש-$0 \in n+1$.
    \end{itemize}
    בשני המקרים קיבלנו $0 \in n+1$, ולכן $n+1 \in A$.
\end{enumerate}
לפי עקרון האינדוקציה, $A = \N$, והטענה נכונה לכל $n$.
\end{proof}

\subsection{תכונה 2: טרנזיטיביות ההכלה (איברים הם תת-קבוצות)}


\begin{claim}
לכל $n \in \N$, ולכל $m \in n$, מתקיים $m \subseteq n$.
\end{claim}

\begin{proof}
נגדיר את הקבוצה $A$:
$$ A = \{ n \in \N \mid \forall m \in n \implies m \subseteq n \} $$
\begin{enumerate}
    \item \textbf{בסיס ($n=0$):} $0 = \emptyset$. התנאי "לכל $m \in \emptyset$" מתקיים באופן ריק (אין איברים ב-$0$). לכן $0 \in A$.
    \item \textbf{צעד:} נניח ש-$n \in A$. עלינו להוכיח ש-$n+1 \in A$.
    יהי $m \in n+1$. לפי ההגדרה $n+1 = n \cup \{n\}$.
    לכן ייתכנו שני מצבים: $m \in n$ או $m = n$.
    \begin{itemize}
        \item \textbf{מקרה 1 ($m \in n$):} מהנחת האינדוקציה ($n \in A$) נובע ש-$m \subseteq n$.
        כיוון ש-$n \subseteq n \cup \{n\} = n+1$, נובע ש-$m \subseteq n+1$.
        \item \textbf{מקרה 2 ($m = n$):} ברור ש-$n \subseteq n \cup \{n\}$, ולכן $m \subseteq n+1$.
    \end{itemize}
    בכל מקרה קיבלנו $m \subseteq n+1$.
\end{enumerate}
לכן $n+1 \in A$. לפי אינדוקציה, הטענה נכונה לכל $n \in \N$.
\end{proof}

\section{אינדוקציה שלמה (\textenglish{Strong Induction})}


\begin{theorem}[עקרון האינדוקציה השלמה]
תהי $B \subseteq \N$. אם מתקיים התנאי הבא לכל $n \in \N$:
$$ (\forall m < n, m \in B) \implies n \in B $$
(במילים: אם כל המספרים הקטנים מ-$n$ נמצאים ב-$B$, אז גם $n$ ב-$B$). \\
אזי $B = \N$.
\end{theorem}

\begin{proof}
(הוכחה מהלוח באמצעות רדוקציה לאינדוקציה רגילה) \\
נגדיר קבוצת עזר $A$ המכילה את כל המספרים שכל קודמיהם נמצאים ב-$B$:
$$ A = \{ n \in \N \mid \forall m < n, m \in B \} $$
נוכיח ש-$A = \N$ באמצעות אינדוקציה רגילה:
\begin{enumerate}
    \item \textbf{בסיס ($n=0$):} קבוצת המספרים הקטנים מ-0 היא ריקה. התנאי "לכל $m<0, m \in B$" מתקיים באופן ריק. לכן $0 \in A$.
    \item \textbf{צעד:} נניח ש-$n \in A$.
    משמעות הדבר היא: $\forall m < n, m \in B$.
    לפי הנתון של המשפט, תנאי זה גורר ש-$n \in B$.
    
    כעת עלינו להוכיח ש-$n+1 \in A$. כלומר, עלינו להראות שלכל $k < n+1$ מתקיים $k \in B$.
    יהי $k < n+1$. אז $k \in n \cup \{n\}$, כלומר $k < n$ או $k = n$.
    \begin{itemize}
        \item אם $k < n$: הוכחנו כבר ש-$k \in B$ (כי $n \in A$).
        \item אם $k = n$: הוכחנו הרגע ש-$n \in B$.
    \end{itemize}
    לכן לכל $k < n+1$ מתקיים $k \in B$.
    מסקנה: $n+1 \in A$.
\end{enumerate}
הוכחנו באינדוקציה ש-$A = \N$.
כעת, יהי $n \in \N$ כלשהו. כיוון ש-$A = \N$, אז $n+1 \in A$.
לפי הגדרת $A$, זה אומר שכל המספרים הקטנים מ-$n+1$ נמצאים ב-$B$.
בפרט, $n < n+1$, ולכן $n \in B$.
מכאן ש-$B = \N$.
\end{proof}

\section{עקרון הסדר הטוב (\textenglish{Well-Ordering Principle})}


\begin{theorem}
לכל תת-קבוצה לא ריקה של הטבעיים $B \subseteq \N$ קיים איבר מינימלי (איבר ראשון).
\end{theorem}
הערה: עקרון זה שקול לעקרון האינדוקציה המתמטית.

\end{document}
