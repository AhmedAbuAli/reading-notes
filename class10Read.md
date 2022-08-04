
### This topic is very important becouse it teaches you about Errors

<br>
<hr><hr><hr>
<br>

# Reading


### What is a ‘call’?
- invoking a function 

### How many ‘calls’ can happen at once?
- Just 1 

### What does LIFO mean?
- Last In First Out

### Draw an example of a call stack and the functions that would need to be invoked to generate that call stack?
function fun1(){
    console.log("Ahmed")
}

function fun2(){
  fun1();
}

function fun3(){
  fun2();
}

fun3();


### What causes a Stack Overflow?
- A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

### What is a ‘reference error’?
-  variable that is not yet declared, 

### What is a ‘syntax error’?
-  cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

### What is a ‘range error’?
- Getting out of lenght range in objects or arrays

### What is a ‘type error’?
- Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

### What is a breakpoint?
- stop or prevent code from debugging

### What does the word ‘debugger’ do in your code?
- it lets the code has more tools to watch and fetch data and variables during excution


### Things I want to know more about
