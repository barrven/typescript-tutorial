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
          "esModuleInterop": true,
          "outDir": "./dist"  // This line specifies the output directory
        },
        "include": ["src"]  // This line specifies the directory containing the TypeScript files
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
