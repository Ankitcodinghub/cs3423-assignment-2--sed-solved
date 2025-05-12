# cs3423-assignment-2--sed-solved
**TO GET THIS SOLUTION VISIT:** [CS3423 Assignment 2- Sed Solved](https://www.ankitcodinghub.com/product/cs3423-assignment-2-sed-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91185&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS3423 Assignment 2- Sed Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
sed

</div>
</div>
<div class="layoutArea">
<div class="column">
For this assignment, you will use sed and bash to create a program for formatting C code. Your program should take a source code file as input and apply the following:

<ul>
<li>No more than one space between tokens.</li>
<li>No trailing whitespace after a line.</li>
<li>Binary operators should always surrounded by a single space on either side (including assign-
ment and Boolean operators). Only the following operators must be accounted for: +, -, *, /,

!=, =, ==, &lt;=, &gt;=, &lt;, &gt;, &amp;&amp;, ||, and ˆ.
</li>
<li>Conditions should not have whitespace immediately inside of either the opening or closing
parentheses. Further, a parenthetical condition should not possess any whitespace preceding

it.
</li>
<li>The program should not modify spaces which are leading, expanded tabs.</li>
<li>The program should ensure that each opening curly brace, that does not begin the line it is
on (excluding existing whitespace), should have at least one space character preceding it.
</li>
<li>The contents of comments should be left alone. You may behave as though comments (either
single- or multi-line) will not appear on lines with source code.

Note: Do to the use of the “&lt;” and “&gt;” “operators” in preprocessor directives, ignore all lines consisting of preprocessor directives (e.g., lines beginning with zero or more whitespace, followed by a hash (“#”) character).

Note: Do not be concerned with changes in strings; if any such replacement changes the contents of a string, this need not be corrected for, nor will it be considered an issue.

Hint: All of the above does not need to be done in a single pass.

This assignment requires only sed and bash. Do not use awk, Python, or any other languages/util-

ities.
</li>
</ul>
</div>
</div>
<div class="layoutArea"></div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Example

In the code below, underscores (_) represent spaces in the source code. Note that there are no changes to comments or pre-processor directives (i.e. #include) lines.

Input (inputProgram.c):

1 2 3 4 5 6 7 8 9

<pre>10
11
12
13
14
15
16
17
18
19
20
21
22
23
</pre>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
/** author:_____some_student **/

#include_ &lt;stdio.h&gt;

int_main()_{

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
____int_numberIn; ____printf(“Enter_a_number:_”); ____scanf(“%d”,_&amp;numberIn);__ ____if_(_numberIn_ &gt;_10_)_{

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
____//____add__two ________return_numberIn_+__2; ____}_else___if____(numberIn &lt;___5){ ____//____subtract_two___ ________return__numberIn_ -_2;

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
____int____isNumOdd__=_numberIn__%__2;

____return__numberIn *2; }

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
1 2 3 4 5 6 7 8 9

<pre>10
11
12
13
14
15
16
17
18
19
20
21
22
23
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Output (outputProgram.c):

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
/** author:_____some_student **/

#include_ &lt;stdio.h&gt;

int_main()_{

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
____int_numberIn; ____printf(“Enter_a_number:_”); ____scanf(“%d”,_&amp;numberIn); ____if(numberIn_ &gt;_10)_{

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
____//____add__two ________return_numberIn_+_2; ____}_else_if(numberIn_ &lt;_5)_{ ____//____subtract_two___ ________return_numberIn_ -_2;

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
____int_isNumOdd_=_numberIn_%_2;

____return_numberIn_*_2; }

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Script Execution

</div>
</div>
<div class="layoutArea">
<div class="column">
Your program should be invoked through a single bash file (see below) with the path to the input program as the argument. The resulting output file should be printed directly to stdout.

<pre>$ assign2.bash /path/to/input.txt
</pre>
Assignment Data

A sample input file can be found in: /usr/local/courses/ssilvestro/cs3423/Spring20/assign2.

Script Files

Your program should consist of at least two files:

• assign2.bash – the main file which is initially invoked

• At least one .sed file which is used for a sed invocation run in assign2.bash. Each sed invocation should have its own .sed file which may contain multiple sed commands.

For example, your submission may include assign2.bash, command1.sed, command2.sed, …, commandN.sed where each .sed file correspond to sed invocations within assign2.bash.

Verifying Your Program

Your program must work for any arbitrary input files by applying the rules above. You can test your program with the input provided in inputProgram.c and compare the output with outputProgram.c using diff (check the man-pages on how to use the diff command to your requirements).

</div>
</div>
</div>
