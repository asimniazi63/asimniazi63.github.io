%# asimniazi63.github.io

%-------------------------
% Resume in Latex
% Author : Sourabh Bajaj
% Website: https://github.com/sb2nov/resume
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
\usepackage[pdftex]{hyperref}
\usepackage{fancyhdr}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.375in}
\addtolength{\evensidemargin}{-0.375in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

%-------------------------
% Custom commands
\newcommand{\resumeItem}[2]{
  \item\small{
    \textbf{#1}{: #2 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-1pt}\item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-5pt}
}

\newcommand{\resumeSubItem}[2]{\resumeItem{#1}{#2}\vspace{-4pt}}

\renewcommand{\labelitemii}{$\circ$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  CV STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING-----------------
\begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
  \textbf{{\Large Asim Hameed Khan}} & Email : {asimhameed.cs@gmail.com}\\
   Mobile : +923026756763 & {github.com/asimniazi63} \\ & linkedin.com/in/asimniazi63
\end{tabular*}
%----------Summary-------------------
\section{Summary}
\item{}{Masters Student and former research assistant experienced looking forward for a career in software industry for solving real world problems with background in machine/deep learning with focus in computer vision.}
\item{}{Proficient in Python, C++, OpenCV, Scikit, TensorFlow/Keras, PyTorch as well as some hands-on knowledge in android, web and gaming applications.}

%-----------EDUCATION-----------------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {National University of Science and Technology, Islamabad}{Islamabad, Pakistan}
      {Master of Science in Computer Science;  Research in Progress}{2019 -- Present}
    \resumeSubheading
      {Namal Institute, Mianwali (Associated with University of Bradford, UK)}{Mianwali Pakistan}
      {Bachelor of Science with Honours in Computer Science; }{2014 -- 2018}
  \resumeSubHeadingListEnd


%-----------EXPERIENCE-----------------
\section{Experience}
  \resumeSubHeadingListStart

    \item
      \textbf{Research Assistant} at \textit{Namal Institute, Mianwali}
      \hfill{Oct 2018 - Aug 2019} \linebreak
      {Diagnosing diseases in plant using machine learning algorithms. Assisted in writing research proposals and literature review of machine learning algorithms for diseases diagnosis in Olive plants. Also designed Android app for fetching diagnosis results from machine learning algorithm deployed on server.}

  \resumeSubHeadingListEnd

\section{Awards and Honors}
 \resumeSubHeadingListStart
 \item{ Graduate Assistantship for Master at GIKI }
 \item{ Award of Dean's Honors from University of Bradford, UK (2019)}
 \item{ Secured First Runner Up position in National Electronic Olympiad GIKI '17}
 \item{Secured First position at Coding Competition Namal IEEE Chapter 2017}
 
 \resumeSubHeadingListEnd

%-----------PROJECTS-----------------
\section{Projects}
  \resumeSubHeadingListStart
  %\item{\textbf{}}
  %---------Masters projects--------
  
  \item{\textbf{Object Detection on Satellite Images}}
  {Satellite Imagery dataset contain data of 15 different vehicles. We trained state of art object detection models like YOLOv3, Faster RCNN and RetinaNet for the task of object detection. We improved these accuracies further by embedding different state of art building blocks.Keras, PyTorch, OpenCV and other libraries were used for image operations and data visualizations.}
  
  \item{\textbf{Semantic Segmentation for Histopathology (Medical Imaging) using Deep Learning}}
  {Used standard UNet, SegNet and DeepLabv3 as baseline models and improved accuracy of baseline using state of art building blocks. Keras, OpenCV and other libraries were used for image operations and data visualizations.}
  
  \item{\textbf{Nuclei Segmentation of Cancerous Images (Medical Imaging)}}
  {The objective of this method was to perform Nuclei Segmentation as the shape, structure and appearance of Nuclei is one of the bio-markers for prognosis. These bio-markers are later used for prognosis therefore accurate and timely segmentation of nuclei are needed. For this purpose we used multiple models (on multiple datasets) namely: SegNet, DeepLabv3+, Vanilla U-Net and Modified U-Net.}
  
  \item{\textbf{Pokemon(1) and Faces (2) Classification}}
  {Dataset of Pokemons were collected using Bing Search Engine API and opencv was used for basic operation while FeedForward and Convolutional neural networks were trained for the task of classification in PyTorch Framework.}
  
  \item{\textbf{Classification and generation  of People Names from countries/regions}}
  {A names classification and generation pipeline was developed in Pytorch that can classifies names as well as learns to genrate names from that origin.}
  
  
  \item{\textbf{Human Pedestrian/Object Detection}}
  {Computed HoG features for INRA dataset using OpenCV library and trained SVM and Random Forest classifier (using sklearn) for classification tasks. Keras,OpenCV and other libraries were used for image operations and data visualizations.}
  
  \item{\textbf{Natural Disaster Classification}}
  Classification of natural disaster like EarthQuake, Flood, Fire and Cyclone using Machine Learning (Convolutional Neural Networks).
  
  \item{\textbf{ResNet and Inception-ResNet for CNN architecture for Image Classification}}
  {Implemented cnn architectures using deep learning's modular design. Used opencv for image operations. Other data visulization libraries i.e. pandas and matplotlib for data visualizations. }
  
  \item{\textbf{Object Tracking}}
  Implemented single and multiple object tracking algorithms in OpenCV.
  \item{\textbf{Image Feature Detection and Matching}}
  {Extracted features using algorithms in OpenCV to and matched set of images using top features.}
  %----------Bachelors projects------
    \item{\textbf{Training First person shooting bots with Machine learning}
    }
    {In the research work, we applied reinforcement learning (a type of machine learning) to first person shooter bots to learn the diverse behavior without hard coding the AI. This project applies Proximal Policy Optimization algorithm with neural networks using TensorFlow and Unity Machine learning agents Framework.}
    \item{\textbf{Snails Game}}
      {Developed Snails game AI using MinMax algorithm in MATLAB.}
    \item{\textbf{Tanks Game}}
      {Implemented tanks game AI using genetic algorithm and neural networks in MATLAB.}
    \item{\textbf{Fight For Land - A Real Time Strategy Game}}
    {A real time strategy game based on the history of sub-continent game implemented in Unity3D with both Single and Multiplayer.}
    \item{\textbf{Sensor Based Music Player-Android}}
      {Android Music player which lets user control music using accelerometer and light sensor.}
    \item{\textbf{Personal Academic Tutor}}
      {A management system to assign a personal academic adviser to each student of Namal College, Mianwali.}
    \item{\textbf{Trash Can Monitoring System}}
      {A IOT based system that notifies user on Android App when Trash Can of a specified area are filled.}
  \resumeSubHeadingListEnd

%
%--------PROGRAMMING SKILLS------------
\section{Programming Skills}
 \resumeSubHeadingListStart
 \item{\textbf{Top Languages: }}{Python, Java, C++}
 
    \item{\textbf{Others}}{C, C# , JavaScript, HTML, Haskell, Prolog}
    
    \item{\textbf{Frameworks,Libraries and Tools:  }}{ OpenCV, Keras, TensorFlow, PyTorch, MATLAB, Scikit-Image, Scikit-Learn, Pyplot, MatplotLib, NumPy, Pandas, AWS, MS Azure, GCP, Google Colab, Github}
    
    \item{\textbf{Databases: }}{MySQL, SQLite, MongoDB, Firebase}
    \item{\textbf{Operating Systems: }}{Linux (Ubuntu, Kali, Mint), Windows(7/8/10)}
 \resumeSubHeadingListEnd
 
%  \section{Awards and Honors}
%  \resumeSubHeadingListStart
%  \item{ Graduate Assistantship for Master at GIKI }
%  \item{ Award of Dean's Honors from University of Bradford, UK (2019)}
%  \item{ Secured First Runner Up position in National Electronic Olympiad GIKI '17}
%  \item{Secured First position at Coding Competition Namal IEEE Chapter 2017}
 
%  \resumeSubHeadingListEnd
 
\section{References}
\item{\textbf{Dr. Muhammad Moazam Fraz} (Assistant Professor) \hfill  moazam.fraz@seecs.edu.pk}

\item{\textbf{Dr. Junaid Akhtar} (Assistant Professor) \hfill  juniad.akhtar@namal.edu.pk}

\item{\textbf{Dr. Malik Jahan Khan} (Associate Professor) \hfill  malik.jahan@namal.edu.pk}

%-------------------------------------------
\end{document}
