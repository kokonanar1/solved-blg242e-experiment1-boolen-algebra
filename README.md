Download Link: https://assignmentchef.com/product/solved-blg242e-experiment1-boolen-algebra
<br>
The aim of this experiment is to recall the axioms and theorems of Boolean algebra and validate these axioms and theorems using the Verilog.

<ul>

 <li>Please complete the preliminary work and explain their in detail in your report.</li>

 <li>You are allowed to use ‘&amp;’ (Bitwise AND), ‘|’ (Bitwise OR), and ‘∼’ (Bitwise NOT) operations. Other operations such as ‘ˆ ’, ‘+’, ‘-’, ‘*’, ‘/’, ‘<em>&lt;&lt;</em>’, and ‘<em>&gt;&gt;</em>’ are forbidden.</li>

 <li>More complex experiments will be later experiments, so you can not use always, parametric modules, switch case, and if else in this experiment.</li>

</ul>

<em>For your questions: Abdullah Ekrem Okur (<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="7916120c0b181b1d39100d0c571c1d0c570d0b">[email protected]</a>)</em>

<h1>2      Preliminary</h1>

<ul>

 <li>Revise the axioms and theorems of Boolean algebra.</li>

 <li>Prove the given equalities below by using the axioms of Boolean algebra. Please specify which axioms you use.

  <ul>

   <li><em>a </em>+ <em>a </em> <em>b </em>= <em>a</em></li>

   <li>(<em>a </em>+ <em>b</em>) · (<em>a </em>+ <em>b</em><sup>0</sup>) = <em>a</em></li>

  </ul></li>

 <li>Determine and prove the duals of the equalities defined above.</li>

 <li>Calculate the complementary expression (<em>F</em><sup>0</sup>) for the function <em>F </em>which is defined as follows (<em>F </em>= <em>a</em><em>b</em>+<em>a</em><sup>0 </sup>·<em>c</em>) by using De Morgan theorem and draw the logic circuit for both expressions (<em>F </em>and <em>F</em><sup>0</sup>).</li>

 <li>Simplify given logical function and draw the logic circuit.

  <ul>

   <li><em>F</em>(<em>a,b,c,d</em>) = ∪<sub>1</sub>(1<em>,</em>2<em>,</em>5<em>,</em>6<em>,</em>9<em>,</em>10<em>,</em>13<em>,</em>14)</li>

  </ul></li>

</ul>

1

<em>Experiment 1 Boolen Algebra</em>

<h1>3      Experiment</h1>

Part 1

In this part, you are requested to implement AND, OR, NOT modules which you will use in the following experiments. You are not allowed to use these operators in the following parts, you can only use these modules when you need them.

Part 2

In this part, you should design and implement the logic circuits for the given expressions below by using AND, OR, NOT modules which you designed in the first part. Then, you should simulate it for each different combination of input and validate the correctness of your implementation.

<ul>

 <li><em>F</em><sub>1</sub>(<em>a,b</em>) = <em>a </em>+ <em>a </em> <em>b </em>= <em>a</em></li>

 <li><em>F</em><sub>2</sub>(<em>a,b</em>) = (<em>a </em>+ <em>b</em>) · (<em>a </em>+ <em>b</em><sup>0</sup>) = <em>a</em></li>

</ul>

Part 3

A theorem is given as: (<em>a </em>+ <em>a </em>· <em>b </em>= <em>a</em>).

First, determine the dual of the given theorem and then, implement the functions for both sides of the dual theorem using AND, OR, NOT modules which you designed in the first part. Please validate the truth of the theorem by comparing the changes in the outputs using simulation.

Part 4

<em>F</em><sub>3</sub>(<em>a,b,c</em>) = <em>a </em>· <em>b </em>+ <em>a</em><sup>0 </sup>· <em>c </em>is given.

Firstly, determine the complement of the given function (<em>F</em><sub>3</sub>). Then, implement the circuit which realizes the complementary function ( ).             Please validate your implementation by using the truth table and simulate it for each different combination of input.

Part 5

A basic logical function (<em>F</em>4) is defined as follows.

<em>F</em><sub>4</sub>(<em>a,b,c,d</em>) = ∪<sub>1</sub>(1<em>,</em>2<em>,</em>5<em>,</em>6<em>,</em>9<em>,</em>10<em>,</em>13<em>,</em>14)

First, simplify given logical function and implement the simplified expression using AND, OR, NOT modules which you designed in the first part. Please validate your implementation by observing the outputs for each possible input.

2

<h1>4      Report</h1>

Prepare your report using the guidelines and the report template which are posted on Ninova e-Learning System. Please report the preliminary work in detail. Your report should also include the following materials:

<ul>

 <li>Circuits diagrams of the expressions which were implemented during this experiment.</li>

 <li>Function tables (or truth tables) of the implemented expressions.</li>

 <li>Simulation outputs of each part.</li>

</ul>

Additionally, if there were any complications which affect your performance during the experiment, please also indicate these difficulties in your report.