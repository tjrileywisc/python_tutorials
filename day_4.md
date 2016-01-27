##Python day 4 - adding strings
 
Let's do some work on strings (remember that ```"hello"``` is a string, as is ```'goodbye'```). 
Below, you can type in your first and last name instead of what is written below, if you like. 
If you use a non-English alphabet, just use the closest English language transliteration equivalent or you 
will run into a problem that we won't discuss until later.

``` 
first_name = "john"
last_name = "johnson"
 
print first_name
print last_name
```
 
That's all well and good, but what if we wanted them on the same line? Easy:
``` 
print first_name + last_name
``` 
 
 
 
I just 'added' two text strings together! Python has no problem with this at all.
 
Well there is a problem actually. No space between the words! That's easy to fix:

``` 
print first_name + " " + last_name
``` 
 
 
Note that you could have also just created a new variable, maybe ```full_name = first_name + " " + last_name``` if you wanted.
