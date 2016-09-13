#Variables
* You can assign variables by typing ```variable == 1``` or ```variable == "string"``` 
* You can attach variables to anything like integers or strings
* The word variable can be replaced with anything that you would like to help you code

* To use variables you can ```print variable```
* The code should output ```1``` or ```string```

* There are also different types of variables such as 

```
float(x)   # This converts x to a floating-point number
str(x)	   # This converts x to a string representation
repr(x)    # This convers x to an expression string
```

#Conditionals
* ```if-statements``` create a "branch" in the code
* You can do something like a choose your own adventure type of thing
* Or you can just plug in variables and see the results


* For Example 
```
hunter = 100
harrison = 3
ben = 50 

if hunter > harrison
	print "Hunter is cooler than Harrison"
if ben > harrison 
	print "Ben is cooler than Harrison"
if hunter > ben
	print "Hunter is cooler than Ben"
```

##What you should see
```
Hunter is cooler than Harrison
Ben is cooler than Harrison
Hunter is cooler than Ben
```
 

#Functions
* Functions begin with the keyword ```def``` by the functions name and then parantheses ```()```
* Use ```if-statements``` to solve the problem at hand 

###Problem
```
has_teen

A number is a teen if it is in the range 13 to 19 inclusive. Given three integers, return true if any of them are a teen.
```
###Answer
```
def has_teen(a,b,c):
	if a >= 13 and a <= 19 or b >= 13 and b <= 19 or c >= 13 and c <= 19:
		return True
	else:
		return False


print has_teen (43, 54, 15) # Expect True
print has_teen (73, 14, 5) # Expect True
print has_teen (13, 24, 8) # Expect True
print has_teen (173, 24, 8) # Expect False
```

##What you should see
```
True
True
True
True
False
```