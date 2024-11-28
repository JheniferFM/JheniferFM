\documentclass[letterpaper,11pt]{article}

\usepackage[utf8]{inputenc}  % Suporte a acentuação
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
\input{glyphtounicode}

% Font options
\usepackage[sfdefault]{roboto}  % Sans-serif font

% Custom header
\pagestyle{fancy}
\fancyhf{}
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Margin and page layout adjustments
\addtolength{\oddsidemargin}{-0.7in}
\addtolength{\evensidemargin}{-0.7in}
\addtolength{\textwidth}{1.4in}
\addtolength{\topmargin}{-.8in}
\addtolength{\textheight}{1.4in}

% URL style
\urlstyle{same}
\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Section formatting
\titleformat{\section}{\Large\bfseries\scshape\raggedright}{}{0em}{}[\titlerule]
\titlespacing{\section}{0pt}{1.5ex plus 0.5ex minus 0.2ex}{1.5ex plus 0.2ex}

\titleformat{\subsection}{\large\bfseries\raggedright}{}{0em}{}
\titlespacing{\subsection}{0pt}{1.5ex plus 0.5ex minus 0.2ex}{1ex plus 0.2ex}

% Ensure PDF is machine readable
\pdfgentounicode=1

% Custom commands
\newcommand{\resumeItem}[1]{\item\small{#1}}
\newcommand{\resumeSubheading}[4]{
\vspace{-2pt}\item
  \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
    \textbf{#1} & #2 \\
    \textit{#3} & \textit{#4} \\
  \end{tabular*}\vspace{-5pt}
}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}
\newcommand{\resumeSubHeadingList}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeProject}[3]{
    \item[]\textbf{#1}
    \begin{itemize}[leftmargin=0.2in, label={$\bullet$}]
        \resumeItem{#2}
        \resumeItem{#3}
    \end{itemize}
}
\newcommand{\resumeLink}[2]{\item[]\href{#1}{#2}}

\begin{document}

\begin{center}
  \textbf{\Huge Jhenifer Meneses} \\
  \small (61) 99198-77252 $|$ \href{mailto:jhenifer.meneses10@gmail.com}{jhenifer.meneses10@gmail.com} $|$ 
  \href{https://jheniferfm.github.io/Portf-lio}{https://jheniferfm.github.io/Portf-lio/}
\end{center}

\fontsize{11}{13}\selectfont  % Define o tamanho da fonte como 11pt e o espaçamento entre linhas como 13pt

\section*{PROFESSIONAL SUMMARY}
I am an enthusiastic student of Systems Analysis and Development (3rd semester) with solid experience in Power BI. I create interactive dashboards and dynamic reports, transforming data into valuable insights. I have hands-on experience in data integration, creating visualizations, and personalizing dashboards to support strategic decision-making. Additionally, I have development skills in Python, JavaScript, and SQL, along with expertise in automating processes, integrating data, and optimizing workflows. 

\section{Education}
\resumeSubHeadingList
  \resumeSubheading
      {Centro Universitário de Brasília (UNICEUB)}{}
      {}
      {July 2023 - December 2025}
      {Bachelor in Systems Analysis and Development}
\resumeSubHeadingListEnd

\section{Key Projects}
\resumeSubHeadingList

  \item[] \textbf{Currency Converter (Web App)}
  \begin{itemize}[leftmargin=0.25in, label={$\bullet$}]
      \resumeItem{Developed a currency converter for converting Brazilian Real to USD, EUR, and Bitcoin using an API.}
      \resumeItem{\href{https://jheniferfm.github.io/Conversor-de-moedas/}{Live Demo: https://jheniferfm.github.io/Conversor-de-moedas/}}
  \end{itemize}

  \item[] \textbf{Weather Forecast Dashboard}
  \begin{itemize}[leftmargin=0.25in, label={$\bullet$}]
      \resumeItem{Created a weather forecasting web application that provides real-time weather information for a specific city.}
      \resumeItem{\href{https://jheniferfm.github.io/Previs-o-do-tempo/}{Live Demo: https://jheniferfm.github.io/Previs-o-do-tempo/}}
  \end{itemize}

  \item[] \textbf{Sales Analysis Dashboard (Power BI)}
  \begin{itemize}[leftmargin=0.25in, label={$\bullet$}]
      \resumeItem{Developed an interactive Power BI dashboard for analyzing fictional sales data, including advanced filtering and visualization.}
      \resumeItem{Used Python (pandas, numpy) for data manipulation and Excel file generation.}
      \resumeItem{\href{https://github.com/jheniferfm/Dashboard-Vendas}{GitHub: https://github.com/jheniferfm/Dashboard-Vendas}}
  \end{itemize}

\resumeSubHeadingListEnd

\section{Skills}

\resumeSubHeadingList
    \resumeSubheading
        {Systems Development & Automation:}{}
        {Python, JavaScript, SQL, HTML, CSS}{}
        {Web application development, Process automation, Data integration, API integration.}{}
\resumeSubHeadingList
\vspace{0.5em}
\resumeSubHeadingList
    \resumeSubheading
        {Power BI & Data Analysis:}{}
        {Power BI, DAX, Data Modeling, Data Transformation}{}
        {Creation of interactive dashboards, Dynamic reporting, Data analysis for business insights.}{}
\resumeSubHeadingList
\vspace{0.5em}
\resumeSubHeadingList
    \resumeSubheading
        {Technologies:}{}
        {Git, GitHub, Linux (Ubuntu), Windows 10/11, Microsoft 365, Google Analytics}{}
        {Version control, Cloud computing, Microsoft Office Suite.}{}
\resumeSubHeadingListEnd

\section{Experience}
\resumeSubHeadingList
    \resumeSubheading
        {Internship in Systems Infrastructure and Automation - IGUT}{}
        {Network maintenance and automated process implementation.}{}
    \resumeSubheading
        {Internship in Data Analysis - Organization of the Amazon Cooperation Treaty (OTCA)}{}
        {Responsible for data analysis and report development.}{}
\resumeSubHeadingListEnd

\section{Languages}
\resumeSubHeadingList
        {Portuguese (Native), English (Intermediate)}{}
\resumeSubHeadingListEnd

\section{Certifications}
\resumeSubHeadingList
    \resumeSubheading
        {Cisco Academy:}{}
        {Networking Technician.}{}
    \resumeSubheading
        {IFRS:}{}
        {Web Programming, Programming Logic, English, Data Structures.}{}
    \resumeSubheading
        {Udemy:}{}
        {Zabbix and Grafana, IT Infrastructure Management, ITIL 4 Foundation.}{}
\resumeSubHeadingListEnd

\end{document}
