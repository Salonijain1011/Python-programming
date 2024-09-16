# Python-programming
Python basic </br>
(1) #calculator</br>
    a=10</br>
    b=2</br>
    print("the value of",a,"+",2,"is:",a+b)</br>
    print("the vaue of",a,"-",2,"is:",a-b)</br>
    print("the value of",a,"*",2,"is:",a*b)</br>
    print("the value of",a,"/",2,"is:",a/b)</br>
    print("the value of",a,"**",2,"is:",a**b)</br>
    print("the value of",a,"%",2,"is:",a%b)</br>
    
output:- </br>
the value of 10 + 2 is: 12</br>
the vaue of 10 - 2 is: 8</br>
the value of 10 * 2 is: 20</br>
the value of 10 / 2 is: 5.0</br>
the value of 10 ** 2 is: 100</br>
the value of 10 % 2 is: 0</br>


 (2) #Typecasting</br>
  a="1"</br>
  b="2"</br>
  print(int(a)+int(b))</br>
    
output:- 3 </br>

  #explicit typecasting</br>
  string="20"</br>
  number=2</br>
  string_number=int(string)</br>
  sum=number+string_number</br>
  print("the sum is:",sum)</br>

output:- the sum is: 22 </br>


  #implicit typecasting</br>
  c=2.7</br>
  d=3</br>
  print(c+d)</br>

output:- 5.7 </br>


(3) #user input</br>
    a=input()</br>
    print("my name is :",a)</br>
    b=input("enter first number:")</br>
    c=input("enter second number")</br>
    print(int(b)+int(c))</br>

output:- saloni</br>
my name is : saloni</br>
enter first number:2</br>
enter second number3</br>
5</br>


(4) #type function </br>
    print(type(a))</br>

output:- <class 'str'> </br>
    

(5) #strings</br>
    x = "Saloni"</br>
    print(x)</br>
    
output:- Saloni<br/>


(6) #slicing of strings</br>
    names = "harry,shubh"</br>
    print(names[0:5])</br>
    print(names[:2])</br>
    print(names[:-3])</br> 
    print(names[-3:-1]) #negative indexing</br>

output:- harry</br>
ha</br>
harry,sh</br>
ub</br>

   #strings are immutable</br>
   #operations on string</br>
   name = "harry!"</br>
   print(len(name))</br>
   print(name.upper())</br>
   print(name.lower())</br>
   print(name.rstrip("!")) #removes trailing characters</br>
   print(name.replace("harry","john"))</br>
   print(name.split(" "))</br>
   print(name.capitalize()) #first character is in uppercase and others are in lower case</br>
   print(name.count("harry")) #how many times harry word is in name</br>
   print(name.endswith("!"))</br>
   print(name.find("arry"))</br>
   print(name.isalnum()) #a-z,A-Z,0-9</br>
   print(name.isalpha())#a-z,A-Z</br>
   print(name.isupper())</br>
   print(name.islower())</br>
   print(name.isprintable())</br>
   print(name.isspace())#white space</br>
   print(name.istitle())</br>
   print(name.startswith("harry"))</br>
   print(name.swapcase())</br>

output:- 6</br>
HARRY!</br>
harry!</br>
harry</br>
john!</br>
['harry!']</br>
Harry!</br>
1</br>
True</br>
1</br>
False</br>
False</br>
False</br>
True</br>
True</br>
False</br>
False</br>
True</br>
HARRY!</br>



    




