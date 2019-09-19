## Chapter 1 Introduction

### Functions of a Compiler

#### Compiler

- Input a program written in some kind of language(source language)
- output this program in another language(target language)
- this program supposed to be executable

#### Interpreter

- Use inputs to execute the given operations in source program
- No target program is generated, executed directly
- Java is a kind of language that integrated Compiler & Interpreter

### Structure

#### Analysis/Front end

- program to token & syntax structure
- structure built intermediate representation
- info to symbol table

#### Synthesis/Back end(related to machine)

- construct target program using the representation & symbol table

#### Phases

![p1](C1/c1p1.png)

### Lexical analysis

#### Scanning

- output Lexeme
- <token-name, attribute-value>
- token-name works for syntax analysis
- attribute-value works for semantic analysis & code generating

![p2](C1/c1p2.png)

### Syntax analysis

#### Parsing

- Build Syntax tree
- Get syntax structure

![p3](C1/c1p3.png)

### Semantic analysis

- check with symbol table & syntax tree
- generate code, check types, type shift

![p4](C1/c1p4.png)

### Generate intermediate code

![p5](C1/c1p5.png)

### Polish

- faster & more effective

![p6](C1/c1p6.png)

### Final code generating

- allocate registers
- choose proper operations

![p7](C1/c1p7.png)

### Others

#### Symbol table

- Record variables' name & attributions

#### Tools

- Scanner: Lex/Flex
- Syntax analyzer: Yacc/Bison
- Other transcript engines...

#### Applications

- Program Transcription
- SF Quality & Productivity
  - type check
  - bound check
  - internal memory manage
