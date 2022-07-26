
### This topic is very important becouse it teach you how to loop throught components or other items faster than Using Loops

<br>
<hr><hr><hr>
<br>

# Reading

## Map Function

### What does .map() return?
- Return a new array performing a function 

<hr>

### If I want to loop through an array and display each value in JSX, how do I do that in React?

- we use .map() function to loop through the array and we return the result that we want using curly braces {}

<hr>

### Each list item needs a unique **True**

<hr>

### What is the purpose of a key?
-  help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity:

<hr><hr>

## Speed operator

### What is the spread operator?
- adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments

<hr>

### List 4 things that the spread operator can do ?
1) Copying an array
2) Concatenating or combining arrays
3) Using Math functions
4) Using an array as arguments

<hr>

### Give an example of using the spread operator to combine two arrays ?

```
  let cars1 = ["Nissan", "Toyota"];
  let cars2 = ["Ford", "VW"];
  let allCars = [...cars1, ...cars2];
  
  Output:
  ["Nissan","Toyota","Ford","VW"]

```
<hr>

### Give an example of using the spread operator to add a new item to an array? 

```
let Nums = [1, 2, 3];
let newNum = 4;
let Nums = [...Nums, newNum];

Output:
[1,2,3,4]

```

<hr>

### Give an example of using the spread operator to combine two objects into one ?

```
let Car = {
    Model : 'Ford'
    Year: 2022,
};


let Parts = {
    inParts: 'Seats',
    outParts: 'Wheels'
};

let employee = {
    ...Car,
    ...Parts
};


Output:
{
    Model : 'Ford',
    Year: 2022,
    inParts: 'Seats',
    outParts: 'Wheels'
}

```

<br>
<hr><hr><hr>
<br>

# Video

## How to Pass Functions Between Components


### what is the first step that the developer does to pass functions between components?
- creat a function and pass the state into it to so we can make a setstate 

<hr>

### In your own words, what does the increment function do?
- It checks if the name that is inserted equals the name thats already in the constructor; then the count will increase by one and it will be updated.

<hr>

### How can you pass a method from a parent component into a child component?
- Simply call the method in any element in child component.

<hr>

### How does the child component invoke a method that was passed to it from a parent component?
- You decide that by the method that you want, in the video it was by clicking a button.

<hr>

## Things I want to know more about
