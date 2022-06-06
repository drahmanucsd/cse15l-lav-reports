# Report 5
Dani Rahman

After saving the output from the given and my markdown parser java files and then use vimdim to then compare the whether or not the two files have any differences

The following is a screenshot of the differences, and can see that there are some differences in a couple of the outputs. I believe that the multiple dots means that there was some sort of error that occured when running the code.

![Image](https://github.com/drahmanucsd/cse15l-lav-reports/blob/main/Images/lab5-1.png?raw=true)

## Error with file 198.md
![Image](https://github.com/drahmanucsd/cse15l-lav-reports/blob/main/Images/lab5-2.png?raw=true)


The issue with my code is that my code doesn't contain any check for `:` and `/url` type urls, it only checks for parenthesies

As seen in the first image becuase my code doesn't catch for the lack of parenthethis it throws error here. When we look back to the vimdiff, the given markdown parse file also fails as it simply ignores the link. this means that it too doesn't have a clause to understand this type of linking. 

![Image](https://github.com/drahmanucsd/cse15l-lav-reports/blob/main/Images/lab5-3.png?raw=true)
## Error with file 202.md

![Image](https://github.com/drahmanucsd/cse15l-lav-reports/blob/main/Images/lab5-4.png?raw=true)
This is a simliar type of syntax to the one given in the previous file, however this time, there are quotes which change the name of the link wen hovered, and there is a incomplete link at the end as well.
![Image](https://github.com/drahmanucsd/cse15l-lav-reports/blob/main/Images/lab5-3.png?raw=true)
Because this is the same type of error, it is the same portion of code that is faulty, except this time there is also the handeling of incomplete links that needs to be taken care of. This will be handled in teh same location. The given markdown parser, again just like teh last test file doesn't throw an error, but doesn't produce the correct output, as it simply ignores the `:` version links and treats them as incomplete links, but the given markdown parser can handle such incomplete links.






