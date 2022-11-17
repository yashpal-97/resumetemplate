# resumetemplate
visit the overleaf website paste this code and compile it. Then edit according to your information.






%-------------------------
% Resume in Latex
% Author : Jake Gutierrez
% Based off of: https://github.com/sb2nov/resume
% License : MIT
%------------------------

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
\usepackage{fontawesome5}
\usepackage{multicol}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}


%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\classesList}[4]{
    \item\small{
        {#1 #2 #3 #4 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------
% \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
%   \textbf{\href{http://sourabhbajaj.com/}{\Large Sourabh Bajaj}} & Email : \href{mailto:sourabh@sourabhbajaj.com}{sourabh@sourabhbajaj.com}\\
%   \href{http://sourabhbajaj.com/}{http://www.sourabhbajaj.com} & Mobile : +1-123-456-7890 \\
% \end{tabular*}

\begin{center}
    {\Huge \scshape Akshat Kumar Verma} \\ \vspace{1pt}
    \vspace{1pt}
    \small \raisebox{-0.1\height}\faPhone\ +91-9981876201 ~ \href{mailto:akshatvermajbp@gmail.com}{\raisebox{-0.2\height}\faEnvelope\  \underline{akshatvermajbp@gmail.com}} ~ 
    \href{https://www.linkedin.com/in/akshatkumarverma/}{\raisebox{-0.2\height}\faLinkedin\ \underline{akshatkumarverma}}  ~
    \href{https://github.com/akshatkverma}{\raisebox{-0.2\height}\faGithub\ \underline{akshatkverma}}
    \vspace{-8pt}  
    
\end{center}


%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {National Institute of Technology, Agartala}{2020 -- 2024}
      {Bachelor of Technology in Electronics and Communication}{\textbf{CGPA: 8.90}}
      \resumeSubheading
      {Little Kingdom Sr. Sec. School, Jabalpur}{2019 -- 2020}
      {Senior Secondary (XII)}{\textbf{Percentage: 93.4}}
      \resumeSubheading
      {Little Kingdom Sr. Sec. School, Jabalpur}{2017 -- 2018}
      {Secondary (X)}{\textbf{Percentage: 89.2}}

  \resumeSubHeadingListEnd

%------RELEVANT COURSEWORK-------
%\section{Relevant Coursework}
    %\resumeSubHeadingListStart
       
    %\resumeSubHeadingListEnd


% -----------EXPERIENCE-----------
\section{Experience}
  \resumeSubHeadingListStart
  
    \resumeSubheading
      {Contact}{November 2021 -- February 2022}
      {Android Developer Intern}{}
      \resumeItemListStart
        \resumeItem{Developed Android Native application for tracking Covid-19 Cases which interfaces with RFID card reader using USB to get and process information, which would be uploaded to database.}
        \resumeItem{Worked on \textbf{MVVM architecture} and \textbf{developed several APIs} for sending and receiving data.}
        \resumeItem{Tools and Technologies used: \textbf{Kotlin, Java, Node.js, SQLite, Firebase.}}
    \resumeItemListEnd
    
  \resumeSubHeadingListEnd
\vspace{-16pt}

%-----------PROJECTS-----------
\section{Projects}
    \vspace{-5pt}
    \resumeSubHeadingListStart
      \resumeProjectHeading
          {\textbf{\href{https://github.com/akshatkverma/AadhaarAddressUpdation}{\color{blue}Aadhaar Address Updation}}} {}
          \resumeItemListStart
            \resumeItem{This was made as a solution for UIDAI Hackathon 2021, it provides the user the feature for updating their address using their landlords address through the app.}
            \resumeItem{Uses official UIDAI provided API’s for user authentication and e-KYC download.}
            \resumeItem{Tools and Technologies: \textbf{Kotlin, Java, SQLite, Firebase.}}
          \resumeItemListEnd
    %       \vspace{-13pt}
    %   \resumeProjectHeading
    %       {\textbf{\href{https://tanya-rajhans-chatsapp.herokuapp.com}{\color{blue}ChatsApp}}} {}
    %       \resumeItemListStart
    %         \resumeItem{Built a real-time chat application where users can create rooms and chat among themselves.}
    %         \resumeItem{\textbf{Tools and Technologies}: HTML, CSS, JavaScript, Node.js, Express.js and Socket.IO.}
    %       \resumeItemListEnd 
         \vspace{-13pt}
         \resumeProjectHeading
          {\textbf{\href{https://github.com/akshatkverma/github-browser}{\color{blue}Github Browser}}} {}
          \resumeItemListStart
            \resumeItem{Built an Android app for tracking user's favorite repositories and checking their branches, open issues and commits.}
            \resumeItem{Tools and Technologies: 
            \textbf{Kotlin, SQLite, GitHub API's.}}
          \resumeItemListEnd 
       %   \resumeProjectHeading
        %  {\textbf{\href{https://github.com/tanyarajhans/heart\_disease\_predictor}{\color{blue}Heart Disease Predictor}}} {}
        %  \resumeItemListStart
        %    \resumeItem{Built a model to predict the probability of heart disease occurrence to a person based on information like age, sex, chest pain type etc.}
         %   \resumeItem{\textbf{Tools and Technologies}: Python3, pandas, NumPy, Matplotlib/Seaborn and Scikit-Learn.}
        %  \resumeItemListEnd 
    \resumeSubHeadingListEnd
\vspace{-15pt}

\section{Achievements}
\resumeItemListStart
\resumeItem {\textbf{Codeforces:} \textbf{Specialist (1522)} rated and solved \textbf{350+} problems.
     \href{https://codeforces.com/profile/akshatverma}
     {\textbf{Profile}: \color{blue}akshatverma}}
     
    % \resumeItem {\textbf{LeetCode:} Solved \textbf{500+} problems. 
    %  \href{https://leetcode.com/tanyarajhans7/}
    % {\textbf{Profile}: \color{blue}leetcode.com/tanyarajhans7}}
    
    \resumeItem {\textbf{CodeChef:} \textbf{4 star (1836)} rated and solved \textbf{200+} problems.
     \href{https://www.codechef.com/users/akshatverma}
    {\textbf{Profile}: \color{blue} akshatverma}}
    
    \resumeItem {\textbf{LeetCode:} \textbf{Top 16.14 \%}. Solved}\textbf{350+} questions. 
     \href{https://leetcode.com/akshatverma}
    {\textbf{Profile}: \color{blue} akshatverma}
     
    % \resumeItem {Secured rank \textbf{766} out of \textbf{5000+} candidates in Google Kickstart Round H 2021.}
    
    
    % \item Inhttps://www.hackerrank.com/akshatvermajbpd to \textbf{Twitter DevelopHer 2021} as \textbf{one of the 30} attendees all over India among second and third year female undergraduates, for excellence in the field of Computer Science.
    
    %  \item Invited to \textbf{Publicis Sapient Jumpstart 2021} - an exclusive event with sessions on technologies like AR/VR, Machine Learning etc. and mentorship by industry experts who are transforming businesses and creating an impact.
    
   % \item Secured \textbf{987} rank out of \textbf{14000} people in November Long Challenge on CodeChef.
 \item Secured \textbf{Global Rank 35} in AlgoManiac held on CodeChef.
 
 \resumeItem {Ranked among the top \textbf{70} out of \textbf{7271} teams in \textbf{HackOn with Amazon 2022.}}
    
    % \item Secured \textbf{Global Rank 554 among 15000+ participants} in CodeChef Div 3 April Long Challenge.
    % \item Published a  \href{https://leetcode.com/discuss/interview-question/1098081/Famous-Backtracking-Problems}{\color{blue}blog at LeetCode}  which gained over  \textbf{10K views and 160+ upvotes}.
    \item \textbf{Finalists} in UIDAI Hackathon 2021 among \textbf{3000+ teams.}
    
  \item Ranked among \textbf{top 2.5 percentile} students in \textbf{JEE Main 2020}, among \textbf{1.4 million students}.
  
  
\resumeItemListEnd
 \vspace{-13pt}
%
%-----------PROGRAMMING SKILLS-----------
\section{Technical Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Languages}{: C++, C, Kotlin, JavaScript} \\
     \textbf{Technologies}{: HTML, XML, Node.js} \\
     \textbf{Computer Fundamentals}{:  Object-Oriented Programming, Operating Systems, Database Management Systems.} \\
     \textbf{Other Tools}{: Git, Github, Android Studio, VS Code, MATLAB, Adobe Softwares.}
    }}
 \end{itemize}
 \vspace{-16pt}


%-----------INVOLVEMENT---------------
\section{Positions of Responsibility}
            \resumeItemListStart
            \resumeItem{\textbf{Lead, Google Developer Student Club (G-DSC), NIT-A}: Conducted and organized various sessions talking about development resources \& opportunities.}
            
            \resumeItem{\textbf{Android Study Jams Facilitator}: Mentored and Trained 100+ students to kick-start their Android Development journey by providing resources and teaching.}
            
            \resumeItem{\textbf{Core Member, Developers and Coders Club, NIT-A}: Trained juniors into building an active coding culture, clearing doubts and providing resources to excel in Data Structures and Algorithms.}
            
            \resumeItemListEnd
        
\end{document}
