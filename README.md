# BNF Interpreter
 Define your own language using this BNF Interpreter
This Webpage use Javascript and BNF table to read your text and execute it.
It is a three steps operations:
1) Build a tree structure with your text.  Around 150 lines of code.
2) Rebalance a tree.  Same family operation (+-, or */) has priority on the left. Around 25 lines of code.
3) Execute a tree.  Around 25 lines of codes.

At the top of the webpage, you can see the BNF use in this program.
After that, a input text area where you can paste your equation.
If you want to generate a random equation to test, click Generate.
You can click compute and this program with execute your equation with your BNF and compare its value with Javascript.
Up to this day, every result are the same with the BNF included with this program.
The only problem with Javascript is the error generated with 1++1 even if it is a correct statement.
