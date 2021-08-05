
#  What is JavaScript Programming ? 

> Ans: JavaScript is a dynamic, loosly type programming language that's used for web development, web applications, game development and many more.
---
# JavaScript Programming Basics
## Variables : 

>Variables are containers that hold the data, it doesn't mean which type of data it holds and then stores that data into compute memory. 

__Types of Variable availabe in JS :__
There are 3 types of variable avaible in JavaScript. They are:
1. var
>It has functional scope. You can re-declare var many times if you want. You can update variables.

Syntax: __var VariableName = Value__  ;

```JavaScript
   exp:  var num= 1;
         var num=3;  // This is the drawback of var 
         var name= "Sanket";
         var val="true";
```
2. let
>let introduce to over come from drawbacks of var Variable.It works quite similiar as var but it has lexical scope (A lexical scope in JavaScript means that a variable defined outside a function can be accessible inside another function defined after the variable declaration). You cannot redeclare let variable. You can update it.

Syntax: __let VariableName = Value__  ;

```JavaScript
   exp:  let num= 1;
         num= 3;
        let num=7; // this will throw an error 
```

3. Const
>It has also lexical scope. You cannot redeclare const variable you cannot update it.

Syntax: __const VariableName = Value__  ;

```JavaScript
   exp:  const num= 1;
         num= 3; // this will throw an error 
        const num=7; // this will throw an error 
```
## DATATYPES :
> Datatypes declare that which type of data or value has been assigned to the variable. There are two types of data types in JavaScript.
1. Primitive Data Type : It is pre defined data types we can't change it. 
    
    * Number : In JavaScript there's no such int, float and double so on. In JS we have only number which can be write in deciaml or without decimal.

    __To check the data type of any variable we can use : typeof() function.__

    ```JavaScript
      var x=4;
      var y=3.55;
      // Let's check the data type of these two variables using typeof() function
      console.log(typeof(x));  // Output will be : Number
      console.log(typeof(y));  // Output will be : Number
    ``` 
    ---

   * String : It is used to store strings and for storing string we have to use either single quote __' '__ or double quote __" "__ bothe are allowed. We can store number as a string using double quotes.

    __To check the data type of any variable we can use : typeof() function.__

    ```JavaScript
      var x="1";
      var y="Sunday";
      // Let's check the data type of these two variables using typeof() function
      console.log(typeof(x));  // Output will be : String
      console.log(typeof(y));  // Output will be : String
    ``` 
    ---

    * Boolean : In JavaScript boolean returns either true or false. It can be used as a function that has some condition for true and false.

    __To check the data type of any variable we can use : typeof() function.__

    ```JavaScript
      var x="true";
      var y="false";
      // Let's check the data type of these two variables using typeof() function
      console.log(typeof(x));  // Output will be : Boolean
      console.log(typeof(y));  // Output will be : Boolean
    ``` 
    ---

    * Undefined : In JavaScript when we declare any variable not assigned any value to that then the type of the variable will be undifined.
    In simple words... When any variable don't have any type the that is undefined. Null is another type.

    __To check the data type of any variable we can use : typeof() function.__

    ```JavaScript
      var x=;
      var y="undefined";
      // Let's check the data type of these two variables using typeof() function
      console.log(typeof(x));  // Output will be : Undefined
      console.log(typeof(y));  // Output will be : Undefined
    ``` 
    ---

    * Null : It is used for null value.

    __To check the data type of any variable we can use : typeof() function.__

    ```JavaScript
      var x=;
      var y="Null";
      // Let's check the data type of these two variables using typeof() function
      console.log(typeof(x));  // Output will be : Undefined
      console.log(typeof(y));  // Output will be : Null
    ``` 
    ---

    * Symbol : Symbol introduced just few years ago, it is a very peculiar data type that is used for symbols.

    ---
2. Non-Primitive Data Types : Objects and Arrays are considerd as        non-primitive data types in JavaScript.
    * Object : Objects are used to store collection of data and it has key-value pair. Object In JS object are define using {} .

     ```JavaScript
      var personal_info={name:"Sanket",pass:"sanket"};
      
      // Let's check the data type of variables using typeof() function
      console.log(typeof(personal_info));  // Output will be : Object

    ``` 
    __We can add new values to the variable__
    
    syntax: Object_name.keyname= "value";
    ```JavaScript
      var personal_info={name:"Sanket",pass:"sanket"};
      
      // Let's add a new value..
      console.log(personal_info.age="21");  
      // Output will be : Object
      personal_info={name:"Sanket",pass:"sanket",age=21}
    ``` 
    ---

   * Array :  In JavaScript, arrays are the nothing but the more properties of an objects. Arrays are define using [].
   
   ```JavaScript
      var num=[1,2,3,4,5];
      
      // Let's check the data type of variables using typeof() function
      console.log(typeof(num));  // Output will be : Array

      // Let's access the index of array num 
       console.log(num[3]);
      // Output will be :  4
    ``` 

## Identifiers : 
> An identifier is used to identifies a variable or functions.
Every variable or fuction has a unique name.

__Rules for creating Identifiers :__

* A JavaScript identifier must start with a letter or underscore  _  or dollar sign $.
* Identifier are case sensitive in JS.
* Identifier must start with a letter, it can be start with dollar sign or underscore.
* Reserved words(Some special characters) cannot be used as Idetifier.

## Reserved words :
> Keywords are tokens that have special meaning in JavaScript.

exp : new , return , switch , this , throw , try , typeof , var , void, break , case , catch , continue , debugger , default, while , and with , delete , do , else , finally , for , function , if , in , instanceof.

## Operators : 
> In JavaScript, Operators are special symbols that are used to perform some mathematical or logical operation and give desired output.

1. Arithmatic Operator :

     | Operator      | Syntax | Description
     | ----------- | ----------- | ----------- |
     | +      | x+y       | It will add both the numeric operands. |
     | -   | x-y        | It will subtract second numeric operand from first one. |
     | * | x*y | It will multiple both the numeric operands. |
     | / | x/y | It will give divide.
     | % | x%y | Modulus will give remainder as output. |
     | ++ | x++ | Increment  |
     | -- | x-- | Decrement |

2. Assignment Operator :
Let suppose :- var x = 2, y = 5;
     | Operator      | Example | Description
     | ----------- | ----------- | ----------- |
     | =      | x=y; // x will be 5       | Assigns right operand value to left operand |
     | =+   | x+=1; // x will be 3    | It will add one to the left operands and assign the result to left operand |
     | -= | x-=1; // x will be 1  | It will subtract one to the left operands and assign the result to left operand |
     | *= | x*=5; // x will be 10 | It will multiply left and right operand values and assign the result to the left operand
     | /= | x/=2; // x will be 1 |It will divide left operand value by right operand value and assign the result to the left operand |
     | %= | x%=1; // x will be 1 | It will give the modulus of left operand divide by right operand and assign result modulus to left operand  |

    --- 
3. Comparison Operator :
Let suppose :- var x = 2, y = 5, z=2;
     | Operator      | Example | Stand for
     | ----------- | ----------- | ----------- |
     | ==     | x==y; // Result is false       | Equal to |
     | ===   | x===2; // Result is true   | Equal to and equal type |
     | != | x!=y; // Result is false  | Not equal to  |
     | > | y>x; // Result will be true | greater than
     | >= | x>=2; // Result will be true | greater than equal to  |
     | < | x<y // Result will be true | less than  |
     | <= | x<=y // Result will be true | less than equal to
    
    ---

4. Logical Operator : 
    
     ![Screenshot (85)](https://user-images.githubusercontent.com/88035158/127876781-cc0e3fde-ec4a-4456-a592-e6912722d540.png)

5. Type Operator :

     | Operator | Description |
     | -------- | ----------- |
     | typeof   | It will return the type of that variable |
     | instance of | It will return true if the object is the intance of intence type |

6. Ternary Operator :
In programming language if we want to print any conditional program then we simply use if-else statement for execution but we can use the ternary operator as the shortcut for the if-else statement as follows:

    __syntax: condition ? expression_1 : expression_2;__

     The condition is an expression that evaluates to a Boolean value either true or false. If the first condition is true, the ternary operator returns expression_1, otherwise it returns the expression_2.

## Conditional Statement :
Conditional statements are used to perform conditional operations.
  
  * If 
  
  >The block of code will get executed when the if-condition is true.

  ```JavaScript
     if(condition){
       // the block of codes to be executed if condition gets true
     }
  ```
  * else 
  >The block of code will get executed when the if-condition is false.
   ```JavaScript
     if(condition){
       // the block of codes to be executed if condition gets true
     }
     else{
      // the block of codes to be executed if condition gets flase
     }
  ```
  * else-if
  > When we have more than one conditions then we can use else-if statement to execute the block of codes.
  ```JavaScript
     if(condition){
       // the block of codes to be executed if condition gets true
     }
     else if{
      // the block of codes to be executed else-if condition gets true
     }
     else{
       // the block of codes to be executed if all conditions  get flase
     }
  ```

  * Switch case
  > To select one condition amongst many conditions we use __Switch Case Statement .__
  ```JavaScript
     switch(expression){
     case 1 :
       // block of codes to be executed 
     break;
     case 2 :
       // block of codes to be executed 
     break;
     default:
       // block of codes to be executed   
    }
  ```
## Loop Controls :
  * For loop 
  > For lop is used if we want to run the same code over and over again.
 
  __syntax :__ 
  ```JavaScript
     for(initialization, condition, increment/decrement)
     {
         // block of codes to be executed 
     }
  ``` 

  * While 
  > While loop prints the block of code over and over again as long as specified condition is true.

  __syntax :__ 
  ```JavaScript
     while(condition)
     {
        // code block to be executed
     }
  ``` 

   * Do-While 
  > It is the next level of While statement. Do-While prints specified block of code without checking the condition, and then it checks the condition and repeat it as long as the specified condition is true.

  __syntax :__ 
  ```JavaScript
     do
     {
        // code block to be executed
     }while(conditon);

  ``` 
  * Break
  > The break statement is used to jump out of a loop. It can only be used inside a loop or a switch statement.

  __syntax :__
  ```JavaScript
     break;
  ```
  * Continue
  > The continue statement is used to break an iteration if the specified condition is true and it will jump in the next iteration. It can only be used inside a loop.


  __syntax :__
  ```JavaScript
     continue;
  ```