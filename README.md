# babu-lang
\documentclass{article}
\usepackage{hyperref}

\title{\textbf{BabuLang - A Custom Programming Language}}
\author{Your Name}
\date{2024}

\begin{document}

\maketitle

\section*{Introduction}
BabuLang is a custom programming language inspired by Hindi keywords and C-like syntax. It is designed to explore compiler construction, recursive descent parsing, and AI-powered code assistance. The language features a complete lexical and syntax analysis system, a compiler backend that generates assembly code, and an AI-powered code suggestion module.

\section*{Features}
\begin{itemize}
    \item \textbf{Custom Syntax} – Hindi-inspired keywords with C-like syntax.
    \item \textbf{Recursive Descent Parser} – Converts source code into an Abstract Syntax Tree (AST).
    \item \textbf{Compiler Backend} – Generates NASM assembly code and links it using \texttt{ld}.
    \item \textbf{AI-Powered Code Suggestions} – Uses transformer models for syntax correction.
    \item \textbf{Executable Output} – Compiles source code into machine-executable code.
\end{itemize}

\section*{How It Works}
\begin{enumerate}
    \item \textbf{Lexical Analysis} – Tokenizes the input source code.
    \item \textbf{Parsing} – Constructs an AST using recursive descent parsing.
    \item \textbf{Code Generation} – Translates AST into NASM assembly code.
    \item \textbf{Compilation \& Execution} – Assembles and links the output into an executable file.
\end{enumerate}

\section*{Example Code}
\begin{verbatim}
likho("Hello, duniya!");  // Print "Hello, world!"

agar (x > 10) { 
    likho("X is greater than 10"); 
} warna { 
    likho("X is 10 or less"); 
}
\end{verbatim}

\section*{Tech Stack}
\begin{itemize}
    \item \textbf{C++} – Core language implementation
    \item \textbf{NASM \& LD} – Compiler backend for assembly and linking
    \item \textbf{Lex/Yacc} – (Optional) For advanced parsing
    \item \textbf{Transformer Models} – AI-powered code suggestions
\end{itemize}

\section*{Setup \& Usage}
\begin{verbatim}
git clone https://github.com/YOUR_GITHUB_USERNAME/BabuLang.git
cd BabuLang
make build
./babuc lang_script.babu
\end{verbatim}

\section*{Roadmap}
\begin{itemize}
    \item Add \textbf{loop constructs} (while, for)
    \item Implement \textbf{function support}
    \item Expand \textbf{AI-powered debugging}
    \item Create a \textbf{VS Code extension} for syntax highlighting
\end{itemize}

\section*{Contributing}
Contributions are welcome! Feel free to fork the repository, open issues, and submit pull requests.

\section*{License}
This project is licensed under the MIT License. See the LICENSE file for details.

\end{document}
