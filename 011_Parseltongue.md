# Adventures in parseltongue

&nbsp;
&nbsp;


### ISO Python IDE to love and cherish


#### Terminal 
Pro: outputs only the info I want to see. I feel like I'm in the Matrix and/or 1997 <br>
Con: can't edit inline <br>

#### Spyder
Pro: seems cool <br>
Cons: not launching in my Python 2.7 env for some reason. Also, the runfile paths printing doubled up in the console at every single run makes it hard to read output <br>

Example: print (2+5) <br>
yields: runfile('/Users/hhouse/.spyder-py3/temp.py', wdir='/Users/hhouse/.spyder-py3')
7 <br>

#### Sublime Text
Pro: I like it for editing HTML and CSS at work <br>
Con: Very annoying time counter with every output. I tried to customize to quiet build environment but I didn't work. I guess I did it wrong.

#### BBEdit
Pro: Easier to read output (though still annoying extra stuff present) <br>
Con: Maybe doesn't accept input. Getting error: EOFError: EOF when reading a line

#### Visual Studio Code
Pro: Looks like it would be useful if I had any idea what I was doing <br>
Con: I don't have any idea, and I need something that is simpler to understand and get using

#### Brackets
Pro: Again, looks like it would be handy if I wasn't so noo <br>
Con: Needs other things loaded or added in order to accept inputs

#### PyCharm CE
The version I downloaded is free and has a good rep. About to test it out. Maybe 7th time's the (py)charm! <br>

Pro: "Run" is a clearly displayed option in the menu toolbar. Easy to find! <br>
Con: SIGH. Extraneous output. When everything runs correctly still get "Process finished with exit code 0" message. It's annoying, but it seems like I can't escape this output quirk. 

Will keep using PyCharm for now.


&nbsp;
&nbsp;

#### Polite math bot

num = int(input("Hello, let's do some division. Please tell me a number. ")) <br>
print("Thank you for the number", num, ".") <br>

check = int(input("Hello, what number would you like me to divide that by? ")) <br>
print("Thank you. You'd like me to divide", num, "by", check, ".") <br>

if num % check == 0: <br>
    &nbsp; &nbsp; ans = num/check <br>
    &nbsp; &nbsp; print ("\n") <br>
    &nbsp; &nbsp; print (num, "divided by", check, "is", int(ans), ". ") <br>
else: <br>
    &nbsp; &nbsp; print ("\n") <br>
    &nbsp; &nbsp; print("I'm sorry. That's too hard.") <br>

&nbsp;
&nbsp;

#### Tell me a number
num = int(input("Hello, tell me a number: ")) <br>
print("Thank you.") <br>

if num % 2 == 0: <br>
    &nbsp; &nbsp; print ("That was an even number.") <br>
else: <br>
    &nbsp; &nbsp; print("That was an odd number.")

&nbsp;
&nbsp;

#### My first Python script
name = input("Hello, what is your name? ") <br>
age = input("Hello again, how old are you? ") <br>
age = int(age) <br>
year = str((100-age)+2018) <br>
print ("\n") <br>
print ("Hello, " + name + ". You will be 100 years old this time of year in " + year + ".")




&nbsp; &nbsp; &nbsp; &nbsp;

Markdown is interacting with my copy/paste Python from Terminal. Having to manually insert indents and line breaks. Some may be missing. This is really not the best format for this material.

&nbsp; &nbsp;

## Mathing with pet names

&nbsp; &nbsp;

>>> Earnest = 10000 <br>
>>> print(Earnest)
#### 10000

&nbsp;

>>> Earnest = 5 < 8 <br>
>>> print (Earnest)
#### True

&nbsp;

>>> print("Duvel" + "Bear")
#### DuvelBear

>>> print ("Duvel " + "Bear")
#### Duvel Bear

&nbsp;

>>> ExtraKitty = 100 <br>
>>> print (ExtraKitty > 6)
#### True

&nbsp;

>>> print ("Duvel " * 3)
#### Duvel Duvel Duvel 

&nbsp;

>>> ss = "Extra Kitty" <br>
>>> print(ss.upper())
#### EXTRA KITTY

 &nbsp;
 
>>> Earnest = "I'm going to eat too fast and puke and then eat that" <br>
>>> print (len(Earnest))
#### 52

&nbsp;

>>> Duvel = "Little orange sunshine" <br>
>>> " ".join(Duvel)
#### 'L i t t l e   o r a n g e   s u n s h i n e'

&nbsp;

>>> print("".join(reversed(Duvel)))
#### enihsnus egnaro elttiL

&nbsp;

 
>>> print(" ; ".join(["Earnest", "Extra Kitty" , "Duvel"]))
#### Earnest ; Extra Kitty ; Duvel

&nbsp; 

>>> Duvel = "Little orange sunshine" <br>
>>> print (Duvel.split())
#### ['Little', 'orange', 'sunshine']
&nbsp;
>>> NewList = (Duvel.split())
>>> print (NewList)
#### ['Little', 'orange', 'sunshine']
&nbsp;
>>> print (" ; ".join(NewList))
#### Little ; orange ; sunshine


&nbsp;

>>> name, hex = "Seafoam Blue", "89BBBC" <br>
>>> print (name)
#### Seafoam Blue
>>> print (hex)
#### 89BBBC
>>> print ("#" + hex)
#### #89BBBC

&nbsp; 

>>> x = "Earnest loves {} and {}." <br>
>>> print(x.format("treats","hugs"))
#### Earnest loves treats and hugs.

&nbsp; &nbsp;

# Things to be learned

&nbsp;

## Something going wrong here with the line breaks
&nbsp;

>>> ''' <br>
... As the wise Ralph said <br>
... My cats breath smells like cat food <br>
... This was a haiku <br>
... '''
#### '\nAs the wise Ralph said\nMy cats breath smells like cat food\nThis was a haiku\n'
&nbsp;

I don't understand **line breaks and escape characters**. Research later.

&nbsp; &nbsp; 

## Learn how to call values from dictionaries

>>> MyColor = {'name': 'seafoam blue', 'hex': '89BBBC'} <br>
>>> print(MyColor.hex)
#### Traceback (most recent call last):
#### File "<stdin>", line 1, in <module>
#### AttributeError: 'dict' object has no attribute 'hex' <br>
>>> print(hex.MyColor)
 
#### Traceback (most recent call last):
#### File "<stdin>", line 1, in <module>
#### AttributeError: 'builtin_function_or_method' object has no attribute 'MyColor'
>>> 

&nbsp; &nbsp; &nbsp; &nbsp;
  

< [There's no place like home](./index.md)
