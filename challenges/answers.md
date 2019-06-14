1. Describe the biggest difference between .forEach & .map.

The biggest difference is that.map returns a new array while .forEach doesn't.
Because .map returns a new array, it allows you to modify that new array thats created 
instead of just having to change the original arrray like you would have to do in .forEach. 


2. What is the difference between a function and a method?

A method is a function where there is an object associated with that function. But, when there isn't an 
object to associate with that function, it just remains a function. 


3. What is closure?

Closure refers to when a function is being declared but a variable in that function that is being referenced 
lies on the outer scope of that function. Closure occurs when the function reaches outside of their local scope
to grab the properties of what is being referenced.


4. Describe the four rules of the 'this' keyword.

    1. Global binding -
    'This' keyword defaults to the window Object when a function is declared but none of the other 'this' rules 
    can be applied. 

    2. Implicit binding -
    'This' in implicit refers to the Object to the left of the dot that is placed when invoking a function. 

    3. New binding -
    'This' applied to the newly constructed item/instance of the Object that is being created as a result of the
    'new' keyword

    4. Explicit binding -
    'This' keyword is referring to whatever is being explicitly referenced in the function when .call or .apply 
    is being used to change what the objects are being set to



5. Why do we need super() in an extended class?

Super in an extended class is necessary because it is telling that extended class to implement the parent attributes to that extended class. It's taking place of Object.create and without it the extended classes wouldn't
be able to inherit the attributes of their parent class through the parent class constructor. 


