# typescript-tutorial
Tutorial repo for learning Typescript

### Lesson Outline for Learning TypeScript

#### **Lesson 1: Introduction to TypeScript**
1. **What is TypeScript?**
   - Overview of TypeScript
   - Benefits over JavaScript
2. **Setting Up TypeScript**
   - Installing TypeScript
   - Setting up a TypeScript project

**Exercise 1:** Install TypeScript and set up a basic project.

#### **Lesson 2: Type Annotations**
1. **Basic Types**
   - Number, string, boolean
   - Arrays and tuples
2. **Type Inference**
   - How TypeScript infers types
3. **Complex Types**
   - Objects, enums, any, and union types

**Exercise 2:** Create a TypeScript file that demonstrates basic types and type inference.

#### **Lesson 3: Functions**
1. **Function Types**
   - Specifying parameter and return types
2. **Optional and Default Parameters**
   - How to handle optional and default parameters
3. **Arrow Functions**
   - Using arrow functions with types

**Exercise 3:** Write functions with different parameter and return types, including optional and default parameters.

#### **Lesson 4: Interfaces and Type Aliases**
1. **Defining Interfaces**
   - How to create and use interfaces
2. **Extending Interfaces**
   - Extending and merging interfaces
3. **Type Aliases**
   - Using type aliases for complex types

**Exercise 4:** Create interfaces and type aliases for a complex object and use them in a function.

#### **Lesson 5: Classes and Inheritance**
1. **Classes**
   - Defining and using classes
2. **Inheritance**
   - Extending classes and using super
3. **Public, Private, and Protected Modifiers**
   - Access modifiers in TypeScript

**Exercise 5:** Create a class hierarchy with at least two levels of inheritance, demonstrating public, private, and protected modifiers.

#### **Lesson 6: Generics**
1. **Introduction to Generics**
   - What are generics and why use them?
2. **Generic Functions**
   - Creating functions with generics
3. **Generic Classes and Interfaces**
   - Using generics with classes and interfaces

**Exercise 6:** Write a generic function and a generic class to handle a collection of items.

#### **Lesson 7: Advanced Types**
1. **Intersection and Union Types**
   - Combining multiple types
2. **Type Guards and Type Assertions**
   - Ensuring type safety at runtime
3. **Mapped Types and Conditional Types**
   - Advanced type manipulation

**Exercise 7:** Create examples using intersection, union, type guards, and type assertions.

#### **Lesson 8: Modules and Namespaces**
1. **Modules**
   - Importing and exporting modules
2. **Namespaces**
   - Organizing code with namespaces

**Exercise 8:** Create a module and use it in another file. Organize related code using namespaces.

#### **Lesson 9: Error Handling**
1. **Error Types**
   - Defining and throwing custom errors
2. **Error Handling**
   - Try/catch blocks and error propagation

**Exercise 9:** Implement error handling in a function that can throw multiple types of errors.

#### **Lesson 10: Advanced Configuration**
1. **tsconfig.json**
   - Configuring the TypeScript compiler
2. **Compiler Options**
   - Important compiler options and their uses

**Exercise 10:** Create a `tsconfig.json` file with custom compiler options and compile a TypeScript project.

---

### Exercises and Grading

For each lesson, I will provide exercises to reinforce the concepts. Please complete the exercises and share your code with me. I will review your code, provide feedback, and suggest improvements.

#### **Starting with Exercise 1:**

**Exercise 1:** Install TypeScript and set up a basic project.

1. **Install TypeScript:**
   - Use npm to install TypeScript globally: `npm install -g typescript`
2. **Set up a basic project:**
   - Create a new directory for your project.
   - Inside this directory, initialize a new npm project: `npm init -y`
   - Create a `tsconfig.json` file with the following content:
     ```json
     {
       "compilerOptions": {
         "target": "es5",
         "module": "commonjs",
         "strict": true,
         "esModuleInterop": true
       }
     }
     ```
   - Create a `src` folder and a `main.ts` file inside it.
   - Write a simple TypeScript program in `main.ts`, for example:
     ```typescript
     const greet = (name: string): string => {
       return `Hello, ${name}!`;
     }

     console.log(greet("World"));
     ```
3. **Compile and run the project:**
   - Compile the TypeScript file: `tsc`
   - Run the compiled JavaScript file: `node dist/main.js`

Submit your `tsconfig.json`, `main.ts`, and the compiled JavaScript file for review. Once you have completed this exercise, I'll review your work and we can proceed to the next lesson.
