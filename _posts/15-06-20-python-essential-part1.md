---
layout: post
author: Girish Ramnani
category:
 - python
 - essentials

---

This is the tutorial series for python which will contain essentail parts of the language.
So lets begin.

Python is a **weakly** typed programming language, that means you dont need to declare the data type of any variables.

## The fundamentals

The variables 

{% highlight python %}

i = 5  #integer

j = 5.5 #float

k = "i love python" #string

li = [1,2,3,4,5] # array or known as list in python

{% endhighlight %}

Basic input output

{% highlight python %}

print("hello world") # prints hello world and goes to the next line

word = input("enter a number") # takes input from the user ,and storing it into the word as a string

type(word)  # string. 

#to convert the word into other types

int_word = int(word)

float_word = float(word)

list_word = list(word)  #but be aware if the you try to convert string to an int, it would give an error

str_word = str(word)
 
 {% endhighlight %}


