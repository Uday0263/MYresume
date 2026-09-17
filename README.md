```latex
\documentclass[a4paper,10pt]{article}

\usepackage[margin=0.45in]{geometry}
\usepackage[hidelinks]{hyperref}
\usepackage{titlesec}
\usepackage{enumitem}
\usepackage{tabularx}
\usepackage{fontawesome5}

\pagestyle{empty}

%==================== FORMATTING ====================

\titleformat{\section}
{\normalsize\bfseries}
{}{0em}{}[\titlerule]

\titlespacing*{\section}{0pt}{10pt}{6pt}

\setlist[itemize]{
    leftmargin=*,
    itemsep=4pt,
    topsep=3pt,
    parsep=0pt,
    partopsep=0pt
}

%==================== DOCUMENT ====================

\begin{document}

%==================== HEADER ====================

\begin{center}

{\Large\textbf{Uday Pratap Gangwar}}

\vspace{2.5mm}

\faGithub\ 
\href{https://github.com/Uday0263}{Uday0263}
\quad|\quad
\faLinkedin\ 
\href{https://linkedin.com/in/uday-pratap-gangwar-412151360/}
{uday-pratap-gangwar}
\quad|\quad
\faEnvelope\ 
\href{mailto:udayganawar@gmail.com}{udayganawar@gmail.com}
\quad|\quad
\faPhone\ +91 9838010047

\\[2.5mm]

\faCode\ 
\href{https://leetcode.com/u/Uday_2023b0131058/}{LeetCode}
\quad|\quad
\faMapMarker*\ Ghaziabad, Uttar Pradesh

\end{center}

%==================== EDUCATION ====================

\section*{Education}

\begin{tabular*}{\textwidth}{@{\extracolsep{\fill}}lr}

\textbf{B.Tech Information Technology, ABES Engineering College}
&
Nov 2023 -- Jul 2027
\\[2pt]

&
\textbf{CGPA: 8.1}
\\[5pt]

\textbf{Class XII (CBSE)}
&
\textbf{73.4\% \quad 2022}
\\[4pt]

\textbf{Class X (CBSE)}
&
\textbf{90.3\% \quad 2020}

\end{tabular*}

%==================== PROJECTS ====================

\section*{Projects}

%-------------------- BIN2BITE --------------------

\noindent
\href{https://github.com/Uday0263/Bin2Bite}
{\textbf{Bin2Bite}}
\hfill
\textit{2026}

\noindent
\textit{Client-Server Web Application}

\begin{itemize}
\item Developed a food redistribution platform that helps users discover nearby donors with excess food.
\item Implemented live location-based donor discovery and radius filtering to find available donors within a selected distance.
\item Built a client-server application that enables users to connect with nearby donors and procure available excess food.
\end{itemize}

\vspace{5pt}

%-------------------- GREEN COMPUTE --------------------

\noindent
\textbf{Green-Compute: Carbon-Aware AI Orchestration}
\hfill
\textit{Final Year Project | 2026 -- Present}

\noindent
\textit{React.js, Vite, Tailwind CSS}

\begin{itemize}
\item Developing the frontend dashboard for a carbon-aware AI workload orchestration system.
\item Building responsive interfaces to visualize workload queues, carbon intensity forecasts, execution status, and estimated emissions savings.
\item Creating reusable React components and interactive dashboard views using React.js, Vite, and Tailwind CSS.
\end{itemize}

\vspace{5pt}

%-------------------- SUPERMARKET --------------------

\noindent
\textbf{Supermarket Management System}
\hfill
\textit{Nov 2025}

\noindent
\textit{React.js, Tailwind CSS}

\begin{itemize}
\item Developed responsive frontend interfaces for managing products, billing, inventory, and supermarket-related operations.
\item Built reusable React components and interactive user interfaces using React.js and Tailwind CSS.
\end{itemize}

\vspace{5pt}

%-------------------- FOOD ORDERING --------------------

\noindent
\textbf{Food Ordering Website}
\hfill
\textit{Oct 2024}

\noindent
\textit{HTML, CSS, JavaScript}

\begin{itemize}
\item Developed a responsive food ordering website that allows users to browse food items and explore menus.
\item Created interactive and user-friendly interfaces using HTML, CSS, and JavaScript.
\end{itemize}

%==================== TECHNICAL SKILLS ====================

\section*{Technical Skills}

\begin{tabularx}{\textwidth}{@{}lX@{}}

\textbf{Languages}
&
Java, JavaScript, SQL, HTML, CSS
\\[4pt]

\textbf{Frontend}
&
React.js, Tailwind CSS, Vite
\\[4pt]

\textbf{Backend \& Database}
&
Node.js (Basic), MongoDB (Basic), SQL
\\[4pt]

\textbf{Core Concepts}
&
OOPS, DBMS, Data Structures, Problem Solving
\\[4pt]

\textbf{Developer Tools}
&
VS Code, Eclipse
\\[4pt]

\textbf{Version Control}
&
Git, GitHub
\\[4pt]

\textbf{DSA}
&
Arrays, Strings, HashMaps, Linked Lists

\end{tabularx}

%==================== ACHIEVEMENTS ====================

\section*{Achievements}

\begin{itemize}

\item Solved \textbf{250+ Data Structures and Algorithms problems} on
\href{https://leetcode.com/u/Uday_2023b0131058/}{LeetCode}.

\item Completed \textbf{The Complete Full Stack Web Development Bootcamp} on Udemy.

\item Earned HackerRank
\href{https://www.hackerrank.com/certificates/81b14bae5049}
{\textbf{Problem Solving (Basic)}} certification.

\item Earned HackerRank
\href{https://www.hackerrank.com/certificates/2f1832d78ae4}
{\textbf{Problem Solving (Intermediate)}} certification.

\end{itemize}

%==================== EXTRACURRICULAR ====================

\section*{Extracurricular Activities}

\begin{itemize}

\item Participated in Aderma, a college hackathon
\hfill
\textit{Sep 2024}

\item Assisted in organizing an AI Prompt-Based Image Generation Competition
\hfill
\textit{2024}

\end{itemize}

\end{document}
```

**Only Bin2Bit was changed**:

* `Bin2Bit` → `Bin2Bite`
* GitHub link → `Bin2Bite`
* Binary-converter description → food redistribution/location/radius-filter description
* `HTML, CSS, JavaScript` → `Client-Server Web Application`

Everything else—including your margins, spacing, projects, skills, achievements, and extracurricular sections—is unchanged.
