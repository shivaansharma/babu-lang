# Babu Lang: Its just like talking to your girlfriend its barely makes any sence !!!

Welcome to Babu Lang, the programming language that's just like talking to your girlfriedn - it barley makes any sence! Created by someone who thought "Why write code that actually runs when we can write code that makes you question your career choices?"

## What is Babu Lang?

Babu Lang is the result of a fever dream had by a programmer who fell asleep watching Bollywood movies while debugging C++ pointers. It's a language where error messages are more cryptic than your girlfriend's text responses, and syntax feels like it was designed by a committee of cats walking across keyboards.

## Features (or "Quirks" as we like to call them)

- **Confusing Keywords**: "mano" for variables, "likhoBabu" for printing, and "babuBus" for return statements. It's like someone replaced all your function names with baby talk!
- **Bizarre Syntax**: It's just like talking to your girlfriedn - it barley makes any sence!
- **Error Messages**: Written in Sanskrit, translated to Latin, then poorly converted to English by someone who speaks neither.
- **Performance**: Runs at the speed of your girlfriend deciding where to eat dinner.

## The Babu Lang Grammar (AKA: "What Were We Thinking?")

```
[prog] → [stmt]* (A program is just a bunch of statements, like how a relationship is just a bunch of misunderstandings)

[stmt] → babuBus ([int_lit]); (Return statement, for when you want to rage quit)
      | likhoBabu ([exp]); (Print statement, for when you need to cry for help)
      | mano ident = [exp]; (Variable declaration, named after the sound you make when debugging this language)
      | agar([Expr])[scope] (If statement, for when you want conditional suffering)
      | [scope]* (Nested scopes, for when you hate yourself)
      | {[stmt]*} (Code blocks, for organizing your terrible life choices)

[exp] → [Term] (Simple expressions)
      | [Binexp] (Complex expressions that will make you question reality)

[scope] → {[stmt]*} (A place to hide your shame)

[Binexp] → [exp] * [exp]  (Multiplication, or as we call it, "pain multiplier")
         | [exp] / [exp]  (Division, for dividing your sanity in half)
         | [exp] + [exp]  (Addition, for adding to your frustration)
         | [exp] - [exp]  (Subtraction, for removing your will to live)

[Term] → ident (Variables, if you can remember what you named them)
       | literal (Actual values, rare as they are)
       | (exp) (Parentheses, because we needed more ways to confuse you)

[literal] → int_lit (Integers, for counting your regrets)
          | char_lit (Characters, for single-letter swear words)
          | string_lit (Strings, for multi-letter swear words)
          | float_lit (Floating point, for when integers aren't frustrating enough)
```

## Usage Examples (or "Ways to Torture Yourself")

```
mano x = 5; // Declaring a variable, simple enough... FOR NOW
mano y = 10; // Another one, feeling confident?
likhoBabu(x + y); // Printing the sum, which will probably be 42 somehow

agar(x > 3) { // If statement, or "agar" as we call it because... reasons
    likhoBabu("x is greater than 3"); // This will print... sometimes
}

{
    mano z = x * y; // Scoped variable, will vanish like your hopes and dreams
    likhoBabu(z); // Printing z while it still exists
}

babuBus(0); // Return statement, your sweet release from this nightmare
```

## Installation

1. Don't.
2. Seriously, don't.
3. If you insist, compile with:
```bash
g++ -std=c++17 -o bad_decisions main.cpp tokenize.cpp parser.cpp -Wall -Wextra -Wsanity-check
```

## Debugging Tips

1. Cry
2. Question your life choices
3. Wonder why you didn't become a baker instead
4. Google "how to explain to my parents I'm quitting programming"
5. Return to step 1

## Memory Management

The project uses an arena allocator for efficient memory management of AST nodes, which is the only mercy we've shown in this entire language design.

## Dependencies

- C++17 or higher
- A strong will to live
- Therapy (recommended)
- A sense of humor (required)

## Future "Enhancements"

- More cryptic error messages
- Random semicolon requirements
- Keywords that change meaning based on the phase of the moon
- Documentation written entirely in interpretive dance

Remember, it's just like talking to your girlfriedn - it barley makes any sence! But that's half the fun, right?

...right?
