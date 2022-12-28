# Console - Finances

## Task

The task was to write JavaScript code that analyzes the records to calculate each of the following:

* The total number of months included in the dataset.

* The net total amount of Profit/Losses over the entire period.

* The average of the **changes** in Profit/Losses over the entire period.
  * You will need to track what the total change in profits are from month to month and then find the average.
  * (`Total/Number of months`)

* The greatest increase in profits (date and amount) over the entire period.

* The greatest decrease in losses (date and amount) over the entire period.

## Solution

This was a nice little challenge with a for loop. One of the tasks is a little bit misleading as you don't need to track changes on a month to month basis - you don't need a computer for this task at all as you only need to find the difference between the first and last month and divide it by number of months minus 1 (not the number of months!). No need to use a brute force with a mistake in it when the solution is smiling at you from the screen.
I've populated the DOM with a graph and the result just so the page doesn't look so empty.