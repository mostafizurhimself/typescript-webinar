# TypeScript Interview Questions for Beginners

1. What is TypeScript?

   - [ ] A JavaScript runtime environment
   - [ ] A programming language that compiles to JavaScript
   - [ ] A JavaScript framework
   - [ ] A JavaScript library

2. Which company developed TypeScript?

   - [ ] Google
   - [ ] Facebook
   - [ ] Microsoft
   - [ ] Mozilla

3. What is the file extension for TypeScript files?

   - [ ] .ts
   - [ ] .tsx
   - [ ] .typescript
   - [ ] Both .ts and .tsx are correct

4. What is the `any` type in TypeScript?

   - [ ] A type that can only hold numeric values
   - [ ] A type that represents null values
   - [ ] A type that can hold values of any type
   - [ ] A type that represents undefined values

5. What is type inference in TypeScript?

   - [ ] Manually specifying types for variables
   - [ ] The compiler's ability to automatically determine types
   - [ ] Converting one type to another
   - [ ] Checking types at runtime

6. Which of the following is the correct way to declare a variable with a specific type?

   - [ ] `let name: String = "John"`
   - [ ] `let name: string = "John"`
   - [ ] `let name: TEXT = "John"`
   - [ ] `let @string name = "John"`

7. What is an interface in TypeScript?

   - [ ] A class that cannot be instantiated
   - [ ] A contract that defines the structure of an object
   - [ ] A function that returns multiple values
   - [ ] A module system for organizing code

8. How do you declare an array of numbers in TypeScript?

   - [ ] `let numbers: number[] = [1, 2, 3]`
   - [ ] `let numbers: Array<number> = [1, 2, 3]`
   - [ ] Both of the above are correct
   - [ ] `let numbers: [number] = [1, 2, 3]`

9. What is a tuple in TypeScript?

   - [ ] An array with a fixed number of elements of different types
   - [ ] An array with unlimited elements of the same type
   - [ ] A type that represents null values
   - [ ] A function that returns multiple values

10. What is an enum in TypeScript?

    - [ ] A collection of related values as constants
    - [ ] A type for numeric values only
    - [ ] A type for string values only
    - [ ] A function that returns boolean values

11. How do you specify optional properties in an interface?

    - [ ] Using the `?` symbol after the property name
    - [ ] Using the `optional` keyword
    - [ ] Using the `?:` operator
    - [ ] Using the `undefined` type

12. What is a union type in TypeScript?

    - [ ] A type that must include all specified types
    - [ ] A type that can be one of several types
    - [ ] A type that combines two objects
    - [ ] A type that represents null or undefined

13. How do you declare a function type in TypeScript?

    - [ ] `type MyFunction = (x: number) => number`
    - [ ] `function MyFunction(x: number): number`
    - [ ] `interface MyFunction { (x: number): number }`
    - [ ] Both A and C are correct

14. What is the purpose of the `never` type?

    - [ ] To indicate that a function never returns
    - [ ] To represent null values
    - [ ] To represent undefined values
    - [ ] To indicate optional parameters

15. What is type assertion in TypeScript?

    - [ ] Automatically converting one type to another
    - [ ] Telling the compiler to treat a value as a different type
    - [ ] Checking types at runtime
    - [ ] Creating new types from existing ones

16. How do you create a generic class in TypeScript?

    - [ ] `class Container[T] {}`
    - [ ] `class Container<T> {}`
    - [ ] `class Container(T) {}`
    - [ ] `class Container{T} {}`

17. What is the purpose of the `as` keyword?

    - [ ] To perform type assertion
    - [ ] To create type aliases
    - [ ] To implement interfaces
    - [ ] To extend classes

18. What is a type alias in TypeScript?

    - [ ] A way to rename variables
    - [ ] A way to create a new name for a type
    - [ ] A way to convert types
    - [ ] A way to combine types

19. How do you make all properties in a type optional?

    - [ ] Using the `Partial<T>` utility type
    - [ ] Using the `Optional<T>` utility type
    - [ ] Adding `?` to each property
    - [ ] Using the `Maybe<T>` utility type

20. What is the difference between `interface` and `type`?

    - [ ] Interfaces can be extended, types cannot
    - [ ] Types can use unions, interfaces cannot
    - [ ] Interfaces are slower at compile time
    - [ ] There is no difference

21. How do you specify multiple types for a variable?

    - [ ] Using the `|` operator
    - [ ] Using the `&` operator
    - [ ] Using the `+` operator
    - [ ] Using the `,` operator

22. How do you make a property in an interface required?

    - [ ] Using the `required` keyword
    - [ ] By not marking it as optional
    - [ ] Using the `!` operator
    - [ ] Using the `Required<T>` utility type

23. What is the purpose of `index signatures`?

    - [ ] To define the type of object properties
    - [ ] To create indexed arrays
    - [ ] To specify array indices
    - [ ] To create object keys

24. What is the `unknown` type?

    - [ ] Similar to `any` but requires type checking before use
    - [ ] The same as `any`
    - [ ] A type for undefined values
    - [ ] A type for null values

25. How do you specify a default value for a generic type?

    - [ ] `<T = string>`
    - [ ] `<T: string>`
    - [ ] `<T | string>`
    - [ ] `<T default string>`

26. What is method overloading in TypeScript?

    - [ ] Having multiple methods with the same name but different parameters
    - [ ] Having multiple methods with different names
    - [ ] Having multiple methods with the same parameters
    - [ ] Having multiple classes with the same name

27. What is the purpose of the `Pick` utility type?

    - [ ] To select specific properties from a type
    - [ ] To remove properties from a type
    - [ ] To make properties optional
    - [ ] To make properties required

28. What is the difference between `type` and `interface` in terms of declaration merging?

    - [ ] Interfaces support declaration merging, types don't
    - [ ] Types support declaration merging, interfaces don't
    - [ ] Both support declaration merging
    - [ ] Neither supports declaration merging

29. How do you create a read-only array in TypeScript?

    - [ ] `ReadonlyArray<T>`
    - [ ] `Array<T>readonly`
    - [ ] `Readonly<Array<T>>`
    - [ ] Both A and C are correct

30. How do you specify that a property must be a string literal?

    - [ ] Using string literal types
    - [ ] Using the `literal` keyword
    - [ ] Using the `exact` keyword
    - [ ] Using the `strict` keyword

31. What is the purpose of conditional types in TypeScript?

    - [ ] To create types based on conditions
    - [ ] To create conditional statements
    - [ ] To check types at runtime
    - [ ] To convert types

32. How do you make all properties in a type required?

    - [ ] Using the `Required<T>` utility type
    - [ ] Using the `!` operator
    - [ ] Using the `required` keyword
    - [ ] Removing all optional modifiers

33. What is the purpose of the `Record` utility type?

    - [ ] To create an object type with specified keys and values
    - [ ] To record type information
    - [ ] To create arrays
    - [ ] To create tuples

34. How do you create a type that excludes null and undefined?

    - [ ] Using the `NonNullable<T>` utility type
    - [ ] Using the `Required<T>` utility type
    - [ ] Using the `!` operator
    - [ ] Using the `strict` keyword

35. How do you create a type that represents a function with any number of arguments?

    - [ ] Using rest parameters in the type definition
    - [ ] Using the `any[]` type
    - [ ] Using the `Arguments<T>` type
    - [ ] Using the `...args` syntax
