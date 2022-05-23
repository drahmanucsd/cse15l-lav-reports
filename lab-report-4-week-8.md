# Report 4
Dani Rahman
## Markdown-Parse Repository Link:
The following is my markdown-parser reposity
[Link](https://github.com/drahmanucsd/markdown-parser.git)

The folling is week 7 lab markdown-parser reposity
[Link](https://github.com/nathom/markdown-parser)

## Expected Outputs:
Snipet 1: ["`google.com", "google.com","ucsd.edu"]

Snipet 2: ["a.com","a.com(())","example.com"]

Snipet 3: ["https://www.twitter.com","https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule","https://cse.ucsd.edu/"]
## Running Snippet tests
Errors for the other persons markdown parser

![Image](https://github.com/drahmanucsd/cse15l-lav-reports/blob/main/Images/lab4-1.png?raw=true)
![Image](https://github.com/drahmanucsd/cse15l-lav-reports/blob/main/Images/lab4-2.png?raw=true)
![Image](https://github.com/drahmanucsd/cse15l-lav-reports/blob/main/Images/lab4-3.png?raw=true)

Errors for my markdown parser
![Image](https://github.com/drahmanucsd/cse15l-lav-reports/blob/main/Images/lab4-4.png?raw=true)
![Image](https://github.com/drahmanucsd/cse15l-lav-reports/blob/main/Images/lab4-5.png?raw=true)
![Image](https://github.com/drahmanucsd/cse15l-lav-reports/blob/main/Images/lab4-6.png?raw=true)

## Errors
Since both the lab 7 person and I had the same problems for all 3 snippets, I will just mention them together:

Snippet 1:

This error is due to this implementation not considering the effect of `'` and `"` on links

Snippet 2:

The code did not handle the extra paren. The code simply ignored it. 

Snippet 3:

Neither of our code cannot handle the fact that there is a missing close parenth, but the other persons cod was able to understand that athe re was a space in the end of the link, and not adding it to the end of the link, but my implementation added the whitespace which is incorrect

## Fixes:
For the first snippet is would take 10-20 lines of code to fix, would index all the open and closign `'` in order to see the correct links

For the second snippet it would ~20 lines of code in order to add a trackr that would observe and record any nested parens within the given link

For the third snippet would require 20 lines of code to fix. For mine I need to implement the white space detection as my partner had, and for in order to handle the fact that there is no close parent could add within a couple lines to check after a certain lenght of number of `\n`'s to end the link
