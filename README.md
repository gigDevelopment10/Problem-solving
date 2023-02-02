<h1> Competitive coading with python </h1>

**1. Check the recurision limit in python**
```
import sys
print(sys.getrecursionlimit())
```

**2. Subarray , substring, subsequence, subset** 
<br>
-> Subarray - Contigious block of memory <br>
-> Substring - Contigious block of string <br>
-> Subsequence - Sequence derieved from other sequence by ading or deleting elements but without changing the order <br>
-> Subset -  Any possible combination of the original set. It does not maintan the relative order of the string <br>

**3. Matrix resizing**
<br>
2-d array to 1-d: M[i][j]=M[n*i+j] , where n is the number of cols. This is the one way of converting 2-d indices into one 1-d index. 

1-d array to 2-d: M[i] => M[i/n][i%n] convert 1d to 2d.
