Download Link: https://assignmentchef.com/product/solved-cmsc401-trial-assignment
<br>
Trial Assignment

<ul>

 <li>Write a program that prints the multiplication of two selected numbers from a line</li>

 <li>First line of input contains the number of lines to follow</li>

 <li>First number of each line, n&gt;=4 and n&lt;=1000, contains the number of integers that follow in the line</li>

 <li>Those n integers (each integer &gt;=0; &lt;=1000) follow till the end of the line, and should be stored (except the last two) in an array using index numbers 1…n-2</li>

 <li>The last two integers x, y (x,y&gt;=1 &amp; x,y&lt;=n-2) in the line is the index</li>

</ul>

(starting from 1) of the integers from the line to multiply and print <u>Example: </u>(colors are just for visualization):

Input:                                                              Output:

3

<ul>

 <li>13 2 5 1 3</li>

 <li>5 3 6 7 4 2</li>

</ul>

9 7 12 2 14 5 7 9 6 3

<h1>Input/output in Java</h1>

<ul>

 <li>Use Standard I/O to read input and write the result For Java, input: System.in, output: System.out</li>

 <li>To read numbers, one option is:</li>

 <li>Use a single Scanner object Scanner sc = new Scanner(System.in);</li>

 <li>Use nextInt()over and over to read integers</li>

</ul>

number = sc.nextInt(); • To print numbers: System.out.println(x);

<ul>

 <li>“Do Not”s</li>

 <li>Do not read from a disk file/write to disk file</li>

 <li>Do not write anything to screen except the result

  <ul>

   <li>Ex: Human centric messages (“the result is”, “please enter..”)</li>

   <li>Automated grading via script will be used for checking correctness of your output</li>

  </ul></li>

</ul>

– Submit as a zip file with name “0_LastName_FirstName.zip” and include:

<ul>

 <li>Java source code in a single file java (all lower case letters!)</li>

 <li>The file should have <em>your name </em>in a comment in the first line</li>

 <li>Remember: in Java, class name should match the file name, and is case sensitive</li>

 <li>Please do NOT create your own packages</li>

 <li>Do NOT place the file into a folder – just zip the file</li>

 <li>Use standard I/O to read input (System.in, System.out) and output Make sure the <u>program compiles</u></li>

</ul>