---
title: Bulgarian Solitaire
type: problem
printOrder: n/a
added: 2021-03
---

# Bulgarian Solitaire

This question is about a city of skysrapers, like the one below:

<img src="../../images/bulgarian-solitaire-01.png" width=75>

Each *skyscraper* is a stack of a certain number of squares and, in a *city*, the skyscrapers are arranged in height order from left to right.  
So the *city* above has a total of 7 squares. It has two *skyscrapers*, one 5 squares and one 2 squares high.

King Kong decides to rearrange the city. To do this, he removes the top square off of each skyscraper and uses the square that he has collected to build a new skyscraper. He finishes his new city by arranging the skyscrapers in height order from left to right.

<img src="../../images/bulgarian-solitaire-02.png" width=350>

He sits back to admire his work. Then he then decides to rebuild his new city, again removing the top square of each skyscraper to form a new one and rearranging the skycrapers to be in hight order.

<img src="../../images/bulgarian-solitaire-03.png" width=350>

He continues rearranging each new city, following the same process, until he eventually builds a city which he has already seen.   
In our example, the sixth city he builds is then same as the second.

<img src="../../images/bulgarian-solitaire-04.png" width=350>

At this point, still dissatisfied with his work, King Kong gives up and leaves in search of new cities to rebuild.

In this example, the entire sequence of rebuilds creates 5 different cities.  
You should try starting with different arrangements of seven squares, what is the longest sequence of cities which you can find?

Do you notice any patterns or similarities between different starting cities (all made of 7 squares)? In particular, look at how the sequences end.

As an extention, try using different numbers of squares to build your original city. Try to answer questions like what is the longest sequence that you can create and can you spot a pattern for how the sequences end?

Try using 5 or 6 squares. These will have fewer possibilities for starting cities.

Try using 8, 9 or 10 squares. You will probably not want to consider every starting city for these (since there are a lot), but you may be able to spot some patterns particularly with regards to how the sequences end.
