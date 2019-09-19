## Chapter 3 Lexical Analysis

### Functions

- lexeme to token
- special symbol filtering
- add lexeme to symbol table
- logical independent to syntax analysis but in the same pass
  - pass: one input file to one output file

### Why Independent

- simplify the design of a compiler
- improve efficiency 
  - easier compared with syntax
- transportability

### Token, Pattern, Lexeme

#### Token

- <name, attribute(optional)>

#### Pattern

#### Lexeme

- chars
- match pattern, recognized as token instance

#### Sample

![p1](c3/c3p1.png)

### Rules of Token(Regular Expression)

### Recognition of Token(State Transition Diagram)

### Tools(Lex/Flex)

### NFA/DFA

#### DFA minimize

- IMP: First Divide {Start - Final, Final}
- Add φ when a node's outdegree does not equal to the number of marks