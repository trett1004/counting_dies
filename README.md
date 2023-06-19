# Dies!!

## Purpose
The programm counts two rolled dies. It will ask you for the first and then for the second die with inputfields.

## What is being counted.
1. The thrown number of each die
2. The sum of the two dies

## How does it work?
It is written in JavaScript. Your can see the countings in the console.
A while loop is being performed for every throw of the dies asking for die one and die two.
The input numbers will be saved in an object and the calculations are being performed.

## Result
In the end you will receive:
1. 6 objects containing the the throws for dies (1-6).
2. 12 objects containing the throws of sum of the thrown dies (1-12).


## Possible Improvemts
### Cancel the programm
Right now the programm is canceled by clicking twice on cancel for each input window. This could be improved.

### Displaying the results
The results are visible in the console. There could be a visual output in the html of the numbers or maybe also a graph.

### Errorhandling
There is no errorhandling. If you type in a number < 1 or > 6 it will be counted and saved in an object.

### Separate JS Code
The JS is written within the html file. The js could be written in a separate file,
