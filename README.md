## Access Values in String
To access substrings, Use the square brakets for slicing along with the index or indices to obtain your substring.

```python
var = "Hello"

# Individual
string:			|	H	|	e	|	l	|	l	|	o	|
positive:		|	0	|	1	|	2	|	3	|	4	|
negative:		|	-5	|	-4	|	-3	|	-2	|	-1	|

# Consecutive
string:			|	H	|	e	|	l	|	l	|	o	|
index:			0		1		2		3		4		5
```

In case of printing consecutive characters, it needs to start with beginning index and colon, then ending index.

ex) print `"ello"` from `var`
> var[1:5]


