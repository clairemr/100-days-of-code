# #100DaysOfCode Log - Round 1 - [Your Name Here]

The log of my #100DaysOfCode challenge. Started on Monday 6th April, 2020. 

## Log

### R1D1 
Set up GitHub repository, Visual Studio and learned how to stage, commit and push changes to repo.
Started following tutorial on memory game. 
JS script needs to be at the end of the page

### R1D2
Finished first version of memory game, pretty happy with the basic concept
Still want to add a restart game button and a win message
Got stuck for a bit because I didn't realise Javascript doesn't load in order, so the timeout was messing me up

### R1D3
Started a new JS game that I'm building without a tutorial. Definitely much slower this way, but I'm finding out which bits I actually know
Built up to the first loop checking whether blocks in the same row that touch are all the same colour, for loop is getting stuck halfway through

### R1D4
Fixed the for loop issue - use let variables and deleted the return that was breaking the loop
Extended match function to also check columns
Spent most of today trying to get the blocks to display properly, can't find a CSS float that pulls them to the bottom
Decided to switch tactics and just swap colours on existing divs, then hide the top one - finishing that will be tomorrow's project

### R1D5
Fixed the colour swapping for the top blocks of the column
Still having issues with the bottom block of the column not disappearing reliably or changing the colours so they don't match properly - tomorrow I'll build a proper check for whether a block is the last one in the column

### R1D6
Fixed colour matching - sort() function needed to know what to sort by (div id)
Updated CSS to have 10x12 grid and percentages, instead of fixed px. Might change back though
Updated scoring system to include bonuses, and show on the screen
Tomorrow: minimise empty columns to pull them together

### R1D7
Started playing with pulling columns together, didn't work the way I was hoping it would. Will come back to it tomorrow

### R1D8
Converted game to table to avoid rearranging when shrinking columns
Finished pulling columns together. Main game play is now finished, tomorrow I'll update scoring and add reset game & continue buttons. Potentially different levels and sizes

### R1D9
Added reload buttons and levels
Next session need to lastrow which isn't updating properly so shrink columns has issues in higher levels