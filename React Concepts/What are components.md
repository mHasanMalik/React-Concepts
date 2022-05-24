# What are components ?
> Reusable building blocks in your user interfaces.
> Components are just a mixer of some `html` code. Some `css` for styling & `js` code for some logic.



### What can we achieve with the components ?
1. Reusability
    - Don't repeat yourself.
2. Separation of concerns.
    - Don't doo too many things in one and the same place (function)


A component in react is just a function. That can take certain argument and then return JSX based on those arguments. Each component has it's own state and we can also pass props to a component.

> Few points to keep in mind while creating a component:
>> 1. A component name should be capital. A simple rule in react is that, Lower case elements are for the build in html elements. Whereas the capital element means a custom element i.e a component.
>
>> 2. Each component should only contain one root element. i.e all the elements should be nested under one parent element. That parent element can be a `<div>` etc.
>
>> 3. You can run any valid Javascript expression inside a JSX of a component using the `{}` brackets. e.g ```<h2>{1+1}</h2>```. This would display 2 on the runtime. Since 1+1 is a valid Javascript expression.
