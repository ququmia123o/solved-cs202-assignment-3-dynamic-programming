Download Link: https://assignmentchef.com/product/solved-cs202-assignment-3-dynamic-programming
<br>
<h1></h1>

Solve the the following Dynamic Programming problem with optimization using C++ programming language.

<ol>

 <li>The similarity between two strings where similarity of two strings X and Y is defined as M which is gap penalty or mismatch cost for pair of characters at same index in the two strings. Gap penalty and Mismatch cost is as defined in the book by Kleinberg and Tardos section 6.6.</li>

 <li>You need to align two input DNA Sequences such that this cost of M for these two sequences is minimum.</li>

 <li>Basic correct implementation of the algorithm – (Marks-10)</li>

 <li>Optimization in Linear Space via Divide and Conquer (Marks-20)</li>

</ol>

<em>Above marks will be provided only if below mentioned files are present.</em>

You can implement these in two cpp files, one for first part and other for second part.

For the evaluation of the above files, each file should take two DNA strings as input and output the optimal alignment of the two strings and its cost as per the gap and mismatch cost.

Output Format –

Optimal Alignment of String 1

Optimal Alignment of String 2

Cost = <em>&lt;</em>Cost Value<em>&gt;</em>

Use − to represent a gap in string alignment. See sample I/O for more understanding

Compile the files to take an argument from the command line as 1 or 2.

<ol>

 <li>If argument is 1 – gap penalty = 6, mismatch penalty = 4</li>

 <li>If argument is 2 – gap penalty = 4, mismatch penalty = 6</li>

</ol>

Note: We will run the code in given format –

./part1 1

./part1 2

./part2 1

./part2 2

Sample Input Output:

argument 1 –

Input –

ATAT

GCAT

Output –

ATAT

GCAT Cost = 8 argument 2 –

Input –

ATAT

TATA

Output –

-ATAT TATACost = 8

IMPORTANT:

Do not hard code anything for any of the part. The argument change should only change the penalty values and should have no other change in the code.

BONUS:

2

Take input an argument three and have different penalty values for A-G and T-C mismatch from the usual mismatch penalty.