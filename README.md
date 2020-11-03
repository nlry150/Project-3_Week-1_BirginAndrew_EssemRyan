# Project-3_Week-1-BirginAndrew_EssemRyan
## SUMMARIZING OUR APPROACH TO THE PROBLEM
###### Step 1
For this step, I would create a system where user actions with logging in and out of the system are counted.
Given that the first thing I should be checking for is whether or not ligin activity is enough to warrant suspicious activities (more than 5 logins to any of the systems in a given day).
  To accomplish this, I would need to set a **count of logins** variable that is initially equal to zero, and counts the amount of times a user logs in to the system in a given day, with that counter reseting every day to zero.
      It would be necessary to use the .count() data structure for this section - I would need to assign the data structure so that it recognizes when a specific user logs in, and when they log out, and count that as one iteration for that occurence.
I feel as though it would be easier to utilize a while loop that emphasizes that there isn't suspicious activity until any given user has logged in more than 5 times throughout any given day.
###### Step 2
Define the step using **def behavior()** - Might be able to utilize steps 2 and 3 similar to encode() and decode() in project 2.
I would create a **for** loop that checks whether the user's successful login attempts are greater than the amount of times they log out (they should be equal in order to avoid irresponsible behavior). 
There would have to be a count of irresponsible behavior for each user that relates to the amount of times they logged in more than they logged out for a given day.
I could use the .append() data structure, using this could keep track of the days where login>logout.
###### Step 3
**def glitch()** - define the step as a function like step 2.
For the System glitch step, I think it would work similarly to the encode() and decode() functions from the hangman project - since **System Glitches** are defined as being logout attempts being greater than login attempts, it would make sense to reverse the code for Irresponsible behavior - and define it as a new function.
This step would follow similar code to step 2, but in reverse terms.
###### Step 4
I would count the number of unique domains using '.' as the argument for what determines a new domain. 
It would be useful to set up a count structure. Additionaly, I would have a **for** loop that iterates through a specific domain in the list of domains, and add 1 to the value of domains if it isn't the exact same as the domain that it is being checked against.
###### Additional Comments on Approach:
Counting variables for each step would have to be different in order to iterate them through the requirements mentioned in each step (use different variable names accordingly).


## Updates
### November 3rd, 2020

We've made progress in successfully reading the "userlog" file properly, displaying every user's email address, time and date accessed,
their login/logout activity and the server accessed.

The process was fairly simple and it was nice to look use EC8 as reference because we utilized skills very similar to it.

As it pertains with proceeding with the actual bulk of the project, we are sure we'll run into some difficulties.
If and when we face any obstacles while conducting the project, we'll make sure to list them down.

We havent started coding the rest of the project, however an update with obstacles faced will be coming very soon as this project involves
lots of time and effort on it and it won't treat us very nicely if we worked on it due date to due date.
