# Exports and Imports

In React projects (and actually in all modern JavaScript projects), you split your code across multiple JavaScript files - so-called modules. You do this, to keep each file/ module focused and manageable.

To still access functionality in another file, you need *export*  (to make it available) and *import*  (to get access) statements.

You got two different types of exports: 
- default (unnamed)
    `export default ...;`
- named exports
    `export const someData = ...;`

You can import *default* exports like this:
```
import someNameOfYourChoice from './path/to/file.js';
```
Surprisingly, `someNameOfYourChoice`  is totally up to you.


*Named* exports have to be imported by their name:
```
import { someData } from './path/to/file.js'; 
```

> A file can only contain one default and an unlimited amount of named exports. You can also mix the one default with any amount of named exports in one and the same file.
