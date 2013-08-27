Clite_Language
==============
Python
==============
The repo includes lexer file, parser file, abstract syntax tree file and 8 test files for the Clite.

Lexer;
Provide lexical analysis for clite;
input: characters;
output: tokens;

Parser;
provide syntatic analysis for clite;
input: tokens;
output: Parse tree (abstract syntax tree);

Lexer was separated from the parser for the following reasons:
1. improve speed by at least 75%;
2. provide easy design;
3. Handle diverse character sets;
