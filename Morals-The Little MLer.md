
### morals in The Little MLer

1. use datatype to describe types.When a type contains lots of values,the datatype definnition regers to itself.Use a with datatype to define shapes
2. The number and order of the patterns in the definition of a function should match that of the definition of the consumed datatype.
3. Functions that produce values of a datatype must use the associated constructors to build data of that type.
4. Some functions consume values of star type;some produce values of a star type.
5. Write the first draft of a function following all the morals.When it is correct and no sonner,simplify.
6. As datatype definitions get more complicated,so do the functions over them.
7. Some functions consume values of arrow type;some produce values of arrow type.
8. Replace stars by arrows to reduce the number of values consumed and to increase the generality of the function defined.
9. Some functions produce exceptions instead of values;some don't produce anything.Handle raised exceptions carefully.
10. Real programs consist of many component.Specify the dependencies among these components using signatures and functors.



