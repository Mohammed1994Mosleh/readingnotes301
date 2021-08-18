# Readings for Class10 : In memory storage

## Javascript Call Stack:
![call stack](https://i.ytimg.com/vi/2ZH_1d8TYVg/maxresdefault.jpg)

1.  data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).
2. 
3. the last function that gets pushed into the stack is the first to be pop out, when the function returns.

4. unction firstFunction(){
  throw new Error('Stack Trace Error');
      }

    function secondFunction(){
  firstFunction();
    }

   function thirdFunction(){
       secondFunction();
    }

   thirdFunction();

5. ccurs when there is a recursive function (a function that calls itself) without an exit point

## JavaScript error messages && debugging
1.This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

2. his occurs when you have something that cannot be parsed in terms of syntax

3. bject indicates an error when a value is not in the set or range of allowed values.

4. Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

5. laces where code execution can be stopped

6. Searching for (and fixing) errors in programming code is called code debugging.

