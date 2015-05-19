R-Tutorial: 1
======
author: Murali
date: 19/May/2015
transition: concave
transition-speed: slow
incremental: true


R-Tutorial-1: Intro
=======
transition: zoom


- Open source/Free
- [Download it from] (http://cran.r-project.org/)


R-Tutorial-1: R a calculator...
====

```r
2 + 2
```

```
[1] 4
```

```r
4 * 5
```

```
[1] 20
```

```r
10^2
```

```
[1] 100
```

```r
(5+5)*4
```

```
[1] 40
```

R-Tutorial-1: R a calculator
========


```r
# 2-9
```

```r
a=10
```

```r
b=110
```

```r
a*b
```

```
[1] 1100
```

R-Tutorial-1: R workspce
========
- When you create a variable or (a variable type) an object in R it stored in your *workspace*
- To get the objects in the worspace, use the command:

```r
ls()
```

```
[1] "a" "b"
```
- To remove an object, say 'b', from *workspace*:

```r
rm(b)
```

- Now the remaining objects

```r
ls()
```

```
[1] "a"
```

R-Tutorial-1: R workspce
=====
- To remove all the objects from the *workspace*, use the command:

```r
rm(list=ls())
```
- Now the remaining objects

```r
ls()
```

```
character(0)
```

R-Tutorial-1
## will continue....

