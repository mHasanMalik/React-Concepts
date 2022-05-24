# JSX

JSX stands for javascript XML. Because html in the end is XML.
```
function App() {
    return (
        <div>
            <h2>This is what the JSX syntax looks like</h2>
        </div>
    );
}
```


Lets take another example of component code containing a custom component named `Expenses`.

```
import Expenses from "./components/Expenses";

function App() {
    return (
        <div>
            <h2>Let's get started!</h2>
            <Expenses expenses_data={expenses}/>
        </div>
    );
}
```

In the above example. We can see how JSX made our lifes easier. Buy just writing code in HTML style. We can build many components. These components are very easy to read as well.

Now, Let's take a closer look at how JSX works under the hood. We will rewrite the same JSX code but this time, we'll use the `React` library from our packages.

```
import Expenses from "./components/Expenses";
import React from 'react';

function App() {
    return React.createElement(
        'div',
        {},
        React.createElement('h2', {}, 'Let\'s get started!'),
        React.createElement(Expenses, {expenses_data: expenses})
    );
}
```

The above `React.createElement` will output the same content as the `JSX` code we wrote before that. The difference is, the JSX was very easy to read & less prone to human errros.
Also the JSX code would be much easier to modify without errors.
 