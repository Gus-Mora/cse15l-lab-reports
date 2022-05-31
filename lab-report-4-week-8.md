# Lab Report 4 Week 8

## Reposotories 
[My repository](https://github.com/Gus-Mora/markdown-parser)
[Repository of Group We Reviewed](https://github.com/kaileywong/markdown-parser)
________
## Expected Outcomes of Snippets
Using the [CommonMark demo site](https://spec.commonmark.org/dingus/) here are the expected results for the snippets 
### Snippet 1
![snipex3](snipex1.png)
### Snippet 2
![snipex2](snipex2.png)
### Snippet 3
![snipex3](snipex3.png)
_________
## Created Tests
![tests](testl4.png)
_________
## Outcomes for My Reposotory
![myoutcome](outcomem.png)
The three tests failed shown above with the tests for Snippet 1,2 and 3 all failing. The expected outcomes were different than the result so this resulted in the tests failing. 
## Outcomes for Repository of Group We Reviewed
![theiroutcome](revoutcome.png)
Much like my code, the tests for the group we reviewed also failed. This is shown again by the tests for Snippet 1,2 and 3 all failing as shown above. 
______
## Potential Fixes 
### Fix for Snippet 1
Yes, I believe that there is a fix to this issue with less than ten lines. The main issue that causes problems in this snippet is the inclusion of ` in the phrases. I believe that the code change for this would be to check if there are backticks before or after any parenthesis or brackets. The information for that is already found with the code so seeing if it still formatted correctly in addition to the backticks. 
### Fix for Snippet 2
I think that the fix for this would also be less than ten lines in length. That is because all we are checking is for nested values of the parenthesis or bracket. I believe that the code change would just to be to look for the largest and smallest index of both parenthesis and bracket as those would always be the first and last. This would avoid the nested parenthesis and brackets within the links format.
### Fix for Snippet 3
I do not hvae the best idea of how to go about fixing the output for the third snippet. I think that it could be done in under 10 lines or maybe more. I think that the code change would have to take into account that the links might be more than one line long or even not have an ending parenthesis or bracket. The random addition of text also makes it somewhat difficult to understand what fixes would be necessary here. 