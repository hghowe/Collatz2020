APCS	August 31, 2021

## Collatz Paths 

**(Optional)**

(Github Classroom link for start code: https://classroom.github.com/a/6RP71TZn)

Your goal in this assignment is to find the number _n_ between 1 and 1000 (inclusive) that has the longest Collatz path length (a.k.a. the "total stopping time" for the Collatz sequence of n). I invite you to look at the [wikipedia article on the Collatz Conjecture](https://en.wikipedia.org/wiki/Collatz_conjecture) and this [cartoon](https://xkcd.com/710/) (or its [explanation](https://www.explainxkcd.com/wiki/index.php/710:_Collatz_Conjecture), if you must) to see what I am talking about. Actually, the wikipedia article indicates what the answer to the question is in the "Examples" section, so you might decide to stop before you get to that section to maintain your curiosity, or to go ahead and read on and consider this assignment to be a proof of that answer.

So your goal is to loop through values of _n_ from 1 to 1000, find the total stopping time for each _n_ and indicate which _n_ gave the longest total stopping time, and what it was.

(*Enter your answers on the Google Doc.*)

… and turn in your code via Github Classroom by turning in the commit code to Powerschool, like you did with the other two assignments.

If that is not a sufficient challenge, here is a minor one to add to it: I invite you to try to determine whether a number is odd or even (a requirement for the Collatz algorithm) without using floating point math (no doubles or floats like 1.0 or 2.0) or the modulus operator - just integer math. Try to find a way to determine odd/even that is reasonably fast - one that _doesn't_ require a loop.

Have fun!
