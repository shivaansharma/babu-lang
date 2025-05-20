# Compiler Project

This is a custom compiler implementation that parses and processes a unique programming language with its own syntax and semantics.

## Overview

This compiler project implements a recursive descent parser using C++ to analyze and process source code written in a custom programming language. The parser generates an Abstract Syntax Tree (AST) which represents the structure and semantics of the program.

## Features

- Tokenization of source code
- Parsing expressions with operator precedence
- Support for various data types including integers, strings, floats, and characters
- Variable declarations and assignments
- Conditional statements (if/agar)
- Scoped code blocks
- Input/output operations

## Language Grammar

The language follows this formal grammar:

```
[prog] → [stmt]*

[stmt] → babuBus ([int_lit]);
      | likhoBabu ([exp]);
      | mano ident = [exp];
      | agar([Expr])[scope]
      | [scope]*
      | {[stmt]*}

[exp] → [Term]
      | [Binexp]

[scope] → {[stmt]*}

[Binexp] → [exp] * [exp]  (prec = 1)
         | [exp] / [exp]  (prec = 1)
         | [exp] + [exp]  (prec = 0)
         | [exp] - [exp]  (prec = 0)

[Term] → ident
       | literal
       | (exp)

[literal] → int_lit
          | char_lit
          | string_lit
          | float_lit
```

## Keywords and Syntax

- `mano` - Variable declaration (equivalent to "let")
- `likhoBabu` - Output statement
- `babuBus` - Return statement
- `agar` - If statement

## Usage Examples

```
mano x = 5;
mano y = 10;
likhoBabu(x + y);

agar(x > 3) {
    likhoBabu("x is greater than 3");
}

{
    mano z = x * y;
    likhoBabu(z);
}

babuBus(0);
```

## Code Structure

The parser implementation is organized into several key components:

1. **Tokenizer** - Processes the source code into tokens
2. **Parser** - Constructs an AST from tokens
3. **AST Node Types** - Defines the structure for various language constructs
4. **Arena Allocator** - Provides efficient memory management

## Building and Running

To compile the project:

```bash
g++ -std=c++17 -o compiler main.cpp tokenize.cpp parser.cpp -Wall -Wextra
```

To run the compiler on a source file:

```bash
./compiler source_file.txt
```

## Memory Management

The project uses an arena allocator for efficient memory management of AST nodes, reducing the overhead associated with frequent allocations and deallocations.

## Dependencies

- C++17 or higher
- Standard Template Library (STL)

## Future Enhancements

- Code generation for a target platform
- Optimization passes
- Type checking system
- More complex control flow constructs
