<h2>Checkers game</h2>
<p>The following <b>enhancements</b> have been completed:</p>
<p><i>• Identified the game winning handle and added a memoization variable to enable the game to store series of winning moves. This will shorten the steps taken to win if a move is identified as being in the wining moves series.<br>
• Implementation of a depth first search algorithm (min-max) when identifying the next move to make. This will help reduce the time it takes to get a suitable move from the current time which uses a breadth first search algorithm.</i><br></p>
<p>The skills illustrated here are in the use of algorithms and data structures to <b>solve, improve performance</b> and <b>reduce the number of steps</b> required to reach a desired solution. When using algorithms we are trying to <b>optimize</b> a solution. The solution could be found in many different ways but we find the most efficient way such that we can save on <b>time of execution</b> and the <b>resources</b> that would be required to complete the task. <b>Data structures</b> are ways of storing data so that it can be <b>manipulated</b> in a desired manner e.g. you can use a queue to implement a <b>first in first out</b> operation on a set of variables or a stack for a last in first out operation. This structures are very important when dealing with <b>arrays of data</b>.</p>

<b>The checkers game</b>
	<img src="https://github.com/Ritesh214/Checkers/blob/main/pics/Picture1.png"><br>
<b><i>Add three new lists</i></b><br>
	<img src="https://github.com/Ritesh214/Checkers/blob/main/pics/Picture2.png"><br>
<b><i>Append moves made by each player to their respective lists</i></b><br>
	<img src="https://github.com/Ritesh214/Checkers/blob/main/pics/Picture3.png"><br>
<b><i>Append the winning series of moves to the winning series list</i></b><br>
	<img src="https://github.com/Ritesh214/Checkers/blob/main/pics/Picture4.png"><br>
<b><i>When making a move check if the move exists in a winning list containing the series of moves that lead to a win and select the next move from there</i></b><br>
	<img src="https://github.com/Ritesh214/Checkers/blob/main/pics/Picture5.png"><br>
<b><i>Implement a depth first search to reduce the implementation time for the move selection process. Current implementation is breadth first search wich has high space and time complexity</i></b><br>
	<img src="https://github.com/Ritesh214/Checkers/blob/main/pics/Picture6.png"><br>
<b><i>Iterative depth first search (IDFS) implementation</i></b><br>
	<img src="https://github.com/Ritesh214/Checkers/blob/main/pics/Picture7.png"><br>
<b><i>Running the game</i></b><br>
	<img src="https://github.com/Ritesh214/Checkers/blob/main/pics/Picture8.png"><br>
<b><i>Playing the game</i></b><br>
	<img src="https://github.com/Ritesh214/Checkers/blob/main/pics/Picture9.png"><br>

<p>As shown above, the <b>planned enhancements</b> have been done. This artefact has <b>demonstrated various skills</b> that are relevant to my <b>ePortfolio</b>. These include:</p>
<p><i>• Working with data structures<br>
• Using algorithms to make processes efficient in time and computing resources<br>
• Good coding practices and standards</i><br></p>
<p>The artefact has now reduced the time it takes to select a next move by using the <b>memoization technique</b> to store winning moves. When calculating a next move, we have substituted the <b>breadth first search algorithm </b>that was in use for an <b>iterative depth first search algorithm</b> that has reduces the <b>space and time complexity</b> of the algorithm thus making it <b>more efficient</b>.
The process taught me how to practice good <b>coding standards</b> and well commented code. I also learnt the importance of selecting a <b>good algorithm</b> to implement for any given task since they perform differently under different circumstances.</p>
<h2>Review comments</h2>
<p>Hi Ritesh,<br>
This is great progress and I only have one suggestion aside from my reminder of making sure you clearly state what skills you are demonstrating. Make it super easy for the potential employer to see your logic and algorithm skills with the chess game code and narrative. You are on track.</p>
