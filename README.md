# UOCIS322 - Project 5 #
Brevet time calculator with AJAX and MongoDB!

Author: Alexa Roskowski
Date: May 23, 2021

## Overview

This code should open a website that will calculate the brevet times for 
certain control distance races. There are a lot of rules for calculating thses
brevet times that are coded into. Basically people will bike to try to reach
certain check points during a window. The open and close times have VERY 
specific rules to calculate them. Most simply there is a table at 
https://rusa.org/pages/acp-brevet-control-times-calculator that gives the 
simple overview of how this works. If the last checkpoint or the finish line 
is less than 20% of the brevet distance then you just calculate it as if it was 
just the brevet Some of the brevets have specific closing times --> those are 
on wikepedia so. Please note that when your doing the math for anything more 
than 200 then you have to do the math based on the time previously.


this also should have a submit and display button, where the submit button will
put the brevet distances, open times, and close times in a Mongo database.
 Which display will use to show the brevet distances and times. After you
press the submit button the page will reload and clear your entries. 


## note
I got this to work on 5/24/2021 :)
