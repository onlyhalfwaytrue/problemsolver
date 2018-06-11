PROJECT DESCRIPTION

The goal of this project is to create a problem solving system which can address word problems. We want them to be provided by either typing into an input stream or read via images understood via character recognition.

The steps in which the program would have to be structured are

1. Input-> 2. Generate mathematical expression -> 3. Solve mathematical expression

Part 1.
Input via typing is easily dealt with through standard input streams.
Character recognition is good to have but it is not totally necessary so it can be addressed once we get further into the second part.

Part 2.
Here is where the major contributions lie. We need to be able to understand human text and turn it into mathematical expressions which are solvable. This means we need to take human language and turn it into mathematics. A good place to start would be logic problems since those are stated in English as closely to the actual math as possible. Calculus and other problems usually have obfuscation which is tougher to deal with since we get stories about who bought what when.

Part 3.
Solving these expressions is something that symbolic arithmetic engines already do. We need to figure out if we will create our own, or output scripts which run on these other engines (maybe Mathematica, or Matlab).

Suggestion:
Build this in the order of part 2 first and then parts 1 and three in whatever order ends up making sense. This because the most unique thing we are doing happens here, which is taking words and understanding the mathematical problem in them.
I see three approaches here: 1. Build from the ground up the ability to read the mathematical problems out of the word problems, 2. Use machine learning to take questions and find the expression, 3. Use a mixture of both in different areas and “teach” the program to read in the right places in a word problem to find the mathematical expression that needs to be solved.
