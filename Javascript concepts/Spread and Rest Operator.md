# Spread and Rest Operator

The spread and rest operators actually use the same syntax: `...`

Yes, that is the operator - just three dots. It's usage determines whether you're using it as the spread or rest operator.

### Using the Spread Operator:

The spread operator allows you to pull elements out of an array (=> split the array into a list of its elements) or pull the properties out of an object.

#### Here are two examples:

```
const oldArray = [1, 2, 3];
const newArray = [...oldArray, 4, 5;    // This now is [1, 2, 3, 4, 5];
```

Here's the spread operator used on an object:
```
const oldObject = {
    name: 'Hasan'
};

const newObject = {
    ...oldObject,
    age: 25
};
```

`newObject` would then be
```
{
    name: 'Hasan',
    age: 25
}
```


### Using the Rest Operator:

The rest parameters syntax allows a function to acept an indefinite number of arguments as an array.

#### Here is an example:

```
function sortTheArray(...theArgs) {
    return theArgs.sort();          // Since "theArgs" is an array. We can perform "array" operations on it.
}
```
