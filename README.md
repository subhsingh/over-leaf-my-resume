# over-leaf-my-resume
\documentclass[10pt]{extarticle}

\usepackage[margin=0.2in]{geometry}
\usepackage{romannum}
\usepackage[most]{tcolorbox}
\usepackage{enumitem}
\usepackage{multicol}
\usepackage{xcolor}
\usepackage{multirow}
\usepackage{hyperref}
\usepackage{tabularx}
\usepackage{fontawesome}
\usepackage{enumitem}
\usepackage{wasysym}
\usepackage{tfrupee}
\newlist{tabitemize}{itemize}{1}
\setlist[tabitemize]{nosep,
                  topsep= 0pt,
                  partopsep=0pt,
                  leftmargin= *,
                  label=\textbullet,
                  before=\vspace{0.3\baselineskip},
                  after=\vspace{-\baselineskip}
                  }
\renewcommand\tabularxcolumn[1]{m{#1}}
\newcolumntype{M}[1]{>{\centering\arraybackslash}m{#1}}
\setlist[itemize]{noitemsep, topsep=0pt}
\addtolength{\parskip}{-1.5mm}
\tcbset{
    frame code={}
    center title,
    left=0pt,
    right=0pt,
    top=0pt,
    bottom=0pt,
    colback=gray!50,
    colframe=white,
    width=\dimexpr\textwidth\relax,
    enlarge left by=0mm,
    boxsep=3pt,
    arc=0pt,outer arc=0pt,
    }
    \usepackage[default]{lato}
\usepackage[T1]{fontenc}
\begin{document}
\fontsize{9.5pt}{10.5pt}\selectfont{
\begin{flushleft}
\noindent {\huge\textbf{Subham Singh}}

%\hfill \textbf{ dipakm@iitk.ac.in | +91-7982498759}
\end{flushleft}
Research cum project Associate \hfill \faEnvelope\
\href{mailto:subhamsingh129@gmail.com}{Subham Singh} $|$ \faPhone\ +91-7001358094
\\\textbf{Major}: Electronics and Communication Engg \hfill    \faGithub\  
 \href{https://github.com/subhsingh}{SubhamSingh}
$|$ \faLinkedin\  \href{https://www.linkedin.com/in/singhsubh/}{Subham Singh}\ \ \ \ \ 

\vspace{-3pt}

\noindent\rule[0.5ex]{\linewidth}{1pt}
{\large \textbf{\begin{tcolorbox}[center, width=20.7cm]\textsc{Academic Qualifications}\end{tcolorbox}}}
%\vspace{-2pt}
\begin{center}
\begin{tabular}{|p{2.5cm}|p{6.0cm}|p{7.5cm}|p{2.8cm}|}
\hline
\centering{\textbf{Year}} & \centering{\textbf{Degree/Certificate}} & \centering{\textbf{Institute}} & \centering \textbf{Performance} \tabularnewline
\hline
\centering{2019} - 2023 & \centering{Bachelor of Technology} & \centering{Chandigarh Engineering College Mohali} & \centering 7.70/10 \tabularnewline \hline 
\centering{2018} & \centering{Class \Romannum{12} (CBSE)} & \centering{DAV Public School, Asansol} & \centering 68.8$\%$ \tabularnewline
\hline
\centering{2016} & \centering{Class \Romannum{10} (CBSE)} & \centering{DAV Public School, Asansol} & \centering 9.4/10 \tabularnewline
\hline
\end{tabular}
\end{center}
\smallskip{}
{\large \textbf{\begin{tcolorbox}[center, width=20.7cm]\textsc{Professional Experience}\end{tcolorbox}}}
\vspace{-1pt}
 %\vspace{-5pt}
{\large \textbf{\begin{tcolorbox}[center, width=20.7cm, colback=black!10]\textsc{IIT KANPUR | Research cum project Associate} \textcolor{black!70}{}\end{tcolorbox}}}
\begin{tcolorbox}[center, width=20.7cm, colback=black!10]
\textbf{Embedded System, Signal Analyses, TCP/IP, Communication Protocols } %\textcolor{black!70}{[PPO Results Awaited]}
\hfill\hfill\textcolor{black!70}{\small \textit{July'24-Sep'24}}
\end{tcolorbox}
\vspace{-1pt}
\begin{center}
\begin{tabularx}{\textwidth}{ p{1.6cm} | X }
\centering\multirow{1}{*}{\textbf{Objective}} & 
\begin{tabitemize}
    \item Developing \textbf{signal analysis systems} with \textbf{microcontrollers} and automating street lights for smart city projects  

\end{tabitemize}\\
\hline
\centering\multirow{1}{*}{\textbf{Approach}} & 
\begin{tabitemize}
    \item Developed \textbf{Python} algorithms for \textbf{DTFT, FFT, DTDFT} for noise cancellation and analysis of voltage, current signals.
    \item Designed circuits using \textbf{ESP32} and \textbf{6LoWPAN} to automate error detection in solar-powered smart street lights.
    \item Worked with \textbf{I2C, SPI, UART, CAN, RS485, and RS232} protocols for serial communication in embedded systems.
\end{tabitemize}\\
\hline
\centering\multirow{1}{*}{\textbf{Impact}}& 
\begin{tabitemize}
    \item Enhanced signal \textbf{clarity} and \textbf{accuracy}, leading to improved performance in voltage and current signal \textbf{analysis}. 
    %\item Developed the \textbf{biggest} model by Citibank Internal Audit Innovations team with \textbf{104} mappings
    \item Enhanced smart street light reliability in \textbf{Ayodhya Smart City} by automating error detection with \textbf{ESP32} and \textbf{6LoWPAN}. 
\end{tabitemize}\\
\end{tabularx}
\end{center}
{\large \textbf{\begin{tcolorbox}[center, width=20.7cm, colback=black!10]\textsc{PG TECH Pvt Ltd Mohali | Trainee} \textcolor{black!70}{}\end{tcolorbox}}}
\begin{tcolorbox}[center, width=20.7cm, colback=black!10]
\textbf{Python, AIML Python libraries and Model training } %\textcolor{black!70}{[PPO Results Awaited]}
\hfill\hfill\textcolor{black!70}{\small \textit{Jan'23-May'23}}
\end{tcolorbox}
\vspace{-1pt}
\begin{center}
\begin{tabularx}{\textwidth}{ p{1.6cm} | X }
\centering\multirow{1}{*}{\textbf{Objective}} & 
\begin{tabitemize}
    \item Developed a \textbf{virtual mouse} application using \textbf{Python and advanced libraries} to enable gesture-based computer control. 

\end{tabitemize}\\
\hline
\centering\multirow{1}{*}{\textbf{Approach}} & 
\begin{tabitemize}
    \item Improved \textbf{efficiency} and \textbf{convenience} in controlling devices, offering a novel interaction method in tech applications.
    \item Implemented \textbf{data cleaning and abstraction techniques} to filter out noise, improving gesture detection reliability.
    \item Utilized \textbf{sampling and scripting methods} to optimize \textbf{real-time performance} for seamless gesture-to-command translation.
\end{tabitemize}\\
\hline
\centering\multirow{1}{*}{\textbf{Impact}}& 
\begin{tabitemize}
    \item Enhanced \textbf{signal clarity and accuracy}, leading to improved performance in voltage and current signal analysis. 
    %\item Developed the \textbf{biggest} model by Citibank Internal Audit Innovations team with \textbf{104} mappings
    \item Enhanced \textbf{user accessibility} by providing a hands-free control option, beneficial for individuals with physical disabilities. 
\end{tabitemize}\\
\end{tabularx}
\end{center}

\vspace{-5pt}


%\vspace{1pt}
\smallskip{}
{\large \textbf{\begin{tcolorbox}[center, width=20.7cm]\textsc{Key Projects}\end{tcolorbox}}}
\vspace{-6pt}

\vspace{-4pt}

\vspace{2pt}
\begin{tcolorbox}[center, width=20.7cm, colback=black!10]
\textbf{Agricultural Drone Project $|$  National level award $|$ Prize of 10k Won } \hfill\hfill\textcolor{black!70}{\small \textit{Jun’23 - July’23}}
\end{tcolorbox}
\vspace{-6pt}
\begin{itemize}
\item \textbf{Utilized a K3 A PRO flight controller} with GPS, IMU, and telemetry for precise navigation, dynamic stability, and real-time positioning.
\item Equipped with a \textbf{25-liter tank} and \textbf{high-efficiency, precision-engineered} solenoid valves for accurate fertilizer and pesticide application.
\item Implemented long-range \textbf{RF modules, altimeters, and optical flow sensors} for reliable data transmission and altitude control.
\end{itemize}

\vspace{1.5mm}
\begin{tcolorbox}[center, width=20.7cm, colback=black!10]
\textbf{Wearable Personal Safety Device $|$ Patented Project $|$ TEAM PROJECT } \hfill\hfill\textcolor{black!70}{\small \textit{July'20 - April'23}}
\end{tcolorbox}
\vspace{-6pt}
\begin{itemize}
\item Developed and \textbf{patented} a wearable safety device integrating \textbf{GSM module, voice, and gyroscopic sensors} for real-time monitoring.
\item Utilized \textbf{STM32 microcontroller} for \textbf{processing sensor data}, enabling precise \textbf{voice recognition and motion detection} capabilities.
\item Achieved patent registration \textbf{(C.B.R No. 36467)} for innovative safety technology, \textbf{enhancing personal security} through \textbf{advanced sensor integration}.
\end{itemize}
\vspace{2mm}
\begin{tcolorbox}[center, width=20.7cm, colback=black!10]
\textbf{Library Management System using SQL $|$ \faGithub\ \href{https://github.com/subhsingh/library-management-system}{Project reference} } \hfill\hfill\textcolor{black!70}{\small \textit{Oct’22 - Nov’22}}
\end{tcolorbox}
\vspace{-6pt}
\begin{itemize}
\item Designed and implemented a \textbf{relational database schema in SQL} for efficient management of books, members, and transactions.
\item Optimized SQL \textbf{queries} to swiftly retrieve data on book availability, member information, and transaction history.
\item Enhanced \textbf{library system performance} through effective indexing and query optimization techniques, improving \textbf{data access speed}.
\end{itemize}




%\vspace{-6pt}
{\large \textbf{\begin{tcolorbox}\textsc{Technical Skills }\end{tcolorbox}}}
\vspace{-2.5mm}
\begin{itemize}
\item \textbf{Programming:} C, C++, Python, HTML, SQL
\item \textbf{Tools and Libraries:} Google patents, Espanet, MS-Excel,MS-Power BI,GIT,Prior art Search, SEP,,Pandas,Numpy,,Claims, Patent analysis.
\item \textbf{Hand-On:} Wireless/Serial Communication,Iot devices, Microntrollers Arduino, Rasberry pie, Oops-concept, Computer Networks, Linux, DBMS, 2G/3G/4G/5G, sensors.
\end{itemize}














\end{document}
