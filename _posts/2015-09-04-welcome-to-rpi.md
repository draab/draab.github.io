---
layout:     post
title:      Starting Off My RPI Career
date:       2015-09-28 23:00
summary:    The beginning of the great adventure known as college.
categories: school, job, professional
---

I realize that this blog has been a little derelict in the past months. I have grand plans to change that now with the upcoming school year. I am a freshman at RPI intent on increasing my experience coding projects.
RPI has a lot of opportunities in that regard and I am excited to be able to take advantage of them. Just to show I am serious, below is my example to a solution to the fizzbuzz problem using python.


for x in range(1,100):
    if x%3 == 0 and x%15 != 0:
        print 'fizz'
    if x%5 == 0 and x%15 != 0:
        print 'buzz'
    if x%15 == 0:
        print 'fizzbuzz'
    if x%3 != 0 and x%5 != 0 and x%15 != 0:
        print x
