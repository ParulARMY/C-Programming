# C Programming

**Description of Tutorials**<br>

Welcome to the [C Programming Tutorials from NESO Academy](https://www.youtube.com/watch?v=s0g4ty29Xgg&list=PLBlnK6fEyqRh6isJ01MBnbNpV3ZsktSyS) It is freely available on you-tube. The instructor has done a great job , he breaks down the complex topics into small chunks and thoroughly explained n an easy-to-understand manner. 
 Even if you have zero programming experience, these tutorials will take you from beginner to professional level and will help you to build up logical understanding. The great thing about these tutorials are the instructor has include questions which had been asked in GATE paper.

**************************************************************

##### This repository will contain all the related projects.If you are intrested in any code files, please run the code in an IDE for C language.

<b>Lecture 1:</b> Features & The First C program
1. Protability.
2. Procedural language
3. Middle Level language
4. Popular  choice for system apps
5. Wide variety of built in function, standard libraries and header files.<br>

  <b>*Defines*</b>
   - <b>Comments</b>: compilers usually ignore the comments. They are for programmers to make the code more readable.
   - <b>#include</b>: #include is a preprocessor which replace the text with actual content.
   - <b>stdio.h</b>:It is a standard input and output file with .h extension. It is header file. Header contain the prototype of the           functions like printf and scanf.
   - <b>main </b>: It is the starting point of the function.int main means after the completation of function it will return interger. for example `return 0` means after correct execution of function it will return 0 and if something went wrong it will return garbade value.
   <hr>

<b>Lecture 2:</b> Introduction to Variable<br>
 variables are names that points to some memory location. A variable should always declare before using it. memory location depends upon the type you use.<br>
      -<b> int</b> : 2 bytes or 4 bytes depending upon the compiler.<br>
      -<b>char</b> :1 byte<br>
Each variable must be define only once but it can be use multiple time. We can assign same value to different variable in a single line.<br>

   *syntax:* data_type name_of_variable;<br>
   *e.g:*     int var;
<hr>

<b>Lecture 3:</b> Variable Naming Convections<br>
   variable name:composed of letters or combination of letters (both upercase & lowercase) and digits. <br>
<b>*Rules for declaring variable* </b><br>
1. don't start variable name with digit.
2. begining with underscore is valid but not recommended because huge number of variable name staring with underscore are reserved keywords.
3. C language is case sensitive. so, uppercase letters are differen from lowercase letters.
4. special characters (@,#,%,&,*..) not allowed in the name of variables.
5. blanks or white spaces not allowed.
6. don't use keywords to name your variables.
<hr>

<b>Lecture 4:</b>Basic Output Function - printf<br>
    "printf" is the name of one of the main C output functions, and stands for "print formatted"

<hr>

<b>Lecture 5:</b>Fundamental Data Types-Integer(part-1)<br>
         Integers take 2 bytes(16 bits) or 4 bytes(32 bites) of memory space depending upon machine. more the size, more content it can hold.<br>
    <b>Note:</b> If we want to know the size of any datatype we can use sizeOf operator.(sizeOf ia unary operator not a function)<br>
    <b>*Range of Integer*</b><br>
     -for 2bytes(16 bits)<br>
    Unsigned range :0 to 65535(by applying :2^n-1, where n=16)<br>
    Signed  range :-32768 to +32767<br>
      -for 4bytes(32 bits)<br>
    Unsigned range : 0 to 42949672965(by applying :2^n-1, where n=32)<br>
    Signed   range : -2147483648 to + 2147483647
  
  <hr>
