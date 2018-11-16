---
layout: post
title: Jackson Earle, Reflection Week Eight and Nine
date: 2018-11-15
---
These past 2 weeks we have been learning more in depth about tables and what we can do with them. We had a variety of topics for each day, in order they are Into Structs, Data Definitions, Designing Functions with Examples, Filtering tables and Asking Questions with Data. With the main topic we learned being data tables we also learned about data abstractions which are the base of everything, such as contracts and the data-type contract we used for CakeTypes. The example tells us essential pieces of data. A time we used it was when we wanted to get the number of layes out of a cake, so we had to put the name of the function that shows the data-type we wanted to use. The contract for the data-type is: 

data CakeType:
  | cake(
      flavor      :: String,
      layers      :: Number,
      is-iceCream :: Boolean)
end
 
 An example of one of the cakes is birthday-cake and put then we need to put .layers at the end to tell the function that we want to take out the layers section of the contract out, and then tell us what it is when we put birthday-cake.layers. So for this because the birthday-cake function was this: 
 
 birthday-cake = cake("Vanilla", 4, false)
 
so then in the interactions area it would show the number 4 because that is the amount of layers the fucntion birthday-cake has.

A question that was asked this week is what data int
