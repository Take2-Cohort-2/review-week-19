# Review Week 19

# TypeScript 

**Instructions**: Choose the best answer for each question. Mark your answers A, B, C, or D.

---

## Question 1
What is TypeScript?

A) A completely new programming language unrelated to JavaScript
B) A superset of JavaScript that adds static type checking
C) A JavaScript framework for building web applications
D) A database query language

---

## Question 2
Which company created TypeScript and what was their main motivation?

A) Google created it to compete with JavaScript
B) Microsoft created it to address JavaScript's lack of static typing for large applications
C) Facebook created it to improve React development
D) Apple created it to replace JavaScript entirely

---

## Question 3
Where can TypeScript be used?

A) Only in frontend web applications
B) Only in backend Node.js applications
C) Both frontend and backend applications
D) Only in mobile app development

---

## Question 4
What will happen when you try to compile this TypeScript code?
```typescript
let age: number = 25;
age = "twenty-five";
```

A) It will compile successfully and run without errors
B) It will compile but cause a runtime error
C) It will cause a TypeScript compilation error
D) It will automatically convert the string to a number

---

## Question 5
Which of these is the correct way to declare an array of numbers in TypeScript?

A) `let numbers: [number] = [1, 2, 3]`
B) `let numbers: number[] = [1, 2, 3]`
C) `let numbers: array<number> = [1, 2, 3]`
D) `let numbers: number{} = [1, 2, 3]`

---

## Question 6
What is type inference in TypeScript?

A) The process of converting TypeScript to JavaScript
B) TypeScript's ability to automatically determine types without explicit annotation
C) A method for importing types from other files
D) The process of checking types at runtime

---

## Question 7
In this interface definition, what does the `?` symbol mean?
```typescript
interface User {
  id: number;
  name: string;
  email?: string;
}
```

A) The email property is required
B) The email property is a question string
C) The email property must be a string or undefined
D) Both B and C are correct

---

## Question 8
Which function definition is correct in TypeScript?

A) `function add(a, b): number { return a + b; }`
B) `function add(a: number, b: number) { return a + b; }`
C) `function add(a: number, b: number): number { return a + b; }`
D) `function number add(a: number, b: number) { return a + b; }`

---

## Question 9
What is a union type in TypeScript?

A) A type that represents the combination of two objects
B) A type that can be one of several types
C) A type that must include all specified types
D) A type used only for mathematical operations

---

## Question 10
Which of these is a valid union type declaration?

A) `let id: number + string`
B) `let id: number & string`
C) `let id: number | string`
D) `let id: number, string`

---

## Question 11
What does the `readonly` keyword do in this TypeScript interface?
```typescript
interface User {
  readonly id: number;
  name: string;
  email: string;
}
```

A) Makes the property private and inaccessible
B) Prevents the property from being modified after object creation
C) Makes the property optional
D) Converts the property to a string type

---

## Question 12
In this code, what type will TypeScript infer for the variable `country`?
```typescript
let country = "USA";
```

A) `country`
B) `string`
C) `object`
D) `unknown`

---

## Question 13
Which statement about the `any` type is correct?

A) It should be used frequently to make TypeScript more flexible
B) It provides the same type safety as other TypeScript types
C) It should be avoided as it defeats the purpose of TypeScript
D) It can only be used with primitive types

---

## Question 14
Which of these variables can store both numbers and strings?

A) `let value: number = 5;`
B) `let value: string = "hello";`
C) `let value: number | string = 5;`
D) `let value: any = 5;`

---

## Question 15
Which of these is a correct way to define an interface for a car?

A) ```typescript
   interface Car {
     make, model: string;
     year: number;
   }
   ```

B) ```typescript
   interface Car {
     make: string,
     model: string,
     year: number
   }
   ```

C) ```typescript
   interface Car {
     make: string;
     model: string;
     year: number;
   }
   ```

D) ```typescript
   interface Car {
     string make;
     string model;
     number year;
   }
   ```

---

## Question 16
What is wrong with this TypeScript code?
```typescript
let numbers: number[] = [1, 2, 3];
numbers.push("four");
```

A) Nothing is wrong
B) You cannot push to an array in TypeScript
C) You cannot assign a string to a number array
D) The array declaration is incorrect

---

## Question 17
How do you declare a variable with a specific type in TypeScript?

A) `let name = string "Alice"`
B) `let name: string = "Alice"`
C) `let name<string> = "Alice"`
D) `let string name = "Alice"`

---

## Question 18
What is a tuple in TypeScript?

A) An array that can hold any number of elements of any type
B) An array with a fixed number of elements where each element can have a different type
C) A function that returns multiple values
D) An object with numbered properties

---

## Question 19
In TypeScript, what does this syntax mean: `Array<string>`?

A) A string that contains an array
B) An array of strings
C) A function that returns strings
D) An object with string properties

---

## Question 20
What will be the value of `Colour.Green` in this TypeScript enum?
```typescript
enum Colour {
  Red,
  Green,
  Blue
}
```

A) "Green"
B) 1
C) 2
D) undefined
