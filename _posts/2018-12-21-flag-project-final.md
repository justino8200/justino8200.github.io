---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of Puerto Rico by Justin O'Reilly

## Describe your program

I designed for Puerto Rico and I expect an practitioner or apprentice.

## Current output



* * *
![Flag](/images/final-flag.png)
* * *

## Describe your process.



I got help from one of my peers that is not in my class but in my advisory. He guided me into programming the flag and making it straight with no incorrect codes.


## Explain your code.



* * *
```
(define TRIANGLEPART2(rotate Cuba TRIANGLEPART)) In this section I am programming the triangle to be rotated to it side so I can put the star-polygon inside.
(define STARPART(star-polygon (* size 14) size 2 "solid" "white")) I am programming the Star-polygon 
(define LINEBASE (put-image LINE height (* size 42) FLAG)) Fixing the lines to be straight and in the right position 
(define LINE2BASE (put-image LINE height (* size 18) LINEBASE))Fixing the lines to be straight and in the right position
(define TRIANGLEBASE (put-image TRIANGLEPART2 (* size 25) (* size 30) LINE2BASE)) Inserting the triangle inside the rectangle so I can the put the Star-polygon inside.
```

* * *



 



## Program code

```
(define size 5)
(define Width (* size 120))
(define height (* size 60))
(define FLAG(rectangle Width height "solid" "blue"))
(define stripeheight (* size 12))
(define LINE (rectangle Width stripeheight "solid" "white" ))
(define TRIANGLEPART(triangle height "solid" "red"))
(define Cuba 270)
(define TRIANGLEPART2(rotate Cuba TRIANGLEPART))
(define STARPART(star-polygon (* size 14) size 2 "solid" "white"))


(define LINEBASE (put-image LINE height (* size 42) FLAG))
(define LINE2BASE (put-image LINE height (* size 18) LINEBASE))
(define TRIANGLEBASE (put-image TRIANGLEPART2 (* size 25) (* size 30) LINE2BASE))
(define STARBASE (put-image STARPART (* size 17) (* size 30) TRIANGLEBASE))
STARBASE
```
