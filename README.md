# BabuLang - A Custom Programming Language  

BabuLang is a custom programming language inspired by **Hindi keywords** and **C-like syntax**. It is designed to explore **compiler construction, recursive descent parsing, and AI-powered code assistance**. The language features a **custom lexer, parser, and assembly-based backend**.

## 🚀 Features
- ✅ **Custom Syntax** – Hindi-inspired keywords with C-like syntax.  
- ✅ **Recursive Descent Parser** – Converts source code into an **AST**.  
- ✅ **Compiler Backend** – Generates **NASM assembly** and links with `ld`.  
- ✅ **AI-Powered Code Suggestions** – Uses **transformer models** for auto-completion.  
- ✅ **Executable Output** – Compiles source code into a **binary executable**.  

## ⚡ How It Works
1️⃣ **Lexical Analysis** – Tokenizes the input source code.  
2️⃣ **Parsing** – Constructs an **Abstract Syntax Tree (AST)**.  
3️⃣ **Code Generation** – Translates AST into **NASM assembly code**.  
4️⃣ **Compilation & Execution** – Assembles and links the output into an **executable file**.  

## 🔥 Example Code (BabuLang Syntax)
```cpp
likho("Hello, duniya!");  // Print "Hello, world!"

agar (x > 10) { 
    likho("X is greater than 10"); 
} warna { 
    likho("X is 10 or less"); 
}
