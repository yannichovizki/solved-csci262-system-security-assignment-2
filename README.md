Download Link: https://assignmentchef.com/product/solved-csci262-system-security-assignment-2
<br>
Make sure you include referencing for answers where it would obviously be needed.

<ol>

 <li>You have two puzzles with parameters as follows:</li>

</ol>

Puzzle A: One sub–puzzles. <em>k </em>= 6.

Puzzle B: Eight sub-puzzles. <em>k </em>= 3.

You should provide, for both cases other than part (b), the following:

<ul>

 <li>The distribution of the number of cases that require each number of hashes. <strong>1 Mark</strong></li>

 <li>Explain the method you used to obtain your distributions. Don’t go into too many detailsor show working, it’s more “I wrote a C++ program to … and then using … I …”. <strong>5 Mark</strong></li>

 <li>A graph of the distribution of the data above. <strong>5 Mark</strong></li>

 <li>The average number of hashes needed. <strong>5 Mark</strong></li>

 <li>The standard deviation for the distribution of the number of hashes needed. <strong>5 Mark</strong></li>

</ul>

You should assume that if there are <em>N </em>possible solutions you check the <em>N<sup>th </sup></em>by hashing even if all others have failed and there has to be a solution.

<ol start="2">

 <li>Which general security principle is violated in the following pseudo-code? Modify the pseudo-codeto fix the potential security problem. <strong>1 Mark</strong></li>

</ol>

permit = CheckAccess() IF (permit == Access_Denied) Print “Access Denied”

ELSE

Print “Access Granted”

Run Function()

<ol start="3">

 <li>Consider that the incidence of viral attachments in email messages in 1 in 800. Your malware checkerwill correctly identify a message as viral 95% of the time. Your malware checker will correctly identify a message as non–viral 95% of the time. Your malware checker has just flagged a message as being malware. What is the probability that the message is actually okay? Justify your answer using Bayes theorem. <strong>1 Mark</strong></li>

 <li>Describe, in your own words, a specific instance of an insider placing malware within a system. Youshould describe the type of malware placed, the expected likely impact, and some details regarding the outcome. This is not meaning a hypothetical scenario you have made up, find an actual real world example. <strong>2 Marks</strong></li>

 <li>Every hour the worm <strong>X </strong>spreads from each infected computer to one previously uninfected computers. In answering these questions you should explain how you determined your answers.

  <ul>

   <li>Give a table showing the number of infected computers at each hour across a 24 hour period.</li>

  </ul></li>

</ol>

At time <em>t </em>= 0 the number of <strong>X </strong>infected computers is <em>N </em>= 1.                                          <strong>0.5 Mark</strong>

<ul>

 <li>By time <em>t </em>= 6<em>.</em>5 a counter worm <strong>W </strong>has been developed and it is deployed on one infected computer. <strong>W </strong>removes malware <strong>X </strong>from any host <strong>W </strong>is on. The counter worm <strong>W </strong>spreads slightly more quickly than <strong>X</strong>, with each <strong>W </strong>spreading to two <strong>X </strong>infected hosts each hour, provided such hosts are available.</li>

</ul>

Provide another table showing the spread of <strong>W </strong>and the impact on <strong>X </strong>across an appropriate time frame, starting from <em>t </em>= 0 again.

Note the offset in time means that at <em>t </em>= 6<em>.</em>5 the number of <strong>X </strong>infected computers reduces by 1, so the spread of <em>t </em>= 7 will be slightly smaller than before. Overall the number of <strong>X </strong>infected computers will go up on the hour, and down on the half hour. <strong>1.5 Marks</strong>

<ul>

 <li>Graph the two cases against each other, clearly indicating on it where <em>N </em>= 0. <strong>5 Mark</strong></li>

 <li>Assume that at time <em>t </em>= 9, <strong>X </strong>evolves to spread to three uninfected computers each hour. What subsequently happens? <strong>5 Mark</strong></li>

</ul>

<ol start="6">

 <li>Briefly describe, in your own words, each of the following. Be sure to specify the domain and natureof each.</li>

</ol>

<table width="673">

 <tbody>

  <tr>

   <td width="602">(a) An XML bomb.</td>

   <td width="71"><strong>0.5 Mark</strong></td>

  </tr>

  <tr>

   <td width="602">(b) BlueSmack.</td>

   <td width="71"><strong>0.5 Mark</strong></td>

  </tr>

  <tr>

   <td width="602">(c) Mydoom.</td>

   <td width="71"><strong>0.5 Mark</strong></td>

  </tr>

  <tr>

   <td width="602">(d) Torpig.</td>

   <td width="71"><strong>0.5 Mark</strong></td>

  </tr>

 </tbody>

</table>


