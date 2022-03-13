### Lab report 5: Commonmark-spec

In this lab report, I am going to show *two* different tests that gave different outputs than that of our implementation.

## Explain
- *How you found the tests with different results (Did you use diff on the results of running a bash for loop? Did you search through manually? Did you use some other programmatic idea?)*

In our lab, we used the command below to compare the given tests. 

'''
` $ diff markdownparse1/myresults.txt markdownparse2/results.txt`
'''

## 22.md

The file contains the following:

```

[foo](/bar\* "ti\*tle")

```

