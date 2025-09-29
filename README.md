PROGRAM 1(BASIS OF FORMATING TEXT AND PARAGRAPH)

\documentclass{article}
\begin{document}
\title{\textbf{Machine Learning}}
\author{\textit{student}}
\date{June 2025}
\maketitle
\section{\Huge{What is Machine Learning?}}
\normalsize {Machine Learning (ML) is a type of Artificial Intelligence (AI) that allows computer to learn without being explicitly programmed. It involves feeding data into algorithm that can then if identify patterns and make predictions on new data Machine Learning is used in variety of applications, including image and speech recognition.}
\subsection{Classification of Machine Learning}
{Machine learning implementations are classified into four major categories,depending on the learning "signal" or "response" available to a learning system which are as follows;}
\subsubsection{\textbf{Supervised Learning:}}
It a machine learning task of learning a function that maps an input to an output based on example pairs.
\small{Example: Consider the following data regarding patients entering a clinic. The data consist if the gender and age if the patients and each patient is labeled as "healthy" or "sick".}
\footnotesize{Example: Consider the following data regarding patients entering a clinic.}
\subsubsection{\textbf{Unsupervised learning:}}
\large{Unsupervised learning is a type of machine learning algorithm used to draw inferences from data sets consisting of input data without labeled responses. In unsupervised learning algorithms, classification or categorization is not included in the observations.}
\end{document}


PROGRAM 2(MARGIN,ORIENTATION AND TWO COLUMN)

\documentclass[two column]{article}
\usepackage[landscape,a4paper]{geometry}
\geometry{margin=2cm}
\begin{document}
\title{\textbf{Page dimension, Margin, two-column}}
\author{Student}
\maketitle
\begin{large}
    \section{Introduction}
    \textit{LaTeX is a highly quality typesetting system; it includes features designed for the production of technical and scientific documentation. LaTeX is the standard for the communication and publication and publication of scientific documentations.}\\
    \subsection{Definition}
    \textbf{LaTeX} is a programming language similar to C. In particular, LaTeX code must be complied to produce a document. This is often done using pdf latex, a program which produces a PDF file from a LaTeX document.
        LaTeX is widely used in acadmia for the communication and publication of scientific documents and technical note-taking in many fields, owing particularly to its support for complex mathematical notation, etc.
        \subsection{Typesetting}
        LaTeX attempts to follow the design philosophy of separation of presentation from content, so that authors can focus on the content of what they are writing without attending simultaneously to its visual appearance..
        \subsection{Document}
        To create a document in LaTeX, a user first creates a file, such as document. Tex, typically using a text editor. The user then gives their document. Tex file as input to the Tex program, which prompts Tex to write out a file suitable for onscreen viewing or printing..
\end{large}
\end{document}


PROGRAM 3(HEADER AND FOOTERS)

\documentclass{article}
\usepackage{setspace}
\usepackage[utf8]{inputenc}
\usepackage{fancyhdr}
\usepackage{tocloft}
\pagestyle{fancy}
\fancyhf{}
\fancyhead[L]{\textbf{Python Programming}}
\fancyhead[R]{\textit{student}}
\fancyfoot[L]{^1 Features}
\fancyfoot[C]{\thepage}
\renewcommand{\cftsecleader}{\cftdotfill{\cftdotsep}}
\begin{document}
\onehalfspacing
\title{\textbf{Python programming}}
\author{\textit{student}}
\date{July 7 2025}
\maketitle
\newpage
\tableofcontents
\newpage
\textbf{\Large Chapter 1}
\maketitle
\section{\textbf{\LARGE Python Programming}}
In this chapter we will study the data types, features, operators of python programming.
\subsection{Introduction}
Python is a widely used programming language that offers several unique features and advantages compared to language like Java and C++. In the late 1980's, Guido van Rossum dreamed of developing Python.

\subsubsection{Data types}
\textbf{Numeric datatype:} In Python, numeric data type is used to hold numeric values. Integers, floating-point numbers and complex numbers fall under Python numbers category. They are defined ad int, float, complex. It used to holds signed integers of non-limited length. 
Float used to holds floating decimal points and it's accurate up to 15 decimal place. Complex used to holds complex numbers.\\
\quad\textbf{Sequence datatype:} List is an ordered collection of similar or different types of items separated by commas and enclosed within brackets. Tuple is an ordered sequence of items same as a list. The only difference is that tuples are immutable. Tuples once created cannot be modified. In Python, we use the parentheses.

\subsubsection{Features of python programming}
\textbf{Easy to use and read:} Python's syntax is clear and easy to read, making it an ideal language for both beginners and experienced programmers. This simplicity can lead to faster development and reduce the changes of errors.\\

\quad\textbf{Cross platform compatibility:} Python can be easily installed on Window, macOS, and various Linux distributions, allowing developers to create software that runs across different operation systems.\\

\quad\textbf{Free and open source:} Python language is freely available at the official website and you can download it from the given download link below click on the Download Python keyword. Download Python since it is open-source, this means that source code it also available to the public. So you can download it, use it as well as share it.\\

\quad\textbf{Portable language:} Python language is also a portable language. For example, if we have Python code for Windows and if we want to run this code on other platforms such as Linux, Unix, and Mac then we do not need to change it, we can run this code on any platform.

\subsubsection{Operators}
The operator is a symbol that performs a specific operation between two operands, according to one definition. Operations serve as the foundation upon which logic is constructed in a program in a particular programming language. In every programming language, some operators performs several tasks. Same as other languages. Python also has some operators.\\

\textbf{Arithmetic Operator}\\
Arithmetic operators used between two operands for a particular operation. There are many arithmetic operators. It includes the exponent (**) operator as well as the + (addition), - (subtraction), * (multiplication), / (division), \%(reminder), and // (floor division) operations.\\

\textbf{Comparison Operator}\\
Comparison operators mainly use for comparison purposes. Comparison operators compare the value of the two operands and return a true or false Boolean value in accordance. The example of comparison operators are ==, !=, . In the below table, we explain the word of the operators.\\

\textbf{Assignment operator}
Using the assignment operators, the right expression's value is assigned to the left operand. There are some example of assignment operators like =, +=, -=, *=, =, **=, //=. In the below table, we explain the works of the operators.\\

\textbf{Bitwise Operator}
The two operands' Values are processed bit by the bitwise operators. The examples of Bitwise operators are bitwise OR (-), bitwise AND (\&), bitwise XOR, negation, Left shift, and Right shift.\\

\textbf{Logical Operator}
The assessment of expressions to make decision typically uses logical operators. The examples of logical operators are and, or, and not. In the case of logical AND, if the first one is 0, it does not depend upon the second one. In the case of logical OR, if the first one is 1, it does not depend on the second one. Python supports the following logical operations. In the below table, we explain the works of the logical operators.

\end{document}


PROGRAM 4(BULLETED LIST)

\documentclass{article}
\usepackage{amsthm}
\begin{document}
\title{\textbf{Displaying list}}
\author{author}
\date{september 30, 2025}
\maketitle
\section{\textbf{Introduction}}
In this section we are discussing about various types list like numbered list, bulleted list and definition list.
\begin{enumerate}
    \item Python program contains many data types. It includes
    \begin{itemize}
        \item int
        \item float
        \item character
        \item string
        \item boolean
    \end{itemize}
    \item The various types of operator in python programming are:
    \begin{itemize}
        \item Arithmetic
        \item Relational 
        \item Logical
    \end{itemize}
\end{enumerate}
\begin{description}
    \item[Definition 1] Python was developed by Van Rossum in 1991
    \item[Definition 2] Python was developed in advance with c.
\end{description}
\end{document}


PROGRAM 5 (INCLUDE IMAGE)

\documentclass{article}
\usepackage{graphicx}
\title{Image}
\author{Student}
\date{July 2025}
\begin{document}
\maketitle
\section{Introduction}
In this section we are discussing about how to insert a image in LaTeX document.
\subsection{Package}
LaTex cannot manage image by itself. So we need to use the graphicx package. To use it, we include the following  line in the preambe: use package {graphicx}.\\
The command graphicx path |image| tells LaTeX that the image are kept in a folder named images under the directory of the main document.\\
The include graphics {universe} command is the one that actually included the name of the file containing the image without the extension, then universe. PNG becomes universe. The title name of the image should not contain white spaces not multiple dots.\\
It also provide a way to change the width height \& position of the image.
\begin{figure}
    \centering
    \includegraphics[width=0.5\linewidth]{image}
    \caption{Tex Studio}
    \label{fig:enter-label}
\end{figure}
\end{document}

PROGRAM 6(INCLUDE THE TABLE )

\documentclass{article}
\usepackage{multirow}
\usepackage{caption}
\begin{document}
\title{LaTeX Table}
\author{Student}
\date{July 2025}
\maketitle
\section{Introduction}
This topic will explain the steps to create the table and perform different functions in the table. Tables are an efficient way to represent the information and are often used in most of the documents or files.
\subsection{Create a table}
Creating the table in LaTeX is a little complicated compared to others. But here, the steps and the procedure to create a table from the basics will make the process easier.
\begin{table}[h]
    \centering
    \begin{tabular}{|c|c|c|}
    \hline
       \multicolumn{3}{|c|}{\textbf{Student Data}} \\
       \hline
       \textbf{Roll.No.} & \textbf{Name} & \textbf{Department} \\
       \hline
       24MCA054 & Swetha & MCA \\
       \hline
       24MCA002 & Abarna & MCA\\ 
       \hline
       \multirow{3}{*}{24MCA004} & Anju & MCA \\& Hervin & MCA \\& Vaishu & MCA \\
       \hline
    \end{tabular}
    \caption{Student Information}
\end{table}
\end{document}


PROGRAM7(REFERENCING CHAPTER,SECTION,FOOTNOTES)

\documentclass[12pt, a4paper]{article}
\usepackage{graphicx}
\usepackage{footmisc}
\usepackage{amsmath, amssymb}
\usepackage{caption}
\begin{document}
\title{\textbf{JAVA}}
\author{o'Reilly}
\date{August 18, 2025}
\maketitle
\newpage
\textbf{\Huge Chapter 1}
\section{Introduction}
Our core Java programming tutorial is designed for students and working professionals. Java is an object-oriented, class-based, concurrent, secured and general-purpose computer-programming language. It is widely used robust technology.
\subsection{What is Java}
Java is a programming language and a platform. Java is a high level, robust, object-oriented and secure programming language. Java was developed by sun Microsystem (which is now the subsidairy of Oracle) in the year 1995. James Gosling is known as ther father of Java. Before Java, its name was Oak. Since Oak was already a registered compaby, so James Gosling and his team changed the name from Oak to Java . Platform: Any hardware or software environment in which a runs, is known as a platform. Since Java has a runtime environment (JRE) and API, it is called a platform.
\subsection{Versions}
The versions of Java are listed below:
\begin{table}[h]
    \centering
    \begin{tabular}{|c|c|c|} 
    \hline
      S.No   &  Version & Year \\
      \hline
        1 & JDK alpha and beta & 1995\\
        \hline
        2& JDK1.0 & 1996\\
        \hline
        3 & JDK1.1& 1997\\
        \hline
        4 & J2SE1.2 & 1998\\
        \hline
    \end{tabular}
    \caption{Version of Java}
    \label{tab:placeholder}
\end{table}
\newpage
\subsection{Example}
Let's have a quick look at Java programming example. A detailed description of Hello Java example is availabele in next page.\\

\textbf{Simple.java}\\
class simple{\\
public static void main (String args[])\{\\
System.out.println ("Hello Java");\\
\}\\
\}
\begin{figure} [h]
    \centering
    \includegraphics[width=0.9\linewidth]{image.jpeg}
    \caption{Example}
    \label{fig:placeholder}
\end{figure}
\newpage
\textbf{\Huge Chapter 2}
\section{ First Java Program}
In this section,we will learn how to wite the simple program of Java. We can write a simple hello Java program easily after installing the JDK.To create a simple Java program, you need to create a class that contains the main method.Let's understand the requirement first.
\subsection{The requirement for Java Hello World Example}
For executing any Java program, the following software or application must be properly installed.
\begin{itemize}
    \item Install the JDK if you don't have installed it,download the JDK and install it.
    \item  Set path of the jdk/bin directory. http://www.javatpoint.com/how-to-set-path-in-java
    \item Create the Java program
    \item Compile and run the Java program
\end{itemize}
\subsection{Create Program}
Crating Hello World Example Let's create the hello java program: 1 $1.3$ \footnote{The first example of java program}. Refer the program in page no: 2 Refer the program in figure 1.1 save the above file as Simple.java. To compile: java Simple.java. To execute: java \textbf{Simple Output: Hello Java } The code can be run depends on different versions which are listed in table 1.
\end{document} 

PROGRAM 8(BIBLIOGRAPHICS)

\documentclass[12pt, a4paper]{article}
\usepackage[color links=true,allcolors=blue]{hyperref}
\title{\textbf{Bibliography}}
\author{\textit{Student}}
\date{30 september 2025}
\begin{document}
\maketitle
\section{Introduction}
In this section we are discussing about bibliography.
\section{Review literature}
Social media is a revolutionary concept with a totality brilliant possibility with extra scope for advancements.\cite{ref1} Social media has been a crucial part of one's existence from purchasing to digital. mail, education, and commercial enterprise tools. It allows not unusual place hobby primarily based totally groups inclusive of college students to paintings in a collaborative organization project out of doors in their class. \cite{ref2} \\ 
\quad Social media isn't confined simplest to specialists or elders however it's far been broadly utilized in instructional sectors via way of means of students.Students typically use social web sites for lots of motives including for take a look at functions, for amusement functions as social media gives any information you need to shortlessly and speedy inside a fragment of a second.\cite{ref3}
\begin{thebibliography} {99}
\bibitem{ref1}
Shabnoor Siddiqui, Tajinder Singh, Social Media its Impact with Positive and Negative Aspects", Volume-5,2016.
\bibitem{ref2}
Anuradha A. Ename, Vijay M. Rakhade, Loelesh N. yadav, "A Study on Positive and Negative Effects of Social Media. on Society", Volume-3,2022.
\bibitem{ref3}
Jyothi Suraj Harchekar, "Impact of Social Media on Society", Volume-6,2017.
\end{thebibliography}
\end{document}


PROGRAM9(JOURNAL ARTICLE)
 
\documentclass[twocolumn, 12pt]{article}
\usepackage[portrait, a4paper]{geometry}
\usepackage{graphicx}
\usepackage[color links=true,allcolors=blue]{hyperref}
\begin{document}   
\title{\textbf{A Comparative Analysis on OTT platform: ZEE5 Vs Amazon Prime}}
\author{\textit{Dr. L. Thara, S. Vaishnave}}
\date{September 4, 2025}
\maketitle
\begin{abstract}
In the olden days from each family. everyone sit together and watch TV shows. In the today's world when we talk about TV shows, digital media and the availability of the latest movies or series the one word that comes to everyone's mind is OTT. The significant growth of OTT platforms has risen since 2013 and video streaming content will exceed \$332 billion by 2025. The video streaming subscription of around 8 US\$ billion in 2020 was reported by Deloitte. \textbf{Keywords:} OTT, Netflix, Amazon prime, Java, Python, Deep learning.
\end{abstract}
\section{Introduction}
The ott platform is a technology that enables the delivery of streamed content through internet connected devices. This means viewers can watch video contents across multiple devices without needing to be connected to cable or broadcast TV. There are two types of video and audio content played over the internet in an OTT streaming. Pay-to-access and Free-to-access. Subscription video-on-demand services offer access to film and television content, including shows and movies for which OTT acquires right from the content owner.
\subsection{ZEE5}
Netflix is an incredibly popular OTT platform that operates on subscription-based model and is known for its excellent customer engagement services. Refer the logo of Netflix in figure 1. It's media streaming platform that offers a vast collections of award winning shows, documentaries, web series, movies and much more.
\begin{figure} [h!]
    \centering
    \includegraphics[width=0.8\linewidth]{zee5.png}
    \caption{ZEE5 Logo}
    \label{fig:placeholder}
\end{figure}
\subsection{Amazon Prime Video}
Amazon Prime and Netflix are major competitors in the entertainment industry. Amazon Prime offers a vast collection of movies and TV shows that are updated regularly, similar to Netflix. Refer the logo of Amazon in figure 2. In addition to the entertainment package, Amazon Prime also provides unlimited music playlist with millions of songs in different languages, two-day guaranteed delivery, daily offers, and many more benefits to its subscribers.
\begin{figure} [h!]
    \centering
    \includegraphics[width=0.8\linewidth]{amazonprime.jpeg}
    \caption{Amazon Logo}
    \label{fig:placeholder}
\end{figure}
\section{Literature Review}
Numbers Research papers have analyzed video streaming apps, such as Netflix and Amazon Prime video. One such study titled \cite{ref1}, found that viewers prefer to watch offline video because it allows them to enjoy entertainment in areas with poor network connectivity. Another Article \cite{ref2}, revealed that original content is the most important factor for customers when choosing a paid subscription to channels.

\section{Research Methodology}
The researchers conducted exploratory research to obtain vital information about two leading media streaming service provider- Amazon Prime Video and Netflix They used different exploratory research methods including case study analysis and secondary data analysis. Refer the logo of Netflix in 1. Refer the logo of Amazon in 2.
\begin{thebibliography}{99} 
\bibitem{ref1}
Sheet al Pradeep Mehta, "Determining the factors influencing customer engagement while using the subscription-based media streaming services providers: Netflix vs Amazon Prime",2020.
\bibitem{ref2} 
R. Vishnupriya,"Customer perception towards networked streaming services providers with reference to Amazon Prime and and Netflix", 2021.
\end{thebibliography}
\end{document}


PROGRAM10(TEMPLATES FOR BOOK)

\documentclass[12pt,a4paper,openany]{book}
\usepackage{graphicx}
\usepackage{tocloft}
\renewcommand{\cftsecleader}{\cftdotfill{\cftdotsep}}
\usepackage{amsmath}
\usepackage{cite}
\usepackage{fancyhdr}
\pagestyle{fancy}
\fancyhf{}
\fancyhead[R]{OTT Platform}
\begin{document}
\title{\textbf{Comparative Analysis on OTT Platform: ZEE5 Vs Amazon Prime}}
\author{\textit{Dr. L. Thara, S. Vaishnave}}
\date{September 4, 2025}
\maketitle

\tableofcontents

\chapter{OTT Platform}
The OTT platform is technology that enables the delivery of streamed content through internet-connected devices. 
This means viewers can watch video content across multiple devices without needing to be connected to cable or broadcast TV. 
There are two types of video and audio content played over the internet in OTT streaming: Pay-to-access and Free-to-access. 
Subscription video-on-demand services offer access to films and television content, including shows and movies for which OTT acquires rights from the content owner.

\section{Introduction}
An OTT (Over-the-Top) platform is a media service offered directly to viewers via the internet, bypassing traditional cable, satellite or broadcast television providers. 
Popular OTT platforms include Netflix, Amazon Prime Video, Disney+, and Hulu \cite{ref1,ref2}. 
These platforms offer a wide range of content, including movies, TV shows, documentaries, and original programming. 
They can be accessed on various devices such as smart TVs, smartphones, tablets, and computers.

\section{ZEE5}
Netflix is an incredibly popular OTT platform that operates on a subscription-based model and is known for its excellent customer engagement services. 
Refer to the logo of Netflix in Figure~\ref{fig:netflix}. 
It is a media-streaming platform that offers a vast collection of award-winning shows, documentaries, web series, movies, and much more.

\begin{figure}[h!]
    \centering
    \includegraphics[width=0.5\linewidth]{download.png}
    \caption{ZEE5}
    \label{fig:netflix}
\end{figure}

\section{Amazon Prime}
Amazon Prime and Netflix are major competitors in the entertainment industry. 
Amazon Prime offers a vast collection of movies and TV shows that are updated regularly, similar to Netflix. 
Refer to the logo of Amazon in Figure~\ref{fig:amazon}. 
In addition to the entertainment package, Amazon Prime also provides an unlimited music playlist with millions of songs in different languages, two-day guaranteed delivery, daily offers, and many more benefits to its subscribers.

\begin{figure}[h!]
    \centering
    \includegraphics[width=0.5\linewidth]{amazon prime.jpeg}
    \caption{Amazon Prime}
    \label{fig:amazon}
\end{figure}

\section{Literature Review}
Numerous research papers have analyzed video streaming apps such as Netflix and Amazon Prime Video. 
One such study \cite{ref1} found that viewers prefer to watch offline videos because it allows them to enjoy entertainment in areas with poor network connectivity. 
Another article \cite{ref2} revealed that original content is the most important factor for customers when choosing a paid subscription to channels.

\section{Research Methodology}
The researchers conducted exploratory research to obtain vital information about two leading media streaming service providers—Amazon Prime Video and Netflix. 
They used different exploratory research methods, including case study analysis and secondary data analysis. 
Refer to the logo of Netflix in Figure~\ref{fig:netflix}. 
Refer to the logo of Amazon in Figure~\ref{fig:amazon}.

\begin{thebibliography}{99}
\bibitem{ref1}
Sheetal Pradeep Mehta, "Determining the factors influencing customer engagement while using the subscription-based media streaming service providers: Netflix vs Amazon Prime", 2020.

\bibitem{ref2}
R. Vishnupriya, "Customer perception towards networked streaming providers with reference to Amazon Prime and Netflix", 2021.
\end{thebibliography}

\end{document}


PROGRAM11(MARKSHEET)

\documentclass[a4paper,12pt]{article}
\usepackage{graphicx} 
\usepackage{array}
\usepackage{multirow}
\usepackage{geometry}
\usepackage{setspace}
\geometry{margin=1in}
\begin{document}

\begin{center}
    \begin{figure}[h!]
        \centering
        \includegraphics[width=2cm]{psg.jpeg} 
    \end{figure}
    \textbf{\Large PSG College of Arts and Science}\\[0.2cm]
    \textbf{Affiliated to Bharathiyar University}\\[0.2cm]
    \textbf{\large SEMESTER MARKSHEET}\\[0.5cm]
\end{center}

\begin{tabbing}
    \hspace{4.5cm} \= \kill
    \textbf{Name of Student} \> : S.Hervin \\
    \textbf{Roll Number} \> : 24MCA017\\
    \textbf{Program} \> : Master of Computer Appliction\\
    \textbf{Semester} \> : IV \\
    \textbf{Examination Year} \> : 2025
\end{tabbing}

\vspace{0.5cm}
\renewcommand{\arraystretch}{1.4}
\begin{center}
    \begin{tabular}{|c|c|c|c|c|c|}
        \hline
        \textbf{S.No} & \textbf{Subject} & \textbf{Max Marks} & \textbf{Min Marks} & \textbf{Marks Obtained} & \textbf{Result} \\
        \hline
        1 & Mathematics IV & 100 & 40 & 85 & Pass \\
        2 & Data Structures & 100 & 40 & 72 & Pass \\
        3 & Operating System & 100 & 40 & 68 & Pass \\
        4 & Database Management & 100 & 40 & 75 & Pass \\
        5 & Computer Networking & 100 & 40 & 80 & Pass \\
        \hline 
    \end{tabular}
\end{center}

\vspace{1cm}
\begin{tabbing}
    \hspace{6cm} \= \hspace{6cm} \= \kill
    \> \> \textbf{Principal} \\
    \> \> (Signature with seal) \\[1.5cm]
    \textbf{Controller of Examination} \> \> \textbf{Head of Department} \\
    (Signature) \> \> (Signature)
\end{tabbing}
\end{document}


PROGRAM12(BEAMER CLASS)

\documentclass{beamer}
\usetheme{Madrid}
\title{Pilot}
\author{Guido}
\date{September 30,2025}
\begin{document}
\begin{frame}
	\titlepage
\end{frame}
\begin{frame}{Outline}
	\begin{itemize}
		\item Introduction
		\item Objective
		\item Pilot
		\item Conclusion
	\end{itemize}
\end{frame}
\begin{frame} {Introduction}
Pilot, also known as unmanned aerial vehicles (UAVs), are aircraft that operate without a human pilot onboard. They can be controlled remotely by a human operator or autonomously by onboard computer
\end{frame}
\begin{frame} {Objectives}
	Pilot have become an essential tool in modern agriculture, offering numerous benefits and transforming traditional framing practices. Here are some key objectives of using drones in agriculture. Overall, drones, enhance productivity, reduce costs and promote sustainable practices in agriculture. If you have any specific questions or need more details on a particular application, feel free to ask!
\end{frame}
\begin{frame}{Pilot}
	A pilot is a trained professional who operates an aircraft, such as an airplane or helicopter, to transport people or cargo safely to their destinations. They undergo rigorous training and must pass tests to earn a license to fly. Pilots are responsible for various duties, including filing flight plans, performing pre-flight checks on the aircraft, and flying the plane in the cockpit alongside a co-pilot and flight crew.  
\end{frame}
\begin{frame}{Conclusion}
The application of drones in warfare has also ramped up, with the Russia-Ukraine war begin labeled the "first full-scale drone war." Drone weaponry could soon become even more lethal with the introduction of swarm technology. While a single drone can be shot down easily, swarms of drones are far more difficult to defend against it's how drones are used that could turn the technology into a danger for everyday individuals. If regulations don't do enough to promote the responsible use of drones, the general public may lose trust and reject drone technology as a whole.
\end{frame}
\end{document}
