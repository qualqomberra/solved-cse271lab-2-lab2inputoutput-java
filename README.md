Download Link: https://assignmentchef.com/product/solved-cse271lab-2-lab2inputoutput-java
<br>
Write a program, Lab2InputOutput.java, that reads a file containing text.

The name of the input file will be provided by a user of your program as a (the first) command line argument to your program (see lecture 2_1 or the textbook for a reminder on command line arguments).

Prompt the user (system.in) for the name they want to use for the output file using the console.

For this part you do not need to handle the exception. Rather, you can just “throws” it to the main level and have the stack trace printed.




Read each line and send it to the output file, preceded by <em>line numbers</em>.

Example

If the input file is

Mary had a little lamb

Whose fleece was white as snow.

And everywhere that Mary went,

The lamb was sure to go!

then the program produces the output file

/* 1 */ Mary had a little lamb

/* 2 */ Whose fleece was white as snow.

/* 3 */ And everywhere that Mary went,

/* 4 */ The lamb was sure to go!

<h1>Part 2</h1>

Write a program, Lab2FloatingPoint.java, that asks the user to input a set of floatingpoint (<strong><u><a href="https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html">float</a></u></strong><a href="https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html">)</a> values ONE AT A TIME.

When the user enters a value that is not a number, give the user a second chance to enter the value <strong><em>USING EXCEPTIONS by catching the appropriate exception</em></strong>.

After two (failed) chances <strong>in a row</strong>, quit reading input and continue the program.

Finally, add all correctly specified values and print the sum when the user is done entering data. You must u<strong><em>se exception handling to detect improper inputs.</em> </strong>

<strong>HINT: Follow the DataAnalyzer example from class &amp; Textbook Section 7.5 in regards to having an outer loop with exceptions </strong>

<strong>Sample run of second part of Lab 2, demonstrating that it is two exceptions in a row.   </strong>

<strong>2 4 a 4 2 a b </strong>