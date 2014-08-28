runSuite
========
A formal test suite to automate your testing. (Bash Script)

```
./runSuite suite-file program
```
For example:
t1.in (input), t1.args (arguments)
```
./runSuite t1 ./a.out
```

Result:
```
Test failed: t1
Input:
(contents of t1.in)
Expected:
(contents of t1.out)
Actual:
(contents of the actual program output)
```
