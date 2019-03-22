# Csharp-questions-1

### 1. What is a namespace?
#### A namespace in C# is used as an organizational tool for classes in big projects.
[namespace](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/namespaces/)

### 2. What are value types?
#### A  value type gives a description about that specific value. It's important to know that setting up functions can be different depending on its value type.
[valuetypes](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/value-types)

### 3. What are reference types?
#### A reference type stores data about objects. Yet unlike value types you can have to two variables referencing the same object.
[reference types](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/reference-types)

### 4. What is an automatic property and how is it useful?
#### Automatic property is ultimately a shortcut in writing code, this is useful because it saves time and makes mental processing easier.
[automatic property](https://gunnarpeipman.com/csharp/automatic-properties/)

### 5. What is the purpose of using statement?
#### The using statement is used to read objects with the help of the compiler.
[using statement](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/using-statement)

### 6. What are dynamic type variables?
#### Dynamic variables are recognized at run time instead of compiled time.
[dynamic type](https://visualstudiomagazine.com/Articles/2011/02/01/Understanding-the-Dynamic-Keyword-in-C4.aspx)

### 7. What is the purpose of the is operator?
#### The is operator is used to check objects compatibility with their given type.
[is operator](https://www.techopedia.com/definition/27691/is-operator-c)

### 8. What are generics and how is using them useful?
#### Generic allow you to create a class with place holders for things such as methods and parameters. They can be useful because it increases reusability of your code.
[generics](https://www.tutorialsteacher.com/csharp/csharp-generics)

### 9. What is the scope of a public member of a class?
#### Public members can be used outside the class through functions or other classes.
[public member](https://www.youth4work.com/Talent/C-Plus-Plus/Forum/117087-explain-public-protected-private-in-c)

### 10. Can you create a function that can accept a varying number of arguments?
#### Yes this is possible in C#, how you do it is through params.
[params](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/params)

### 11. How do you sort an array?
#### You can sort an array by using array.sort, this will take your array no matter the order and put it in alphabetical or lowest to highest value.
[sort an array](http://www.csharp-examples.net/sort-array/)

### 12. What is a nullable type and what purpose does it serve?
#### A nullable type allows you to assign null to value type variables, the purpose they serve is that they can be a wide range of numbers
[nullable type](https://www.tutorialsteacher.com/csharp/csharp-nullable-types)

### 13. What is an enumeration?
#### Enumerations or enums are a set of named integers that are constants.
[enumeration](https://www.tutorialspoint.com/csharp/csharp_enums.htm)

### 14. What is inheritance?
#### Inheritance is when you create a (child) class that has a lot of the same functionality as previous one (parent).
[inheritance](https://www.techopedia.com/definition/27987/inheritance-c)

### 15. Is multiple inheritance supported?
#### Unfortunately C# does not allow multiple inheritance, but it does allow multiple interfaces.
[multiple inheritance](https://stackoverflow.com/questions/21716747/does-c-sharp-support-multiple-inheritance-4-0)

### 16. What is the purpose of as operator?
#### The as operator is not a boolean type, instead its used for nullables and returns a null if the conversion is not possible.
[operator](https://www.geeksforgeeks.org/is-vs-as-operator-keyword-in-c-sharp/)

### 17. What is an object?
#### An object in C# is a property within a class, for example a dog is an object to the class pet.
[object](https://www.techopedia.com/definition/3232/object-c)

### 18. What is the difference between a struct and a class?
#### Because they are similar the difference is when you would use them. For struct I would use it in a data grouping case. Yet if I were to be combining functions and wanted flexibility I would use a class.
[struct vs class](http://net-informations.com/faq/oops/struct.htm)

### 19. What is the difference between continue and break statements?
#### A Break can be in a switch and loop statements, while Continue statement can only be in a loop statement.
[continue vs statements](http://cs-fundamentals.com/tech-interview/c/difference-between-break-and-continue-in-c-language.php#break-vs-continue)

### 20. What is this and how is it used?
#### The This keyword is used to refer to the current instance of the class. But can also be used to call another constructor from the same class.
[this](https://www.tutorialspoint.com/this-keyword-in-Chash)

### 21. What is try and catch and when are they used?
#### A try focuses on which code you want to monitor, the catch is activated if there is an error in the try. These blocks are used for a stronger code overall and allows for problem solving.
[try and catch](https://stackify.com/csharp-exception-handling-best-practices/)

### 22. How is exception handling done?
#### Exception handling is done through writing things such as try, catch, and throw, in your code so that if an exception occurs your program can possibly fix it self instead of crashing.
[exception handling](https://www.tutorialspoint.com/csharp/csharp_exception_handling.htm)

### 23. What is finally and what is its purpose?
#### The finally block is what will run after the try catch. The purpose is to allow the code to continue to run without crash.
[finally](https://www.geeksforgeeks.org/c-sharp-finally-keyword/)

### 24. List the differences between Array and ArrayList.
#### An array is a collection of the same type of data that are a fixed length and can not be changed at run time. An arraylist can store values of different data types where size does not matter and can be changed at run time.
[array vs arraylist](https://www.c-sharpcorner.com/blogs/difference-between-array-and-arraylist-in-c-sharp)

### 25. What is an object?
#### An object in C# is a property within a class, for example a dog is an object to the class pet.
[object](https://www.techopedia.com/definition/3232/object-c)

### 26. Define constructor.
#### A constructor in C# is a way a programer can set the initial value for variables.
[constructor](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/using-constructors)

### 27. When can var be used to declare a variable and how is the type for the variable determined?
#### When using var before a variable along with setting it equal to something you are asking the computer to choose what value type you want your variable to be at compiling time.
[var](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/var)

### 28. What is an abstract class?
#### An abstract class is used to provide a base class that multiple classes can use. This in return gives reusability in the writing process.
[abstract class](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/abstract-and-sealed-classes-and-class-members)

### 29. What is an interface?
#### Interfaces can contain things like methods or properties but not constants and or operators. It is also important to know that Interfaces have to be public.
[interface](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/interfaces/)

### 30. What is a method?
#### A method is how the computer reads your code. The most common practice for this is called the main method.
[method](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/methods)

### 31. What is a property?
#### Properties are the way in which classes set their values. This can be achieved through the get and set properties.
[property](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/properties)

### 32. What is an access specifier?
#### Access specifiers determine whether or not that code belongs there.
[access specifier](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/access-modifiers)

### 33. What access specifiers are supported and what do they mean?
#### The access specifiers valid in C# are: public, private, protected, internal, protected internal and private protected. The name correlated with how they are accessed.
[types of access specifiers](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/access-modifiers)

### 34. What is a collection?
#### A collection is a class with a lot of flexibility they are easy to modify because they have no limit.
[collection](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/collections)

### 35. What is a Hash Table?
#### Is ultimately collection of pairs that are then organized based of the key of the hashtable.
[hash table](https://docs.microsoft.com/en-us/dotnet/api/system.collections.hashtable?view=netframework-4.7.2)
