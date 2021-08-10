# class03.

## React Docs - lists and keys:

1. The map() method creates a new array populated with the results of calling a provided function on every element in the calling array.

2. loop through the array using the JavaScript map() function. return a li element for each item. Finally, we assign the resulting array of elements to listItems 
3. Special key
4. Keys help React identify which items have changed, are added, or are removed

## The Spread Operator
1. The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.
2. adding items,combining arrays,Copying an array,Using Math functions

3. const cars = ['mohammed', 'audai'];
   const trucks = ['mazen', 'amer'];
   const combined2 = [...cars, ...trucks];

4. const combined = [arr,...,item];

5. const hello = {hello: "😋😛😜🤪😝"}
   const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}
   const helloWorld = {...hello,...world}


## How to Pass Functions Between Components:
1. add function and looping through array of state
2. looping through state object looking for match name and increment there count,then return the updated state array
3. by using this.props.Methodname

