# C++ initial phase


* [x] Variables & Data types
* [x] Strings( c & c++)
* [x] Arrays
* [x] Functions 
* [x] Conditions

* [x] comments 
* [x] Pointers
* [x] Classes & objects
* [x] 

[Link for my other repos & Notes](https://github.com/)

# Table of content 
# c++

-[Toc](#table-of-content)
 





 # Lets start
 ## introduction
 C++ is an object-oriented programming language which gives a clear structure to programs and allows code to be reused, lowering development costs. C++ is portable and can be used to develop applications that can be adapted to multiple platforms.

## variables & data types
variables are containers for storing data values.
eg int name

Boolean(yes/no) -1 & 0
int(interger) 
char (character)
float (decimal numbers with limited precison)
double(decimal with no limit) are common types of ddata types 

 ## c strings -
 mostly used in c programs.

 ## c++ strings - 
 helps to carry out some functions which are predefined in it such as to find value. s1.find(), s1.at(),etc but it has some limitations 
 eg; program for encryption & decryption of messeges 


 ## c++ functions
 c++ consist of predefined functions & we can create a create function as per our need.




 ## conditions
 if
 else
 else if
 switch
 common conditional statements
eg if(a>b)
{
    cout<<"a">>;
}else{
    cout<<"b">>;
}



## Loops
in c++ loops are used to repeat some actions under certain conditions meet
for loop,while loop,do while loop are common types of loops
 eg for(i=0;i<num;i++>)

## comments
comments are not compiled 0r build,its completely for develupers for further reference about line of programs. eg //comment

## pointers
pointers are address locations of the variables.eg int num. (here value of the variable is stored in a particular location & pointers are used to output the address of varibles.* is used to display the address.

----


 -[Toc](#table-of-content)
 



 ## 


#  FLUTTER


* [x] Intro
* [x] Dart basics
* [x] BASIC Class & commands
* [x] 
* [x]
* [x] 
* [x] 
* [x] 
* [x] 
* [x]
* [x] 
* [x] 
* [x] 
* [x] 
* [x]



## intro
flutter enables  multi platform app develepment.Dart langauge is used in it.

## Dart
dart is language similiar to javascript.in dart we cannot change the data type of a string type after assigning to a value.if need we need to change ,use dynamic 
eg string name="kiran";
   name="30" // shows error
   in such case 
   dynamic name="kiran"
   name=30;

   functions in dart similiar to other types  of language.
   "list" is used instead of arrays in dart
    eg list<String> name=[ab,bc];// stores array of string.


    in dart classes & instances are used frequently.
    
    
    eg   
    void main(){
        book novel=book();  //a instance of class created
        print(novel.author); // calling a class function 
        book poem=book();  // new instance of class
    }
    
    class book{
        string author; // contents of book()
        int pages;
        void publisher(){
            print("crime novel 1");
        }
    }
    
## first sample app

app are made with widgets.each terms in app are widgets,
dart documentations & android studio suggestions helps in coding.
comments are added by ide itself .

pubspec.yaml  is file type used to store resources such as images to show in flutter. intentations are very sensitive in .yaml file & yaml is also a markup language.
by connecting a physical device by ussb rendering, to studio we can avoid using emulator. 


## MATERIAL theme
its launched by google,can be used in both ios & andro.
import 'package:flutter/material.dart';//for material theme 

## containers 
its  simple widget,only 1 child can have.

SAFEAREA  neeed to be used for seeing containers in ui.

common commands 
### 1 SAFEAREA
- to see widget wuthin ui(under notch of display)
### 2 stateless widget
-Stateless widget are useful when the part of the user interface you are describing does not depend on anything other than the configuration information in the object itself
### 3 column 
 & rows -can have more child.can be further modified.
mainaxissize-used to change size of column.
verticaldirection -used to change position in vertical of column.
mainaxisalignment- change allignment of multiple column as per start position.(vertical)
crossaxisaligmenrt-change  alignmnet in horizontaly.
    sizedbox - used to provide space between columns.


### 4 scaffold - its  class with more features, we can change  bg color,add text,app bar,so on... 

## FLUTTER CHEATSHEET
[Flutter layout cheatsheet] (https://medium.com/flutter-community/flutter-layout-cheat-sheet-5363348d037e)

## Flutter functions
similiar to other languages , functions have same action here & same syntax.

## flutter packages
contains lot of packages which is been uploaded by devs.& also by google team.
its prebuild package can be add to our project by  add to .yaml file & add to project by import.
h
(https://pub.dev/){flutter packages }
## ARROW FUNCTIONS
these are used to used when one line of code is to execute.else { }is used,
## CLASS & OBJECTS
in dart alike other languages, also has class,its properties & objects



eg 

Class car
{               // class
    int noof Seats=5; //property
    void drive(){  //object
        print ('driving');
    }
}
Car mycar=Car(); // new method (object) creation.
by creating object we can change the value of property value initialised. 


## constructors
constructor is also part of classes.
eg

 Class Life{
    int foot=2;
    int leg=2;
    void talk(){
        print ('talking');
    }
}
Life human=Life();
Life snake=Life();






print(snake.leg)
print(human.leg)

when we init both will have same output of 2.
inorder to have diffferent values we use CONSTRUCTORS.

Life(double countleg){
    leg=countleg;
}

we can have different value. all we need to have is 
Life human=Life(2.4);
Life snake=Life(5.55);
we neeed to give value during creation of object.


## OOPS 
there are 4 pillars in oops
### Abstraction
its the process of splitiing up of tasks.
A bigger tasks are splitted in to simple jobs.
eg in industry. production,quality, collection etc are done by different people. 
### Encapsulation
its the process of giving border to the area.

eg in an hotel with a  waiter  & shef.both person have their won skills so they need to be in their limit. the waiter cant comment of shefs food making method & shef cant comment on waiters serving technique. so in order to have a limit every one need to be in their limit.Encapsulation does this process.
 #ateless widgets are immutable(cant be changed).

## const vs final
both are constant values which cant be changed after init.but the difference is CONST dont have acess during runtime.
FINAL can be used during runtime.

eg const int num=5;
 final int value=4;

 // here values of both cant be chabnged but final can do task during runtime of app.
  

  ## ENUM
  ENUM are user defined values
  
  enum Status { 
   none, 
   running, 
   stopped, 
   paused 
}

## Ternary operator
ternary is used as  a alternate if else conditions.

eg
 int myage =21;
bool buyalchahol=myage>21?true:false;
print (buyalchohol);

## ASYNCHRONOUS PROGRAMING
for eg; if there are 3 tasks to be done.
task 1,task 2,task 3. which are defined in same order.

task1 ()
{print('task1);
}

task2 ()
{print('task2);
}
task3 ()
{print('task3);
}
output will be in same order.this is synchronous method.

if

task2(){
    print('task 2');
}
 task3 if replaced by
task3(){
    print('task3 '+ task 2);
}
here task3 value depends on value of 2 but task 2 delays by 3 sec so output printed in console will be in order of
task 1
task3 + null
task 2

but we can hold the order by using ASYNC & AWAIT method
## Lifecycle method

there are 3 terms 1 init
 1 init state- when we need to add something as soon as stateful widget  is created
 2 build- when we need to add something every time buid method is created  we add here.

 3 cancelation- when we need to add something when widget is destroyed. 
 ## dart mixin
 mixin is method of inheriting the property of classs.



 for eg 
 class animal(){
     void move(){
         print('i am animal);}
 }
class bird(){
    void move(){
        print('i can  fly');
    }
}

now by using extends keyword the bird cklass can use the property of animal class.
eg class bird extends animal{   //likely.if we want change the value of property of parent classs we can use the  OVERWRITE  keyword
EG 
class bird extends animal
{
    @overwrite
    void move(){
        super.move()[
            print('its overwritten command);
        ]
    }
}

} 


 'MIXIN' is used when a new class is created 
 eg 
 a class duck is created but it can move & fly.to use both the property of animal& bird we can use mixin 


 by eg
  mixin bird {
      void move(){
          print('flyyy');
      }
  }
  mixin fish{
      void move(){
          print('swimm);
      }
  }

  here we can duck class which have both prop of fish & bird by using 

  class duck extends animal with fish,bird{}


  here 'WITH' keyword using to encoperate the prop of different class.

  # Stateful & STATELESS WIDGET
  a stateless widget dont a fixed state.where as statefull widget have a state.actually statefull widget is not changing ,its state is been changed,variables inside state widget are not marked as final coz it might change as per ui.after making changes in the state in stateful widget then we make a copy of it.

  in stateless widget all prop neeed to be declared as final,but if need to update the property ina stateless widget then we need to create a new constructor. 


# STATIC

if we need to create a constatnt value inside a class  STATIC keyword used.

void main(){
circle firstcircle=circle();  //object of class

firstcircle.areac;    // by ading static keyword we dont need to use () to call the method ,if no static is used firstcircle().areac; normal call

}



class circle{

    static const double pi=3.14;  // static
 keyword used so value wont change in any object of the class
    static void area(double radius){
      double  areac=2*pi*radius;
      print(areac);


    }
}



# STREAMBUILDER WIDGET
a stream builder is used in firebase related apps,for eg we are creating  a  chat app the data is stored in a db, 

in chat screen user sends chat messege & also can see previous chats of same user & other  users.

sp everytime new meseges is been stored in db so user need to get updated chat ata in a widget in such case stream builder is used.

Streambuilder(){
    stream:  property used to fetch where the data is stored
    builder: property is to give the idea of constructing the widget while new data is been updated,  

    ## watch flashcaht app =>189 video for more info (angela yu udemy)
}  



  # STATE MANAGEMENT
 STATE is  defined data,all the value of data summup ons to form the state.eg
 in a stateful widget properties are not defined as final, coz it may change.
 if a bool data type is declared,& the value of the data is stored by the help of state management system.here the saved data is not big to save in DATA BASE but these small data requires to run the app.

 more precisely , the informations to be remembered for running the app is called DATA. WE CAN CREATE state with EVERY DATAtypes in flutter. there are differnet types of state management in flutter (available in pub.dev)
 .flutter defined state mangement is SETSTATE(){};
 every time we use settstate the widget inside stateful widget is been re created.its only applicable in stateful widget.
  
# NULL SAFETY
eg 
   void main(){
       string name;
       print(name.lenght);

}
in this we get error as value of name is not declared(null),mostly these errors are flagged  during run time of app.when null safety feature is enabled these errors are flagged during compile time so we can resolve the error before it reaches the user ui.

as null safety in introduced in flutter 2.0, no variables cant be declared as null.
if we need to declare a variable as null use '?'
eg 
void main(
    {
    string? name
    print(name?.length);
}
here by using '?' after name variable,the part after '/' is not executed if value of variable is  null else it is executed.

})

## NOTE: DIFF BETWEEN METHOD -OBJECTS-PROPERTIES -CONSTRUCTORS



    class is a combination of both method  & property
    eg class car{
        string wheel='ofspring'; // properties of class
        int no of wheel= 5;

        drive(){
            print('driving);
        }; // method of class car
    }
 
in case of object

it is created as a instance of class
eg   car audi=car();  // type of object //name of object // instance of class  


* object of class can acess both property & method of a class


In case of constructor ,it holds the same name of the class followed by parenthesis,
eg car(){
    print('sss');
}
## PROVIDER STATE MANAGEMENT
provider is a package .
we can pass vales from a parent widget to subclass by adding provider & listeners.

* changeNotifier() class used to inform listeners  that any update from this  class must be updated

# dart data type &  its properties,method
## String

``` 
String person="diljith";

##properties

print(person.length);
print(person.isEmpty);

##methods
print(person.toLowercase());
print(person.toUppercase());

```
##  int
```
int number=20;

##properties
print(number.isEven);      output= true
print(number.isOdd);       output=false
print(number.is Negative);  output=false

```
## double
```
double number=220.5;
## method
print(number.round());
```
# List

```
 List<String>Students=["dil","kishan","gokul"];

 ##properties
 print(Students.first);
 print(Students.isEmpty);
 print(Students.isNotEmpty);
 print(Students.length);
 print(Students.last);
 

 #methods

 Students.add("neymar");        //to add new value to list,but it will be aded at last

 Students.insert(0,"ronaldo");   //to add value to a particular position in list

 Students.remove("neymar");  //tp remove value in list
Students.removeAt(2);       // remove data aspper position
```
## Map (data type)

```

Map<String,dynamic>student={"diljith":"cse","eldo":26}



## property

print(student.length);      // for length of data type ,output :2

print(student.isEmpty);      //check wheather has data , output :false

print(student.isNotEmpty);  // telling that map is not empty ,output:true

print(student.keys);        // to print only keys of map

print(student.values);      //to print values

## methods

student.addAll({"eepan":88,"sarayu":30});       //to add new value or values in a map with key & values

student.clear();        //clear all data in a map
student.remove("sarayu");       //to remove data both key & its value.

```



###  NB : PROJECTS IN SEPERATE REPO




----


 -[Toc](#table-of-content)
 



 ## 


#  PYTHON


* [x] Intro
* [x] Data types
* [x] BASIC Class & commands
* [x] 
* [x]
* [x] 
* [x] 
* [x] 
* [x] 
* [x]
* [x] 
* [x] 
* [x] 
* [x] 
* [x]



## INTRO







## DATA TYPES


INT-5
FLOAT-5.2
STRING-'one'

### dir()
dir() is a function in python ,shows possibilities to do with a list[].
### help(str)- gives the list methods avail for string


* in python inentation is important


apart from c++ in python

if num%2==0:  // column is used,no  parenthesis                                     conditions 
 print("odd")
else:
 print("even")


 ### elif

 more like a else if

 if a<12:
  print ("under 12")
 elif a<18:
  print("under 18")
 else: 
 print("adult +")  


 ## Logical Operat

 AND ,OR ,NOT

 ASKPYTHON.COM - documentation for python  
 # LIST(arrays)  
 oddnumbers=[1,3,5]  // syntax for array & assign values
 print(oddnumbers[2]) // syntax for print value from a array
print(oddnumbers[-1])// syntax for printing final value in the array (counting in backward order)
 

 array documentation has functionalities of arrays  like append,extend

 ## Nested List
   we can insert multiple lists within a list
   eg

   fruits=["starwabery","apple","orange"]
  vegetables= ["cabage","tomato","ladies finger"]

  food=["fruits","vegetables"]

  if we print print(food), we will get both list seperated.


  ## common error  within list

  the total number of elements in a array is always total-1
  ie  food=["cherry","apple","cake"]
   nos=len(food)
   result nos will be 3, if we call for food[3] it will end up in error showing "exceeded limit"
    so the solution is final length of array will be always final length -1 else it end up in error

# loops in python

## loop with in a list
```
 numbers=[2,5,58,8];
 for number in numbers:
  print(number)
  ```
output will be 2 5 58


## loop withina range
 for number in range(1,100,2):  //  1 is start point. 100 is endpoint(100-1), 2 is loop difference


# Functions 
declaration syntax  = 

def move():
  print("moved")       //look for intentation 
  
  # TUPINS
  tupins are immutable
  eg of tupin creation
   coordinates=(4,5)   /n

   print(coordinates)
   or print(coordinate[1])

   tupins are like list but values in tupins cant be changed.
   
   
# Dictionary
Dictionaries are used to store data values in key:value pairs.

A dictionary is a collection which is ordered*, changeable and do not allow duplicates.
eg:
```
thisdict = {
  "brand": "Ford",
  "model": "Mustang", 
  "year": 1964
}
```
in dictionary using for loop we can print eah term 
```
program_data={"brand": "Ford"
  "model": "Mustang" 
  "year": 1964}
  for (key in program_data):
   print key 
   ```
   output will be
   model
   year

   to print the values
   ```
   program_data[key]
   ```
   this will list the value of keys one by one

   ### dictionary with in a dictionary & loop with in  a dictionary 

   ```
   ### normal dictionary declaration

   countries_travelled={"france":"beatiful country","germany":"mechancial city"}
 ```
 ```
 ## list in a dictionary
 
 countries travelled={"asia":[india,pakisthan,china]}
 ```
```
##dictionary with in dictionary

 countries_travelled={"asia":{"india":["kerala","tamilnadu","karnataka"],"pakistan":"ahamedabad"}}
 ```
```
 we cant declare as
 countries_travelled={"asia":"india","pakistan"}

 either it should be in a list or dict
```
# WHILE LOOP

