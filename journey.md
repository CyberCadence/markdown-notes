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