
# TypeScript Interview Questions and Answers

TypeScript starts from the same syntax and semantics that millions of JavaScript developers know today. Don't miss that advanced list of TypeScript interview questions and answers and nail your next web developer tech interview in style.

> You could also find all the answers here 👉 https://www.fullstack.cafe/TypeScript.

### Q1: List the built-in types in Typescript ⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q2: What are Modules in Typescript? ⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q3:  What is Typescript and why one should use it? ⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q4: Explain generics in TypeScript ⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q5: What is TypeScript and why would I use it in place of JavaScript? ⭐


 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q6: What is TypeScript and why do we need it? ⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q7: What are the benefits of TypeScript? ⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q8: Do we need to compile TypeScript files and why? ⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q9: How to call base class constructor from child class in TypeScript? ⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q10: What are the difference beetween Typescript and JavaScript? ⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q11: What is Interface in TypeScript? ⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q12: When to use interfaces and when to use classes in TypeScript? ⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q13: What is the difference between Classes and Interfaces in Typescript? ⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q14: What is "Decorators" in TypeScript? ⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q15: What is getters/setters in TypeScript? ⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q16: How could you check null and undefined in TypeScript? ⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q17: How to implement class constants in TypeScript? ⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q18: Could we use TypeScript on backend and how? ⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q19: Does TypeScript support all object oriented principles? ⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q20: Which object oriented terms are supported by TypeScript? ⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q21: What is a TypeScript Map file? ⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q22: Explain how and why we could use property decorators in TS? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q23: Are strongly-typed functions as parameters possible in TypeScript? ⭐⭐⭐

**Questions Details:**

Consider the code:

```js
class Foo {
    save(callback: Function) : void {
        //Do the save
        var result : number = 42; //We get a number from the save operation
        //Can I at compile-time ensure the callback accepts a single parameter of type number somehow?
        callback(result);
    }
}

var foo = new Foo();
var callback = (result: string) : void => {
    alert(result);
}
foo.save(callback);
```
Can you make the result parameter in `save` a type-safe function? Rewrite the code to demonstrate.


 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q24: Is that TypeScript code valid? Explain why. ⭐⭐⭐

**Questions Details:**

Consider:
```js
class Point {
    x: number;
    y: number;
}

interface Point3d extends Point {
    z: number;
}

let point3d: Point3d = {x: 1, y: 2, z: 3};
```


 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q25: What are different components of TypeScript? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q26: How TypeScript is optionally statically typed language? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q27: What is the default access modifier for members of a class in TypeScript? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q28: How can you allow classes defined in a module to accessible outside of the module? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q29: What's wrong with that code? ⭐⭐⭐

**Questions Details:**

```js
// something is wrong
function reverse(s: String): String;
```


 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q30: Does TypeScript supports function overloading? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q31: How To Use external plain JavaScript Libraries in TypeScript? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q32: What is Typings in Typescript? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q33: What is the difference between "interface vs type" statements? ⭐⭐⭐⭐

**Questions Details:**

```js
interface X {
    a: number
    b: string
}

type X = {
    a: number
    b: string
};
```


 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q34: How would you overload a class constructor in TypeScript? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q35: Explain why that code is marked as WRONG? ⭐⭐⭐⭐

**Questions Details:**

```js
/* WRONG */
interface Fetcher {
    getObject(done: (data: any, elapsedTime?: number) => void): void;
}
```


 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q36: What is one thing you would change about TypeScript? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q37: Explain when to use "declare" keyword in TypeScript ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q38: What are Ambients in TypeScripts and when to use them? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**


### Q39: Is it possible to generate TypeScript declaration files from JS library? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/TypeScript)**



