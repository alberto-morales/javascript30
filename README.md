When trying javascript30 course, after first day lesson, I followed the Wes Bos advice (creator of the javascript30 challenge), building things. What things?

In this repository, I'm going to share you my "homework". First of all, we're going to make JavaScript Pair Match game.

It is a memory game where you need to match pairs of tiles. Playing is very simple: you turn over one tile and then try to find a matching tile. When you click on the first tile of a turn, you should be able to make a match (if you have exposed a matching tile in a previous turn, and you have perfect recall, or obviously, by serendipity).

Following the javascript30 course approach, no frameworks, no compilers, no libraries, no boilerplate will be used, only vanilla JavaScript coding (a base of html and css is assumed).

The more important things we learn from this exercise are:

1) The massive use of the HTML DOM querySelector() method (combined with the use of data (non standard) attributes). Its important the way you set data (custom) attributes to DOM elements, when you use querySelector to select this elements.

2) The use of a closure to build your own random numbers generator, based on a list of numbers.

You can find the post with explanations and video here:

http://albertomorales.eu/blog/my-homework-after-completing-javascript30-course-day-1-lesson-javascript-pair-match-game/