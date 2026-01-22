%----------------------------------------------------------------------------------------
%	PACKAGES AND OTHER DOCUMENT CONFIGURATIONS
%----------------------------------------------------------------------------------------
\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}

% Adjust margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

%----------------------------------------------------------------------------------------
%	RESUME STARTS HERE
%----------------------------------------------------------------------------------------
\begin{document}

%----------HEADING----------
\begin{center}
    \textbf{\Huge \scshape [YOUR NAME]} \\ \vspace{1pt}
    Cobh, Co. Cork \\ \vspace{1pt}
    \small [PHONE NUMBER] $|$ \href{mailto:[EMAIL]}{[EMAIL]} $|$ 
    \href{[LINKEDIN URL]}{LinkedIn} $|$
    \href{[GITHUB URL]}{\textbf{GitHub: github.com/[USERNAME]}}
\end{center}


%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {University College Cork (UCC)}{Cork, Ireland}
      {BSc Mathematical Sciences}{Sept. 2024 -- Present}
      \resumeItemListStart
        \resumeItem{\textbf{Quantitative Aptitude:} Achieved \textbf{95\% (19/20)} in Linear Algebra Mid-Term.}
        \resumeItem{Relevant Modules: Linear Algebra, Calculus, Python Programming, Physics \& Mechanics.}
      \resumeItemListEnd

    \resumeSubheading
      {Coláiste Muire, Cobh}{Cork, Ireland}
      {Leaving Certificate}{2018 -- 2024}
      \resumeItemListStart
        \resumeItem{\textbf{Results:} \textbf{601 Points} (Top 0.5\% Nationally).}
        \resumeItem{Key Grades: \textbf{Mathematics (H1/97.5\%)}, \textbf{Physics (H1/98\%)}, \textbf{Applied Maths (H1/95\%)}.}
        \resumeItem{Awards: 1st Place in Year (Cohort of 100) for Standardised Maths Examination.}
      \resumeItemListEnd
  \resumeSubHeadingListEnd


%-----------PROJECTS-----------
\section{Quantitative Projects}
  \resumeSubHeadingListStart
    \resumeProjectHeading
      {\textbf{Time-Series Data Modelling (Python)} $|$ \emph{NumPy, SciPy, Matplotlib}}{2024}
      \resumeItemListStart
        \resumeItem{Performed statistical analysis on a 26-year volatile dataset to model non-linear trends in population decline.}
        \resumeItem{Built a custom Python model using \textbf{SciPy (curve\_fit)} to optimize parameters and minimize the mean squared error between predicted values and historical data.}
        \resumeItem{Applied a "Phased Approach" to handle structural breaks in the data, combining polynomial trends with variable-amplitude sinusoidal functions to capture volatility.}
      \resumeItemListEnd
      
    \resumeProjectHeading
      {\textbf{Financial Controller (Mini-Company Enterprise)} $|$ \emph{Excel, Financial Modelling}}{2021 -- 2022}
      \resumeItemListStart
        \resumeItem{Co-founded a retail business achieving over \textbf{€5,000 in turnover}.}
        \resumeItem{Built a custom Excel financial model to track daily cash flow, profit margins, and inventory levels.}
        \resumeItem{Managed P\&L and controlled expenditure to ensure business solvency and maximize profit.}
      \resumeItemListEnd
  \resumeSubHeadingListEnd


%-----------SKILLS-----------
\section{Technical Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Programming}{: Python (NumPy, SciPy, Matplotlib), LaTeX, Excel (Advanced Formulas/Pivot Tables).} \\
     \textbf{Maths}{: Differential Equations, Curve Fitting, Statistical Analysis, Mechanics.} \\
    }}
 \end{itemize}


%-----------STRATEGIC INTERESTS-----------
\section{Strategic Interests}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Poker \& Probability}{: Organizer of a weekly Probability \& Poker study group. Applying mathematical concepts (EV, Variance) to real-time decision-making.} \\
     \textbf{Competitive Golf}{: \textbf{5 Handicap}. Junior Captain (2022). Requires risk assessment and consistent technical improvement.} \\
    }}
 \end{itemize}


%-----------EXPERIENCE-----------
\section{Experience}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Pro Shop Assistant}{Cobh, Cork}
      {Cobh Golf Club}{Sept 2022 -- Present}
      \resumeItemListStart
        \resumeItem{Manage retail operations, high-volume transaction handling, and inventory management.}
        \resumeItem{Demonstrate reliability and time management, balancing 15+ hours weekly with full-time university studies.}
      \resumeItemListEnd
      
    \resumeSubheading
      {Private Mathematics Tutor}{Cork}
      {Self-Employed}{2022 -- Present}
      \resumeItemListStart
        \resumeItem{Specialise in teaching students to understand mathematical logic rather than rote memorization.}
        \resumeItem{Managed client scheduling and communicated progress reports to parents.}
      \resumeItemListEnd

  \resumeSubHeadingListEnd

\end{document}
