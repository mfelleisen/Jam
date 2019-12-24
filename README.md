## The Jam Language Design 

This repository records some initial notes from the very beginning of the
TeachScheme!/PLT Scheme project. The files listed below are notes that
Bruce Duba, Shriram Krishnamurthi, or I took after design meetings or after
reflecting on design meetings. 

```
matthias% ls -l 
total 136
-rw-r--r--  1 matthias  staff   759 Mar 29  1995 INDENTATION
-rw-r--r--  1 matthias  staff   377 Mar 29  1995 INTERACTION
-rw-r--r--  1 matthias  staff  1684 Mar  9  1995 LIST
-rw-r--r--  1 matthias  staff    35 Aug 29  1995 TODO
-rw-r--r--  1 matthias  staff  1438 Feb 23  1995 ex1
-rw-r--r--  1 matthias  staff   843 Feb  2  1995 syntax.txt
-rw-r--r--  1 matthias  staff  2340 Mar 27  1995 syntax10
-rw-r--r--  1 matthias  staff  1749 Mar 30  1995 syntax11
-rw-r--r--  1 matthias  staff  1516 Apr 17  1995 syntax12
-rw-r--r--  1 matthias  staff   986 Feb 17  1995 syntax2.txt
-rw-r--r--  1 matthias  staff  1235 Feb 18  1995 syntax3
-rw-r--r--  1 matthias  staff  2250 Feb 20  1995 syntax4
-rw-r--r--  1 matthias  staff  2057 Feb 23  1995 syntax5
-rw-r--r--  1 matthias  staff  2527 Feb 27  1995 syntax6
-rw-r--r--  1 matthias  staff  2142 Mar  2  1995 syntax7
-rw-r--r--  1 matthias  staff  2583 Mar  2  1995 syntax8
-rw-r--r--  1 matthias  staff  2205 Mar 27  1995 syntax9
```

The meetings started way before this, but unfortunately there were no cell
phones to take picture of blackboard designs, the paper designs are lost,
the arguments and design rationales were oral, so this is what we got. 

As for the actual date, here is an email that I recently sent to Matthew,
Robby, Jay, and Sam. 

"So here is my calculation of dating Racket neé PLT Scheme to 28 January 1995. 

Wednesday 25 January 1995 

POPL used to be a Monday thru Wednesday noon affair. Cormac presented his
future paper there (a static analysis on how to eliminate implicit touch
operations; we also had the infamous Felleisen-Wadler paper there) and we
were flying back from SFO to IAH, arriving quite late that day. I got home
and sent email that we’d have a meeting next morning.  

Thursday 26 January 1995 

We all met in Corky’s office because it was bigger than mine. I announced
that I wanted to leave theory behind and build a curriculum and the
language and the support software to use FP to teach math-y and
programming-y thingies across the curriculum in pre-college. Shriram
clearly embraced the idea, Corky thought I was borderline. Bruce loved the
chance to design a new language. We discussed for quite a while and came to
two conclusions: the PhD students needed to focus on sw issues for
dissertations in case we'd fail (Corky was sure we would and indicated he
didn’t really want to go along) and Bruce and I would focus on the language
and the curriculum. Bruce and I discussed this more and came to the
conclusion that we needed a notation that was close to text books.  

Friday 27 January 1995 

We met again after my lecture (PL) and started sketching out this plan to
everyone. We didn’t know how to make graphs and certain symbols (like
integration, unicode was not on our horizon) and discussed how we’d go
about the software dev tasks (as in we study SE techniques while doing our
development; my only idea at the time to get dissertations).  

Bruce and I started designing Jam (which is where the name Jam 2000 came
from for the machine simulator I taught next fall in 210.)  

Saturday 28 January 1995 

A few weeks later Matthew showed me mzscheme/mred and told me has “cobbled
it together over the weekend”. I am sure he didn’t use “cobble” but
something close.  

Ergo, this is the birthday .. in my mind. 

... 

Everything like this is a “founding myth.” All I am pretty sure about is
that the first key strokes of conception probably took place on that day
(cross-producting my memory with my understanding of Matthew). "
