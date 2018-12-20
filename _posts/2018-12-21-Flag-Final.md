---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of Tunisia by Jackson Earle

## Describe your program

The countries I had the option to design were Greece and Tunisia, I chose Tunisia to be my flag because I made it earlier this year so I thought it would be rather simple.


I expect to get a professional because I made a scalable representation of the Tunisian flag before the due date. Then explained the questions in detail.

## Current output



* * *
![MY FLAG](/images/flag-final.png)
* * *

## Describe your process.

Some of the strategies I had that helped me seriously was organizing the code to be something understandable to my eyes, my partner Marlon helped me with how to layer the flag in more simple way than using underlay-xy, he showed me that place-image was much easier for placing images on top of each other, which was what I needed at the time. Then the biggest issue was to find a flag construction that I could understand enough to use. This helped me with most of my other issues such as circle radius and how to do that because I used the radius of the circle for the circles and star as well.


## Explain your code.

* * *
```
size = 100

width = size * 3

height = size * 2

circle-r = height / 4
```

* * *
Each part of the code held some significant value. The size was the only number by itself in the whole program. The width, height and size is what I used to measure the whole construction. Everything in my code is from these 4 lines, then with the original pieces added with a tad more detail it makes up my program


This is what was the basis of my code, it made everything else I used. The size function was used in every single line of code one way or another. For example when doing the circles and star I used the height and divided that by 4 to get the radius. From there I multiplied and divided by the needed amount to get the number I actually needed just by using 1 line of code. So with a single line of code I could do so much more than I origonally could .


## Program code

```
include image

size = 50
width = size * 3
height = size * 2

base = rectangle(width, height, "solid", "red")

circle-r = height / 4

half-height = height / 2
half-width = width / 2

wc1 = circle(circle-r,"solid","white")
wc1f = place-image(wc1, half-width, half-height, base)

rc = circle(circle-r * 0.75, "solid", "red")
rcf = place-image(rc, half-width, half-height, wc1f)

wc2 = circle(circle-r * 0.6, "solid", "white")
wc2f = place-image(wc2, half-width * 1.07, half-height, rcf)

rs = star(circle-r * 0.55, "solid", "red")
rsf =  place-image(rotate(20, rs), half-width * 1.07, half-height, wc2f)


```
