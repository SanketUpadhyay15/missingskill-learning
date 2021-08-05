# JavaScript Advance
As we have seen the basic concepts of JavaScript, now we'll see next level of it. So basically now we are going to see some more advance topic of JavaScript Programming Language Like:
 
 * Array
    
   * Concept of Array
   * How to create Array
   * Built-in Methods in Array
 * Object
   
   * Various Methods to create an Object
       
       
       * using object constructor
       * using 'new' keywords
       * using object constructor 
 * String
  
   * Built-in Methods
 * What are JavaScript Functions ?
   
   * Predefined Function
   * Function Expression
   * Function Constructor
   * Self-Invoking Function
   * Function with Value
   * Function Object
   * Arrow Function
   * Generator Function
 * Constructor
   
   * Parameterised Constructor
 * What is 'this' keyword in JavaScript ?
   
   * Global Scope
   * Object's Method
   * call() or apply() method
   * bind() 
 * Hoisting
   
    * Variable Hoisting
    * Function Hoisting

 ---

## Array
__Concept Of Array :__
  > In JavaScript, Arrays are used to store multiple value at time. The JavaScript Arrays are also known as __object .__ Means if you use typeof () for any array then it will give object.
   It uses [] to store the elements.

   ```JavaScript
      let color= ["red","green","blue","2","5"];
   ```
__How to create an Array :__
   ```JavaScript
       let array_name = [item1, item2, ...];  
   ```
   ---

__Built-in Methods in Array :__
  
Let suppose : 
     var names= ["sanket","upadhyay","samal","gorai"];
| Built-in Methods | Syntax | Description |
| ----------- | ----------- | ----------- |
| indexOf()   | names.indexOf("sanket") | It is used to find the index of element.
| concat()   | var NewVar = names.concat(missingskill) | It is used to merge two array into one single array where missingkill is an array. |
| push() | names.push("Yash") | It will add Yash to last in the names array. |
| pop() | names.pop("Yash) | It will remove Yash from last position in array.|
| shift() | names.shift("sanket") | It will remove sanket from starting position in array. |
| unshift() | names.unshift("sanket") | It will add sanket at the starting position. |
| forEach() | names.forEach("gorai") | It is used to remove element at end of the array. |
| includes() | names.includes("sanket") | It is used to check wheter sanket is present in array or not.
| isArray() | Array.isArray("names") | It is used to check whether the array exist or not.|
| filter() | names.filter("sanket") | It is used to check wether it will pass the test or not. |
| slice() | names.slice("index of element") | It is used to split an array.|
| splice() | name.splice(0, 1, "Harry", "Poter") | It is used to add/remove elements in array. |
| join() | name.join() | This method give an array as a string. |

---


## Object 
  > In JavaScript, everything is an object except primitive values because privitive values don't have properties and methods.
 
  __syntax :__
    
 ```JavaScript
     new object
     object.create
     var names = {}
 ```
 ---
  __Various Methods to create an Object :__ 
  
   * using object literals 
     
     ```JavaScript
        var student={
                name:"Sanket";
                sirname:"Upadhyay";
                rollno:"100";
              }
     ```
     ---
   * using 'new' keywords 
     
     ```JavaScript
        var student = new Object();
        student.name = "Sanket";
        student.sirbane = "Upadhyay";
        student.rollno = "100";
     ```
     ---
    
   * using object constructor 
     
     ```JavaScript
        function student(name, sirname, rollno){
        this.Firstname = name;
        this.lastName = sirname;
        this.rollNo = rollno;
        }
     ```
     ---
  

     ![Screenshot (90)](https://user-images.githubusercontent.com/88035158/128081919-f080091f-2593-4ac9-b475-f2af0d1edbbe.png)

   ---

## String
| Built-in Methods      | Description |
| ----------- | ----------- |
| toUpperCase      | It converts the string into upper case       |
| toLowerCase   | It converts the string into lower case        |
| replace | It replaces a specified value with another value in a string |
| split | It slipts the string using delimiter |
| trim | It removes whitespace from both sides |
|SubString | It extracts  part from string and create new string | 

---

## What are JavaScript Functions ?
>In JavaScript, if we want to execute some block of codes in our program over and over again so we don't need to write it many time we can go for functions. So basically fuctions are the block of codes that are design to perform specified task.
A function is declare as the function keyword, followed by a name, followed by parentheses (). 

__syntax :__ 
```JavaScrpt
    function name(parameter1, parameter2) {
      // block of code to be executed
    }
```


![Screenshot (87)](https://user-images.githubusercontent.com/88035158/128015940-113b2615-8c1b-447c-a597-b7461fe27a57.png)

---

* __Predefined Function__
  
  Some functions are already predefined in JavaScript Programming, we only need to use them.
    * Eval
       >  Eval evaluates a string argumemt and returns a value.
    * parsInt
       > Parses a string argument and returns an integer value.
    * parseFloat
       > Parses a string argument and returns an floating point number.
    * escape
       > It returns the hex code of the argument.
    * unecape
       > It returns the ASCII of the argument. 

   ---

* __Function Expression__
  > Function can be defined as an expression and store return value in a variable.

  __syntax :__ 
  ```JavaScript
    var name= function (parameter1, parameter2){ return expression}
   ```
  __example :__ 
  ```JavaScript
    var x= function (a, b){ return a+b}
    var y= x(1,2)
    console.log(y);

    // Output will be 3
   ```
   ---

* __Function Constructor__
  > Functions can be created as built-in JavaScript function constructor called Function().

   __syntax :__ 
   ```JavaScript
    var VariableName1= new Function ("ParameterKey1","ParameterKey2","return expression");
    var VariableName2= VariableName1(ParameterValue1,ParameterValue2);
    console.log(Name2);
   ```
  __example :__ 
   ```JavaScript
    var Add= new Function ("a","b","return a+b");
    var result= Add(1,2);
    console.log(result);

    // Output will be: 3
   ```
   ---


* __Self-Invoking Function__
  > Self-Invoking functions get executed automatically if the expression is followed by (), you don't worry to include it.

   __syntax :__ 
   ```JavaScript
    (function{
        // code block to be excuted 
    })();
   ```
   __example :__ 
   ```JavaScript
    (function{
        console.log("Hello World !");
    })();

    // Output will be:  Hello World !
   ```
  ---

* __Function with Value__
   > It is nothing but function with parameters means it carries some value to it. First we create the function then we assign it to a variable unlike function expression.
   
    __syntax :__ 
   ```JavaScript
    function FunctionName(ParameterKey..){
        // code to be executed
    }
    let VariableName= FunctionName(ParameterValue)
   ```
   __example :__ 
   ```JavaScript
    function Add(a,b){
        return a+b;
    }
    let result= Add(2,3)
    console.log(result);
   
    // Output will be: 5
   ```
   ---

* __Function Object__
  > In JavaScript Functions are the special types of Objects called as __Function Object .__
  A function object includes a string that holds all codes.

  __syntax :__ 
   ```JavaScript
    var VariableName= "FunctionBody";
    var FunctionName= new function("ParameterList",VariableName);
    FunctionName(ParameterValue)
   ```
   __example :__ 
   ```JavaScript
    var add= "return a+b";
    var result= new function("a","b",add);
    console.log(result(2,3)) 

    // Output will be: 5
   ```
   ---

* __Arrow Function__
  > Arrow Functins are more like methods, Arrow Functions cannot be used as Constructor.
  __syntax :__ 
   ```JavaScript
    let function = (arg1, arg2.....argN) => expression
   ```
   __example :__ 
   ```JavaScript
    let Add = (a,b,c) => {return a+b+c}
    let result= Add(1,2,3)
    console.log(result);

    // output will be: 6
   ```
   ---

* __Generator Function__
   > Function Expression returns only one result at time or nothing, but Generator Function returns (yield) multiple result at a time. 
   For using Generator Function, we can use __function* .__ 

   __syntax :__ 
   ```JavaScript
    function* FunctionName(){
        yield1;
        yield2;
        return3;
    }
   ```
   ---
 ## Constructor 
 > Object instances are created using Constructor only, it is a function which like "object" but called as Constructor or blueprints. It is best practice to create a constructor with first letter in upper case.

   __example .__

   ```JavaScript
      function Colors(){
      this.hexcode= '#FF0000'; //this kewyword refers to object of class
      this.cname= function(){   
       document.write("Hex code of Red is:"+ this.hexcode);
       }
     }
     var red= new Colors();  //created constructor
     x.cname();
   
    // Output will be: Addition is: Hex code of Red is: #FF0000
   ```
   ---

   __Parameterised Constructor .__

   ```JavaScript
      Function Student(name,rollno){
      this.name = name; //this kewyword refers to object of class
      this.rollno = rollno;
    }
     
     Person.prototype.course = "Bsc.IT";  //adding new value using prototype object
     var sanket = new Person("Sanke",2,25);   //created constructor
     console.log(sasha.name,sasha.exp,this.age);

    --------------------------------------
     Output:
     Sasha 2 25
   
    // Output will be: Addition is: Hex code of Red is: #FF0000
   ```
   ![Screenshot (92)](https://user-images.githubusercontent.com/88035158/128176830-1608fe2b-b60f-42e7-8cf3-2a712701f9b7.png)

   ---
## What is 'this' keyword in JavaScript ?
> The JavaScript this keyword refers to the object it belongs. In function it belongs to global object. 

The following four rules to know which object is referred by 'this' keyword.
1. Global Scope
2. Object's Method
3. call() or apply() method
4. bind() method
## Global Scope
   
   If a function which includes 'this' keyword, is called from the global  scope. 'this' will point to the object.
   ```JavaScript
      var num = 10;

     function Function1() {
       var num = 20;

      alert("num = " + num); // 20
      alert("this.num = " + this.num); // 10
     }

     Function1(); 
   ```
   In the above example, a function Function1() is being called from the global scope. The global scope means in the context of window object. We can optionally call it like window.Function1(). So in the above example, 'this' keyword in Function1() function will refer to window object. So, this.num will return 10. However, if you access num without 'this' then it will refer to local num variable defined in Function1() function.

   ---

## Object's Method
   when you create an object of a function using new keyword then 'this' will point to that particular object. 

   ```JavaScript
      var num = 10;

      function Function1() {
      this.num = 20;
     }
     var obj1 = new Function1();
 
     var obj2 = new Function1();
     obj2.num = 30;

     alert(obj1.num); // 20
     alert(obj2.num); // 30
  ```
  ---
## call() or apply() method
   In JavaScript, a function can be invoked using () operator as well as call() and apply() method as shown below. Both will execute a function in the same way like ().

   ```JavaScript
   function Function1() {
    alert('Sanket Upadhyay');
  }
   Function1();
   Function1.call();
   Function1.apply();
   ```
   ---
## bind() 
   The bind() method can be used to set the context of 'this' to a specified object when a function is called. 
   ```JavaScript
      var num = 10;
    
    function Function(callback)
    {
      var num = 20;
       callback();
    };
      
     var obj = {
            num: 30,
            Function : function() {
                alert("'this' points to " + this + ", num = " + this.num);
            }
      };
      
     Function(obj.Function); 
     Function(obj.function.bind(obj)); 

   ```
   ---

## Hoisting
> A variable can be used before it has been declared. Yes, Hoisting is JavaScript's default behavior of moving all declarations to the top of the current scope . We only remember that in Hoisting only declarations are hoisted and not initializated.
When you execute a piece of JavaScript code, the JavaScript engine creates the global execution context.

The global execution context has two phases: __creation and execution.__

* __Variable Hoisting__ 

    In Variable hoisting, the JavaScript engine moves the variable declarations to the top of the script.  
   __example :__ __Called but not initialised__
   ```JavaScript
      console.log(num);  
      var num="3";        // variable declaration
   ```
   ---

   This program has no issue because JavaScript engine will move variable declaration to the top of the program.

   __example :__ __Initialised and then called__
    
   The above example will look like this.
   ```JavaScript
     var counter;   // variable initialisation
     console.log(counter); 
     counter = 1;   // variable declaration
   
   ```
   ---
* __Function Hoisting__

   In JavaScript, Function declaration can also be hoisted, the JavaScript engine moves the function declaration to the top of the program.

   __example :__ __Called but not initialised__
   
   
   ```JavaScript
       let x = 15,
       y = 5;
       let result = add(x,y); // function called 
      console.log(result);
      
       function add(a, b){    // fuction initialisation
        return a + b;
      }

   ```
   ---

   __example :__ __Initialised and then called__
    
   The above example will look like this.
   ```JavaScript
      function add(a, b){
      return a + b;
   }

     let x = 15,
      y = 5;

    let result = add(x,y);
    console.log(result);
  ```
   ---