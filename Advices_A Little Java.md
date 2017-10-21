### Advices of A Little Java
1. When specifiying a collection of data,use abstract classes for datatypes and extended classes for variants.
2. When writing a function over a datatype,place a method in each of the variants that make up the datatype.If a field of a variant belongs to the same datatype,the method may call the corresponding method of the field in computing the function.
3. When writing a function that returns values of a datatype,use **new** to create these values.
4. When writing several functions for the same self-referential datatype,use** visitor protocols** so that all methods for a function can be found in a single class.
6. When the additional consumed values change for a self-referential use of a visitor,don't forget to create a new visitor.
7. When desigining visitor protocols for many different types,create a unifying protocol using Object.
8. When extending a class,use overriding to enrich its functionality.
9. if a datatype may have to be extended,be forward looking and use a constructor-like (overridable) method so that visitors can be extended,too.
10. When modifications to objects are needed,use a class to insulate the operations that modify objects.Otherwise,beware the consequences of your actions.