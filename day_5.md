#Python Day 5 - string modification
 
Let's modify strings. First, replace:
```
mystring = "Hello"
 
mystring = mystring.replace("e", "a")
 
print mystring
``` 
 
 
 
 
And now your program is speaking German to you, or at least this one word. 
This ```variable.method()``` pattern is going to appear a lot. The method (or function if you like) is 
modfiying the variable (which is technically an object). For now, just take this as given until a more detailed lesson later.
 
Try this:
``` 
shouting = "WHY ARE YOU SHOUTING AT ME?"
 
quiet_down = shouting.lower()
 
print quiet_down
``` 

 
 
So that's how you can set a string to all lowercase.
 
How do you set it to uppercase? Here's your first chance to look in the python docs. You'll do a lot of this in the future, 
but this time I'll point you to the correct page to start you off.  
https://docs.python.org/2/library/string.html
 
So you probably saw something like ```string.upper()```. Here ```string``` is a generic placeholder for the string variable. 
You might use case changes if you need to look in a string (maybe using ```string.find()```) to look for something in the string, but you aren’t certain of the case of the letters. 
The text you want to find might be at the beginning of a sentence, for example. If your string to find is 'mystring' and you are looking in

```
search_in = "Mystring starts with a capital letter"
```
then it will fail because technically ```"mystring"``` isn't in ```search_in```. 
If you run search_in.lower() and use ```find()``` on that, you'll see your string in there.

Above, we used ```mystring.replace()``` and ```shouting.lower()```. You can use ```replace()``` and ```lower()``` on any string object.
We'll talk about objects much later.
