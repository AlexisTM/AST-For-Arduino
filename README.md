AST-For-Arduino
===================

Abstract Syntax Tree (AST) for Arduino output in JSON. The aim is to produce an AST from an Arduino code. It uses [Antlr4](http://www.antlr.org/) for javascript and is precompiled for CCP14.

Generate the javascript files yourself 
----------------

Install ANTLR4

Compile

```bash 
antlr4 -visitor -listener -atn -o javascript_release -Dlanguage=JavaScript CPP14.g4
```

JSON AST
--------------

If you have other propositions, don't hesitate

```json
```

Contribute
--------------

Fork, branch, PR

Credits
----------

Alexis Paques (@AlexisTM)

