## Lists in Python

* As the name suggests, **List is an ordered sequence of data. In real life, if you could make a list of things that come to your mind** (or event for any specific purpose), it could be something like this –
  * Brush
  * Leuven
  * 48851964400
  * 3.14
  * Mom

* **Well, this is my list. You could make your own list & include whatever you want in it.** So, in my list, I have included what I do early in the morning, my city, my mobile number, the value of pi to two digits, and mom. It has different types of data – strings, float, and integer. 

* Well, this is the kind of flexibility Python List provides. It can hold elements of different data types. Declaring a List is fairly straightforward. You use square brackets (\[]) and separate the items by a comma. Let me write an example - \
  A = \["Brush", "Leuven", 48851964400, 3.14, "Mom"]

* **Lists are mutable.** Say if you want to change some item on a List, you can do that. For example, if I don’t like  ‘Brush’’, and want to replace this with ‘Morning Walk’, I can do it –
  \
  A = \["Morning Walk", "Leuven", 48851964400, 3.14, "Mom"] 
* Some **essential features** of Python lists are:
  * Collection of values
  * Can be of any data type
  * Can be a combination of different types

**Note:** The tutor in this video used python console. Nothing to worry here, you can use the same code and run it on Jupyter notebook too.













<iframe width="100%" height="315" src="https://www.youtube.com/embed/pP91kLR5cnE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>












## List Methods

### .append()

In Python, you can add values to the end of a list using the .append() method.




![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_9de3a07de4cf45c2a3d65b4c1fe1b8ff.png)




### .count()

The .count() Python list method searches a list for whatever search term it receives as an argument, then returns the number of matching entries found.

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_612831671f40406d81361012ce27ad7c.png)

### len()

The Python len() function can be used to determine the number of items found in the list it accepts as an argument.

 ![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_6a7d4632b13d4094b60c1b47d95a72b6.png)

### .sort()

The .sort() Python list method will sort the contents of whatever list it is called on. Numerical lists will be sorted in ascending order, and lists of Strings will be sorted into alphabetical order. It modifies the original list, and has no return value.





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_ac2c7dda3ded46128f39d9040d58efe2.png)




* List Methods Cheat Sheet:  
https://www.codecademy.com/learn/learn-python-3/modules/learn-python3-lists/cheatsheet
* To learn more about lists, visit:  
https://www.w3schools.com/python/python_lists.asp

## Tuples

* Tuple is also an ordered sequence of items as List. Tuple also holds multiple data types.
* The only difference in Tuple & List is that Tuple is immutable; once created it cannot be changed.

* Creating a tuple is as simple as putting different comma-separated values within round brackets.

* Example: A = (‘Brush’, ‘Leuven’, 48851964400, 3.14, ‘Mom’)

**Note:** The tutor in this video used python console. Nothing to worry here, you can use the same code and run it on jupyter notebook too.
















<iframe width="560" height="315" src="https://www.youtube.com/embed/XQOWZidQSnE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>








* To learn more about tuples, visit:  
https://www.w3schools.com/python/python_tuples.asp

## Dictionary

* Dictionary is an unordered collection of key-value pairs.
* Real word dictionaries are a good analogy to understand them: they contain a list of items(words), and each item has a key(the word) and a value(the word’s meaning).

* It generally is used when we have a huge amount of data.
* It is defined within braces, with each item being in the form of key: value pair. Syntax –  
  ``` 
  my_dict = {
  "key1":"value1",
  "key2":"value2",
  }
  ```


### Tutorial on Dictionaries

For the time being, ignore the video after 4 minutes and 18 seconds. Don’t worry if you don’t understand the topics after 4 minutes and 18 seconds. You will learn that soon.











<iframe width="560" height="315" src="https://www.youtube.com/embed/ZEZdys-fHDw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>












* The keys in a dictionary must always be unique and immutable. This is the reason dictionary keys can be String but not List.

* On the other hand, Values in a dictionary can be of any datatype and can be duplicated.

* Dictionary keys are case sensitive; same name but different cases of Key will be treated distinctly.

* Example:




![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_905c3c070c4b458e86b326755bd78eed.png)