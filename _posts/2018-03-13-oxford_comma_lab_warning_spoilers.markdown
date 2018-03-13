---
layout: post
title:      "Oxford Comma Lab(Warning:Spoilers)"
date:       2018-03-13 09:01:09 +0000
permalink:  oxford_comma_lab_warning_spoilers
---

"Warning, the following contains spoilers for this lab.
I want to take this lab to discuss the process I took for this lab. The ReadMe file indicated that this would be a challenging lab and I will certaintly agree that it was challenging. Despite this, it went by pretty smoothly."

"The idea of the lab was to create a method that would take in an array of words and correctly use commas and the oxford comma for the list. For example an array of ["hippo","giraffe","monkey"] would become "hippo,giraffe, and monkey". One thing to remember from English class is that there is no comma between a list of two so ["hippo","monkey"] should just be "hippo and monkey". To accomplish this, I knew that I would have to make a separate condition for this so I used array.count as my condition for my if/else statement in this method. So if the count was equal to two then I just simply joined the two with "and". In cases where it was greater than two, that is when we want to use the oxford comma."

"There may have been some simpler ways to do this lab that I could have used, but the approach I took was to define the last two elements in each array and store them into variables. 'Last' was the variable I used to store the integer for the last index value of the array. For example, if the array had four elements, last would equal four. 'Comma' was the next one used to identify the second to last value. I stored these for another if/else statement that I am about to explain.
So with these variables ready to go, it's time for some iteration. But, in order to use these variables, I had to have the index value for each element; for this, I used the eachwithindex. I then took the index value and compared it with the two variables. 'Comma' is the second to last value so I wanted to use this one to specify where the ", and " goes when joining the elements. I also had to define the last element so I could make sure it does not get a comma. Then for every other element, it gets a ", ".  In that each iteration, I would shovel these into a new array I called 'fruit'. Once the array was done, I joined all of these together with a "" so that nothing extra was added."
