##Python day 3 - variables
 
Let's create your first variable.
 
Type the following into the python interpreter:
 
```var1 = "my first variable"```
 
Now type the following:
 
```print var1```
 
You should see the following:
 
 
 
 
 
Note that you could have written this: 
 
```print "my first variable"```
 
But then you don't have the advantage of being able to change ```var1``` by other means (hence the name 'variable'). 
This will be more clear in a minute.
 
Now create these variables:

```
var2 = 1
var3 = 2
```

And print this out:

``` 
print var2 + var3
```

You should see this, and hopefully you're not surpised by the result:
 
 
 
 
Now try this:
``` 
var2 = var2 + 3
``` 
The right side of the = is handled first before assigning to the left side. So if you do this:

```
print var2
```

Do you get the expected value of 4? If so, good, you should have a good handle on simple addition of variables. Now you can
use python as a simple calculator.
