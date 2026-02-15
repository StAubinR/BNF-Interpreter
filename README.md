# BNF Interpreter
Define your own language using this BNF Interpreter
This minimalist program use Javascript and BNF table to read your text and execute it.
It is a three steps operations:
1) Build a tree structure with your text.  Around 150 lines of code.
2) Rebalance a tree.  Same family operation (+-, or */) has priority on the left. Around 25 lines of code.
3) Execute a tree.  Around 25 lines of codes.

A webpage is used to show how this BNF interpreter works.
At the top you have BNF use in this program.  If a BNF name do not exist, you will have an error.
After that, a input text area where you can paste your equation.
If you want to generate a random equation to test, click Generate.
Click compute and this program with execute your equation and compare its value with Javascript.

Two webpages with two different BNF and the same BNFInterpreter are used:
- SimpleMath.html use a very simple BNF with only mathematic equation
   <p>https://staubinr.github.io/BNFInterpreter/SimpleMath.html</p>
- MathWithLogic.html include logic operators
   <p>https://staubinr.github.io/BNFInterpreter/MathWithLogic.html</p>
  