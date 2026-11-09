# Assignment: Problem Solving with TypeScript & OOP

## Overview
This repository contains the complete solutions and blog posts for the TypeScript and OOP assignment. It demonstrates clean coding practices, explicit typing, and advanced TypeScript concepts.

## Detailed Summary of Solved Problems (`solutions.ts`)
- **Problem 1 (Multiplier Function):** Implemented a function with default parameters (`multiplier: number = 2`) to handle basic arithmetic and optional values correctly.
- **Problem 2 (Input Processor & Type Narrowing):** Handled union inputs (`string | number | boolean`) using `typeof` type narrowing to perform specific string manipulation, numeric formatting, and boolean inversions.
- **Problem 3 (Coordinate Formatter):** Used read-only tuples (`readonly [number, number, string]`) to ensure immutability when processing geographical or coordinate data.
- **Problem 4 (Array Concatenation with Generics):** Combined rest parameters with TypeScript generics (`<T>`) to dynamically merge multiple arrays of any type safely.
- **Problem 5 (Course Catalog Filter):** Created structured interfaces (`Course`) and utilized immutable array filtering methods (`.filter()`) to extract popular courses based on ratings without mutating the original data.
- **Problem 6 (Generic Plucker):** Implemented advanced generics with `keyof` constraints (`<T, K extends keyof T>`) to safely extract property values from objects.
- **Problem 7 (OOP - Employee & Manager Hierarchy):** Designed class structures applying Object-Oriented Programming principles including inheritance (`extends`, `super`), encapsulation, and access modifiers (`private`, `protected`, `public`).
- **Problem 8 (Asynchronous Age Validator):** Managed asynchronous execution using TypeScript-typed Promises (`Promise<string>`), `setTimeout`, and error handling for conditional resolution and rejection.

## Blog Posts
- [Generics](./Generics.md) how do they help when working with asynchronous Promise<T> responses?
- [Type Narrowing](./type-narrowing.md) Details type narrowing techniques utilizing operators like `typeof` and `instanceof` for robust type safety.

## Author
Md Sadman Islam Tanvir