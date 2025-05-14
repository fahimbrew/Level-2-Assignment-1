# 🛠 TypeScript: Interface vs Type (Plus Union & Intersection Examples)

There are some massive differences between Interface and Type. If you’ve been working with TypeScript for a while, you’ve probably seen both interface and type. They both let you define shapes for objects, so it’s easy to wonder — what’s the difference? And when should you use one over the other?

What is an interface?

An interface is used to describe the shape of an object. It’s like a blueprint that says what properties an object should have.


interface User {
  name: string;
  age: number;
}

const person: User = {
  name: "Fahim",
  age: 25,
};

What is a type?

A type can also describe an object (just like an interface), but it can do more. You can use it for primitives, unions, intersections, and more.


type User = {
  name: string;
  age: number;
};

🧠 When to Use Which?

Use an interface when you’re defining the structure of an object or class.

Use type when you need more flexibility, like combining multiple types or creating unions.

💡 Tip:
If you're describing a thing → use interface
If you're combining things or making choices → use type
