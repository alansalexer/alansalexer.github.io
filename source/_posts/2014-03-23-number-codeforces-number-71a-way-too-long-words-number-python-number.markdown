---
layout: post
title: "#CODEFORCES#71A_Way_Too_Long_Words#Python#"
date: 2014-03-23 20:54:15 +0800
comments: true
categories: 
---
#PYTHON Solution: CF 71A

```python
for i in range(input()):
	s=raw_input()
	if len(s)>10:
		s=s[0]+str(len(s)-2)+s[-1]
	print s
```

This is actually a very basic and simple solution, here we can summarize what we learn from this solution as a beginner:

* `input()` for reading the first line of input which means the total number of test cases and treat it as integer.  
* `range()` as loop times,
* `raw_input()` for reading input test cases.
* `str(len())` for concatencating integers with strings.
* `s[-1]` as the last character of the string.

