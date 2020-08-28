
APCS	August 29, 2019

Collatz Paths 

(Optional)

Your goal in this assignment is to find the number _n_ between 1 and 1000 (inclusive) that has the longest Collatz path length (a.k.a. the "total stopping time" for the Collatz sequence of n). I invite you to look at the [wikipedia article on the Collatz Conjecture](https://en.wikipedia.org/wiki/Collatz_conjecture) and this [cartoon](https://xkcd.com/710/) (or its [explanation](https://www.explainxkcd.com/wiki/index.php/710:_Collatz_Conjecture), if you must) to see what I am talking about. Actually, the wikipedia article indicates what the answer to the question is in the "Examples" section, so you might decide to stop before you get to that section to maintain your curiosity, or to go ahead and read on and consider this assignment to be a proof of that answer.

So your goal is to loop through values of _n_ from 1 to 1000, find the total stopping time for each _n_ and indicate which _n_ gave the longest total stopping time, and what it was.


<table>
  <tr>
   <td><em>n &lt;1000 </em>with longest stopping time
   </td>
   <td>what was that stopping time?
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


… and turn in your code to the PowerSchool Assignment.

If that is not a sufficient challenge, here is a minor one to add to it: I invite you to try to determine whether a number is odd or even (a requirement for the Collatz algorithm) without using floating point math (no doubles or floats like 1.0 or 2.0) or the modulus operator - just integer math. Try to find a way to determine odd/even that is reasonably fast - one that _doesn't_ require a loop.

Have fun!
