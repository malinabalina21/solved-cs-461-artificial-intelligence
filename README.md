Download Link: https://assignmentchef.com/product/solved-cs-461-artificial-intelligence
<br>



<h1>HOMEWORK #1 (5% OR​ 10 <sub>​</sub> POINTS​ )</h1>




<em>Your group for this homework should coincide with your term project group. In any case, indicate clearly the students who are submitting the homework (i.e., write at most 5 names on the submission). </em>

<em>You must submit your homework (including  all the original code written) to our TAs. Just a single submission per group! </em>​<em>Our TAs will soon send you a note explaining the mechanics of submissions. </em>

<em>Any programming language can be used as long as you have it up-and-running on a portable computer. Any group member should be prepared to give a homework demo (online or face-to-face  and using that computer) when requested to do so by our TAs.</em>







In this homework, you’ll work on a variant of  the following classical puzzle:

MISSIONARIES &amp; CANNIBALS: A group consisting of 3 cannibals and 3 missionaries seeks to cross a river. A boat is available which will hold up to 2 people. If the missionaries on either side of the river are outnumbered at any time by the cannibals on that side, even momentarily, the cannibals will do away with the unfortunate, out-numbered missionaries. What schedule of crossings can be devised to permit the entire party to cross safely? (Assume that the group and the boat are on the west bank initially and that they would like to end up on the east bank eventually.)

The two instances you’ll solve (by implementing a single program) are as follows (each worth 5 points):

<ol>

 <li>There are 5 cannibals, 5 missionaries, and a boat holding 3</li>

 <li>Pick one of the following:

  <ol>

   <li>There are 6 cannibals, 6 missionaries, and a boat holding 4</li>

   <li>There are 6 cannibals, 6 missionaries, and a boat holding 5</li>

  </ol></li>

</ol>

Your program must use either DFS or BFS.​ ​(Winston, Chapter 4). It must check for ​repeated ​states. Needless to say, we require that the boat not contain more cannibals than missionaries.

What should be the output of your program? For both instances above, some such sequence of moves resembling the following will be just fine (N.B. the following solution is for the classical version, viz. 3 cannibals, 3 missionaries, and a boat holding 2):










REFERENCES

There are many papers that you can read about the M&amp;S problem but this won’t be necessary unless you’re really interested. I think the following is especially well-written:

<ul>

 <li>Fraley, Robert, et al. “Graphical Solution of Difficult Crossing Puzzles.” ​<em>Mathematics Magazine</em>​, vol. 39, no. 3, 1966, pp. 151–157. ​<em>JSTOR</em>​, www.jstor.org/stable/2689307. Accessed 25 Sept.</li>

</ul>

2020.




<em><u>Caveat:</u> </em>

It is crucial that you explain, in the body of your program and using block comments, how your program does what it does. Don’t forget to state which search strategy you use, DFS or BFS. Also state which question (2a or 2b) you’ve picked.

Your program should also have a simple logic for ‘single stepping’ (tracing)​         so that the TAs can inspect​       the intermediate stages of the problem-solving process in an incremental fashion. This is also useful for debugging your program during the development stage.





