# let and const

#### Q. When and why to use let and const ?

> A very simple rule of thumb is:
>> Use "let" if you are planning to create a varaible. Whose value can be changed.
>
>> Use "const" if you are planning to create a constant. A contant is declared once & never changed throughout the program cycle.

Different ways of creating variables.

- var
    - let
        - variable value
    - const
        - constant value


### Code Example:

#### Open a browser console and run the following code snippets.

```
var myName = 'Hasan';
console.log(myName);

myName = 'Hasan Hasan';
console.log(myName);
```

#### The above code will run without any problems.

#### Lets change the same above code snippet to use the "const".

```
const myName = 'Hasan';
console.log(myName);

myName = 'Hasan Hasan';
console.log(myName);
```

#### The above code will crash/break with an error. "Assignment to constant variable".

> Read more about *let*: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let
>
> Read more about *const*: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const

