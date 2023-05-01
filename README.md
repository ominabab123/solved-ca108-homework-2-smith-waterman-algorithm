Download Link: https://assignmentchef.com/product/solved-ca108-homework-2-smith-waterman-algorithm
<br>
<h1>Smith-Waterman Algorithm</h1>

<ul>

 <li>A dynamic programming algorithm for sequence alignment</li>

 <li>Widely used in bioinformatics ()</li>

</ul>

An Example (1/2)

<ul>

 <li>Sequence 1 = ACACACTA</li>

 <li>Sequence 2 = AGCACACA</li>

 <li>match: +2, mismatch/gap: -1</li>

</ul>

An Example (2/2)

<ul>

 <li>Alignment result:</li>

 <li>Score = 12</li>

 <li>Sequence 1 =&gt; A-CACACTA</li>

 <li>Sequence 2 =&gt; AGCACAC-A</li>

</ul>

<h1>Homework</h1>

<ul>

 <li>Implement Smith-Waterman algorithm on Qtspim with following requirements</li>

 <li>Lengths of two input sequences can be changed or unequal</li>

 <li>Scores: match: +3 , mismatch: -1 , gap: -2</li>

 <li>Traceback: Starting at the highest score in the scoring matrix and ending at a matrix cell that has a score of 0</li>

</ul>

<h1>Homework</h1>

<ul>

 <li>Output should include:</li>

 <li>The highest score in the scoring matrix</li>

 <li>The traceback direction from the highest score to the 0 score</li>

 <li>(direction: (3) ,       (2) , <span style="text-decoration: line-through;">     </span>  (1) )</li>

 <li>Recommended priority: 3 &gt; 2 &gt; 1 seq 1 Example:</li>

</ul>

<h1>Homework</h1>