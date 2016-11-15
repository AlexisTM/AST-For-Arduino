AST-For-Arduino
===================

Abstract Syntax Tree (AST) for Arduino output in JSON. The aim is to produce an AST from an Arduino code. 
The project can use [TXL](txl.ca) and will use [Antlr4](http://www.antlr.org/) later ... once I understood how it works. 
Finally, D3.JS will format the program to 

JSON AST
--------------

If you have other propositions, don't hesitate

```json

{
	"program": {
		"classes": [{}],
		"functions": [{}],
		"variables": [{}],
		"parent": {}
	}
}

Class : 
{
	"name": "className",
	"properties": [{}],
	"functions": [{}],
        "parent": {}
}

Function : 
{
	"name": "oneFunction",
	"paramerters": [{}],
	"return": {}
}

Variable : for properties, variables, parameters, return
{
	"name": "oneProperty",
	"type": "uint8_t",
        "visibility": "public | protected | private",
	"default": 8
}
```


Contribute
--------------

Fork, branch, PR

Credits
----------

Alexis Paques (@AlexisTM)

