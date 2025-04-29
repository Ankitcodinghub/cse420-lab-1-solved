# cse420-lab-1-solved
**TO GET THIS SOLUTION VISIT:** [CSE420 Lab 1 Solved](https://www.ankitcodinghub.com/product/cse420-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113186&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE420 Lab 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Lab 01 Introduction

I. Topic Overview:

The lab is designed to introduce the students to the basics steps of a compiler Design.

After that the lab will focuses and dive deep into the first compilation step which is Lexical analysis. Basic techniques of coding and required tools will also be shown to students.

II. Lesson Fit:

The lab gives a hand on experience of the knowledge of theory class.

III. Learning Outcome:

a. Understand and visualize the Lexical Analysis step.

b. Identifying the “Token” for a particular program.

c. Creating own version of Lexical analyzer.

IV. Anticipated Challenges and Possible Solutions

a. Finding out the identifiers and numerical values from the given code.

Possible Solutions:

i. Use regular expression. ii. Use methods of java String class.

V. Acceptance and Evaluation

Code: 0%

Viva: 100%

VI. Activity Detail

a.Hour: 2

Discussion: Basic Concepts &amp; Regular Expressions

1. What does a Lexical Analyzer do?

2. How does it Work?

3. Formalizing Token Definition &amp; Recognition

Problem task:

i. Task 1 (Page 3- 4)

Assignment 1: Problem Description

In this assignment, your job is to program a simple lexical analyzer that will build a symbol table from given stream of chars. You will need to read a file named “input.txt” to collect all chars. For simplicity, input file will be a C program without headers and methods. Then you will identify all the numerical values, identifiers, keywords, math operators, logical operators and others [distinct]. See the example for more details. You can assume that, there will be a space after each keywords. But, removal of space will add bonus point.

Lab 1: Activity List

Task 1: For the following sample program find all the tokens.

Note that a lexical Analyzer is responsible for

1. Scan Input

2. Remove WS, NL, …

3. Identify Tokens

4. Create Symbol Table (ST)

Input:

int a, b, c; float d, e; a = b = 5; c = 6; if ( a &gt; b)

{

c = a – b;e = d – 2.0; }

else

{

d = e + 6.0;b = a + c;

}

Output:

Keywords: int, float, if, else

Identifiers: a, b, c, d, e

Math Operators: +, -, =

Logical Operators: &gt;

Numerical Values: 5, 6, 2.0, 6.0

Others: , ; ( ) { }
