# SSD Assignment 1


## Question 1

### a
* omitted the blank lines using -v option in grep
* written in quotes.txt

### b
* Replaced the -- with -. We can do this for every non alphabetic character. 
* Sorted the modified quotes and removed duplicates(considering case insensitive).
* Written in quotes_rdup.txt

### c
* from the b part file we consider everything in a line after ~ using cut command
* omitted the space, if there was some in the starting of the name of the personality using sed
* sorted the personality names and chosen the unique ones with their count.
* since the prefix count puts a tab in the front, we replace that by using sed again with a single space.
* extracted the columns using awk and put it in quotes_byperson.txt

### d
* chosen all the words starting with 's' using grep
* omitted those which had 'a' as the second character. 
* sorted and printed the unique ones.