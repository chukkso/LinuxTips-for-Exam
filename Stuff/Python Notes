## Lecture: Data Types - Strings and Numbers

https://www.tutorialspoint.com/python/python_basic_operators.htm
https://www.learnpython.org/en/Loops


Strings can be single quotes or double quotes 'that' or "that" in  the python repl ( read -evaluate-print loop)
 a string is an object and you can call methods on it..methods are  functions that are attached to objects .
This string type has a method called find

'this'
>>> "double".find('b')
3

Stings are 0 indexed that is count starting from 0 so above finding the letter b was 3 indexes

Another method called lower makes caps or lower case items from random e.g

>>> 'tereasdfasdASDfASdf'.lower()
'tereasdfasdasdfasdf'

Numbers = 2 types
integers e.g 4 and floats( decimals) e.g 4.2
You can cast from int to float and or from float to string
Int ()
Float()
String() built in types for makign standard an integer , float or string  -- all from, built in.

## Lecture: Data Types - Booleans and None
Booleans represent truth while none represents not true in python its True or False
You can cast things to boolean too e.g 
>>> bool('3')      #putting a sting in the bool function
True
>>> bool(0)    # a bool(o) is always false
False

>>> None
>>>  # this evaluates to nothing and returns nothing


## Lecture: Data Types - Strings and Numbers

String has some functionality' and so you can methods on it since a string is an OBJECT . METHODS are functions that are attached to an object
E.g sting


#!/usr/bin/python
counter = 100          # An integer assignment
miles   = 1000.0       # A floating point
name    = "John"       # A string
print counter
print miles
print name

mething
Find ( ) method can be attached to string e.g

>>> "double".find("bl")
3

>>> "double".find("e")
5

Lower method make all lowercases in a string

>>> 'TestiNG'.lower()
'testing'
** u cant change a string you can create a new one

Escape characters for delimiting
-t is tab dlimited
>>> print("Tab\tDelimited").
Tab        Delimited

-n new line
>>> print("Tab\nDelimited")
Tab
Delimited
Stings can exisist with single quotes or doulble but myst finish with the same and not the other

>>> print(""Double" in Double")
  File "<stdin>", line 1
    print(""Double" in Double")
                 ^
SyntaxError: invalid syntax
because "" means space or empty so you must delimite the extra " to show the other one so

>>> print("\"Double\" in Double")
"Double" in Double.
NUMBERS
Integers and floats integers = 1, 2,e.tc. Floats are 5.4 , or 2.2

·         When do math between and integer and float you will always get a float as answer but when do math with integer and integer you will always get an integer e.g

>>> 5/3
1
>>> 5.0/3
1.6666666666666667
>>>


Convert an float into an integer
>>> int("23")
23
>>> float("23")
23.0

Convert a integer into a string
>>> str(5)
'5'
>>> str(5.99)
'5.99'


#!/usr/bin/python
str = 'Hello World!'
print str          # Prints complete string
print str[0]       # Prints first character of the string
print str[2:5]     # Prints characters starting from 3rd to 5th
print str[2:]      # Prints string starting from 3rd character
print str * 2      # Prints string two times
print str + "TEST" # Prints concatenated string

The result of the above is :


Hello World!
H
llo
llo World!
Hello World!Hello World!
Hello World!TEST

## Lecture: Data Types - Booleans and None

True = a constant

>>> True
True
>>> bool
<type 'bool'>
>>> False
False
>>> bool("bob")
True
>>> bool("")
False
>>> bool("2")
True
>>> bool("0"
True.

Bool for checking of a string is false or true as above
None evaluates to nothing .. And nothing is printed out
>>> None
>>>

## Lecture: Working with Variables
>>> a_word = "bacon"
>>> a_word'bacon'
>>> print (a_word)bacon

## Lecture: Lists and Tuples. (. Kinda similar to arrays in bash)

A list contains items separated by commas and enclosed within square brackets ([]). To some extent, lists are similar to arrays in C. One difference between them is that all the items belonging to a list can be of different data type.
The values stored in a list can be accessed using the slice operator ([ ] and [:]) with indexes starting at 0 in the beginning of the list and working their way to end -1. The plus (+) sign is the list concatenation operator, and the asterisk (*) is the repetition operator. For example −
#!/usr/bin/python
list = [ 'abcd', 786 , 2.23, 'john', 70.2 ]
tinylist = [123, 'john']
print list          # Prints complete list
print list[0]       # Prints first element of the list
print list[1:3]     # Prints elements starting from 2nd till 4th
print list[2:]      # Prints elements starting from 3rd element
print tinylist * 2  # Prints list two times
print list + tinylist # Prints concatenated lists
This produce the following result −
['abcd', 786, 2.23, 'john', 70.200000000000003]
abcd
[786, 2.23]
[2.23, 'john', 70.200000000000003]
[123, 'john', 123, 'john']
['abcd', 786, 2.23, 'john', 70.200000000000003, 123, 'john']





>>> my_list = [1, 'a', 2.0, True]
>>> my_list
[1, 'a', 2.0, True]
my_list[0]  #shows first entry in list
1
Vai

Len(variable list) will show the length of variable in list
>>> len(my_list)4

>>> db = [1, 'a', 3, 4, 5, 788, False]
>>> db[0]
1
>>> db[-1]
False
>>> len(db)
7
slicing :
>>> db[0:5].  == this means show the first indexe UPTO but not including the 5th index hence the below
[1, 'a', 3, 4, 5]

>>> db[:4]
[1, 'a', 3, 4]
>>> db[4:]
[5, 788, False]

>>> db[1::2]. == this means start with the first one .. Then skip step the number of :'s in this case 2 , and then count 2 indexes from there to
['a', 4, 788]

You can change list in a variable without reassinging it
>>> db += [ 89, 90] = add it to the last entries
>>> db
[1, 'a', 3, 4, 5, 788, False, False, 89, 90]

>>> db[3:5] = ['d', 500] = replaced 3rd and 5 entryies with d and 500
>>> db
[1, 'a', 3, 'd', 500, 788, False, False, 89, 90]

List.pop() = removes the last items or list.pop(0)



Tuples =

A tuple consists of a number of values separated by commas. Unlike lists, however, tuples are enclosed within parentheses.
The main differences between lists and tuples are: Lists are enclosed in brackets ( [ ] ) and their elements and size can be changed, while tuples are enclosed in parentheses ( ( ) ) and cannot be updated. Tuples can be thought of as read-only lists. For example −
#!/usr/bin/python
tuple = ( 'abcd', 786 , 2.23, 'john', 70.2  )
tinytuple = (123, 'john')
print tuple           # Prints complete list
print tuple[0]        # Prints first element of the list
print tuple[1:3]      # Prints elements starting from 2nd till 3rd
print tuple[2:]       # Prints elements starting from 3rd element
print tinytuple * 2   # Prints list two times
print tuple + tinytuple # Prints concatenated lists
This produce the following result −
('abcd', 786, 2.23, 'john', 70.200000000000003)
abcd
(786, 2.23)
(2.23, 'john', 70.200000000000003)
(123, 'john', 123, 'john')
('abcd', 786, 2.23, 'john', 70.200000000000003, 123, 'john')

a fixed length object that never changes length but have a combintion of things. -u cant modify them e.g

>>> "my name is %s" % "james"
'my name is james'

>>> "my name is %s %s" % ("james", "Okonkwo")
'my name is james Okonkwo'


#!/usr/bin/python
tuple = ( 'abcd', 786 , 2.23, 'john', 70.2  )
list = [ 'abcd', 786 , 2.23, 'john', 70.2  ]
tuple[2] = 1000    # Invalid syntax with tuple
list[2] = 1000     # Valid syntax with l


## Lecture: Dictionaries (dicts)

>>> ages = { 'kevin' : 59, 'alex' : 33, 'chuks' : 35 }
>>> ages
Dicts are unordered here.. If u need to order user something from standard library.

They can be called this way
>>> ages['kevin']
59
>>> ages['chuks']
35
>>> ages['alex']
33

You can add a new entry like this
>>> ages['nkem'] = 32
>>> ages
{'nkem': 32, 'alex': 33, 'chuks': 35, 'kevin': 59}
Deleted single key values with
>>> del ages['chuks']
>>> ages
{'nkem': 32, 'alex': 33, 'kevin': 59}  or the entire array with
>>> del ages
>>> ages
Or delete with pop which will show you what is deleted :)
>>> ages = { 'Iloba' : 37, 'alex' : 33, 'chuks' : 35 }
>>> ages.pop('alex')
33

You can call key value method on it e.g


>>> ages.values()
[37, 32, 35]
>>> ages.keys()
['Iloba', 'Tola', 'chuks'] or items method
>>> ages.items()
[('Iloba', 37), ('Tola', 32), ('chuks', 35)]
You cn create dictionaires any of the following ways :


>>> schools = dict(chuks="FGCL", nkem="BOLS", iloba="Ecolint")
>>> schools
{'iloba': 'Ecolint', 'nkem': 'BOLS', 'chuks': 'FGCL'}
>>> aging = dict([('Iloba', 37), ('Tola', 32), ('chuks', 35)])
>>> aging
{'Iloba': 37, 'Tola': 32, 'chuks': 35}


## ## Lecture: Control Flow - Conditionals and Comparisons

>>> 1 < 2
True
>>> 2 > 3
False

>>> 1 ==1
True
>>> 1 !=1
False
>>> 1 !=2
True
>>> 1.0 ==1
True

Sample script:  ..
Note user 4 spaces in python to indicate code block..
>>> name = "chukwuekwu"
>>> if len(name) >= 5:
...     print("name is long")
... elif len(name) == 4:
...     print("name is average")
... else:
...     print("name is short")
...
name is long


>>> if "test":
...     print("this is a test")
...
this is a test
The reason it evaluates as true is because the phrase "test" is considered "True" because when a bool(test) is evaluated it comes out as true :
e.g
>>> bool("test")
True


So this is your way of testing out a code block if it is an if statement.

## ## Lecture: Control Flow - Loops
While and for loop

while True:
...     print("Chuks is awesome")

Chuks is awesome
Chuks is awesome
Chuks is awesome
Chuks is awesome
Chuks is awesome
Chuks is awesome
Chuks is awesome^C
This goes on forever as nothing to break it .. So ctrl C to stop

Beter approach:


>>> go = True
>>> while go:
...     print("Chuks is awesome")
...     go = False
...
Chuks is awesome   only once because it read the first one and then it got to false
More real example is using a counter

>>> count = 0
>>> while count < 20:
...     print("We're counting")
...     count += 2
...
We're counting
We're counting
We're counting
We're counting
We're counting
We're counting
We're counting
We're counting
We're counting
We're counting


>>> count = 2
>>> while count < 20:
...     if count % 2 == 0:
...        break
...     print("We're counting %s" % count)
...     count +=3


For loop :


>>> family = ['chuks', 'buchy', 'micah', 'wifey']
>>> for members in family:
...     print(members)
...
chuks
buchy
micah
wifey
>>>


## Lecture: Control Flow - Logic Operations

>>> not 1
False
>>> bool(1)
True
>>> not True
False

So it is negating the truthfulness of 1  which can be seen by bool(1) which = True

>>> if not len("chuks") > 10:
...     print("it is not")
...
it is not.
{ this is so because we no chuks will always be less than 10  and so instead of having an ELSE statement we do if not.}

Is

it is not
>>> 'a' is 'a'
True
>>> {} is {}.  Empy space is not the same because they have different spots in memory
False
>>> 1 == 1.0.   " read as 1 is EQUIVALENT to 1" which is True as below"
True
>>> 1 is 1.0.    " 1 is NOT 1.0 because they have different spots in memory based on theier identitiues -- unique to python
False.              This is because it looks for the spot in memory and the spot is different as shown below
>>> id(1)
17584472
>>> id(1.0)
17655456


&& and or !! Or  in other program lines

And requires both sides to be equal e.g
>>> 1  and 1
1
And will return the first false value if there is one or the  last truth value
>>> 1 and 2
2

>>> var = None
>>> var and str(var)
>>> var =1
>>> var and str(var)
'1'
OR  shows the first true value e.g

>>> 1 or 2
1       { here 1 is true so it shows the first true one}
>>> 0 or 2
2   ( since 0 is false it shows the first true value which is 2)%sas


#!/bin/python

user = { 'admin': True, 'active': False, 'name': 'chuks'}

print("My name is %s and i am a %s christian"  % (user['name'] , user['admin']))
And the output when run is this :

My name is chuks and i am a True christian


#!/usr/bin/env python
user = [
        { 'admin': False,'active': False, 'name': 'Chuks'},
        { 'admin': True, 'active': True, 'name': 'Ken' },
        { 'admin': False,'active': True, 'name': 'Kevin' },
        { 'admin': True, 'active': False, 'name': 'Doris' },
        { 'admin': True, 'active': True, 'name': 'Buchy' },
        { 'admin': True, 'active': False, 'name': 'Micah' },
       ]
line = 1
for x in user:
    if x['admin']:
        print("%s ADMIN %s" % (line, x['name']))
    elif x['admin']:
        print("%s ADMIN %s" % (line, x['name']))
    elif x['active']:
        print("%s ACTIVE - %s" %(line, x['name']))
    else:
        print("%s %s") % (line, x['name'])
    line += 1

Output =
1 Chuks
2 ADMIN Ken
3 ACTIVE - Kevin
4 ADMIN Doris
5 ADMIN Buchy
6 ADMIN Micah

## Reading User Input
 
Raw_input ( _gives a prompt waiting for user to enter then assignes entry as avariable e.g name = raw_input("what is yoru name? ")
Input () takes the entry and parses it in python like in REPL  and gives back whatever the result is
 
Raw_input is better because it takes any entry and converts it to a string " where as inout doesn’t convert it to a string but take it raw and can err out
 
Or better you can for example age= int(raw_input("how old are you")) = so it till take any entry and try to make it an integer
 
 
#!/bin/python
 
name = raw_input("What is yoru name ? ")
birthdate = raw_input ("What is your birthdate? ")
age = input ("How old are you? ")
print("%s was born on %s" % (name, birthdate))
print("Half of your age is %s" % (age / 2)
)
 
 
## Encapsulating Behavior Using Functions
 
1 #!/bin/python
  2
  3 height = float(raw_input("what is your height? (inches or meters) "))
  4 weight = float(raw_input("what is your weight? (pounds or meters) "))
  5 unit = raw_input("Are your measurements in metric or imperail units? ").lower().strip()
  6 if unit.startswith('i'):     #unit starts with as is implied
  7     bmi = 703 * (weight / (height ** 2))
  8 elif unit.startswith('m'):
  9     bmi = (weight / (height ** 2))
10
11 print ("Your BMI is %s" % bmi)
12
 
 
We will correct the above to cover incase we get random entries in input so we can reprompt
the user to re-enter the password we will do this by putting them into funtions
