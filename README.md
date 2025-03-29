# BabuLang - A Custom Programming Language  

BabuLang is a custom programming language inspired by **Hindi keywords** and **C-like syntax**. It is designed to explore **compiler construction, recursive descent parsing**. The language features a **custom lexer, parser, and assembly-based backend**.

## 🚀 Features
- ✅ **Custom Syntax** – Hindi-inspired keywords with C-like syntax.  
- ✅ **Recursive Descent Parser** – Converts source code into an **AST**.  
- ✅ **Compiler Backend** – Generates **NASM assembly** and links with `ld`.  
- ✅ **Executable Output** – Compiles source code into a **binary executable**.  

## ⚡ How It Works
1️⃣ **Lexical Analysis** – Tokenizes the input source code.  
2️⃣ **Parsing** – Constructs an **Abstract Syntax Tree (AST)**.  
3️⃣ **Code Generation** – Translates AST into **NASM assembly code**.  
4️⃣ **Compilation & Execution** – Assembles and links the output into an **executable file**.  

## 🔥 Example Code (BabuLang Syntax)
```cpp
likhoBabu(10+40); 
mano x =10;
agar (x > 10) { 
    likhoBabu(x); 
} warna { 
    likho(0); 
}
babuBus(0);
