# PyCombinators
A package for building parsers using the Parsers Combinators method

This package is heavily inspired and is based on the parser combinators packages by Dr M. Goldberg (www.littlelisper.org).

## Parser Combinators
Parser Combinators is a compositional method for constructing parsers. It allows the programmer to essentially turn
the syntax specifications into a first-class object in your program.

This allows you to construct your parsers by joining together smaller parsers into larger ones using the algebra of 
context-free grammar (although you can build parsers for context-sensitive grammars with this package).

