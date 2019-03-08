---
layout: post
title: "Video Game - Final Submission"
date: 2019-03-08
---


Justin O’Reilly
https://www.wescheme.org/view?publicId=YpUuXL3LFz
Game Title: 
MARIO 100BC
Describe your game, characters and setting: 
My game is about Mario and him battling ghost and gumba
Choose one of either the onscreen?, update-player, distance, or collide? functions. Copy and paste the entire function including contract, purpose statement, examples and definition. 
; onscreen? : Number -> Boolean
; Determines if the coordinate is on the screen

;; EXAMPLE:
(define(onscreen? x)
  (and (safe-left? x)(safe-right? x)))





Describe every line in the pasted code above.
;onscreen? : number -> boolean: means what is the contract onscreen supposed to take and what is supposed to produce.
(define(onscreen? x): this line means that they are defining onscreen.
(and(safe-left? x)(safe-right? x))): this lines means that they are combining safe-left and safe-right so there is movement from left to right or right to left.


