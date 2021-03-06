# Introduction to TypeScript

## Learning Goals

- Understand TypeScript at a high level
- Explain some of the benefits of using TypeScript when developing web applications

## Introduction

If you've ever worked with JavaScript, you've undoubtedly run into bugs that took
what felt like forever to find the root of, weird errors, or lack-there-of,
(Looking at you, `'undefined' is not a function`), and cursed the JavaScript gods
for allowing such problems to always happen. If this sounds familiar, then
TypeScript may be the answer to your curses.

A superset of JavaScript, TypeScript was created by Microsoft in 2012 to help
developers write code, and catch errors and bugs quickly and efficiently. This
allows developers like you to put your energy and focus towards designing a good
experience for end users of the application.

In this lesson, we will discuss what exactly TypeScript is and why it is so
awesome and useful.

## TypeScript Overview

In a study done for the [2021 State of JS][state-of-js], 69% of the developers
polled said they preferred to use TypeScript as their JavaScript compiler, and
in the Github study, [Top Languages Over The Years][top-languages], TypeScript
came in as the #4 most popular language for 2 years in a row! (2020-2021)

![Octoverse - Top Languages Over The Years 2021 Image](https://curriculum-content.s3.amazonaws.com/blackrock/intro-to-typescript/top-languages-used-2021.png)

As mentioned above, TypeScript is a superset of JavaScript... so what does that
mean? A superset expands and elaborates on all the parts of a language, while
still fully encompassing the entirety of the original language.

Think about JavaScript before ES6. If you were writing a program in ES5 or
before, and tried to use `const` to declare a constant variable, it wouldn't
work, right? But if you were writing your program using ES6 and wanted to go old
school and use `var` to declare your constant variable, it would still work, but
you would be opening your code up to a lot of potential bugs in the future. The
same idea goes for TypeScript. We can write regular JavaScript code into a
TypeScript file and it will work fine, but by using TypeScript it will work a
whole lot better, and save us a lot of debugging and hair-pulling down the line.

TypeScript builds onto JavaScript by adding type-checking and type
declaration abilities for all different data-types, classes, and other
object-oriented features through its type system.

By declaring types, we can write extremely explicit JavaScript code by
telling our program what type of datatype a variable should be, what a function argument
should be, what our arrays will contain, and more!

By using this type system and the TypeScript compiler, TypeScript is able to
easily highlight and unexpected behaviors in our code, taking most of the guess
work out of debugging!

## Working with Types

We recommend getting to know the [TypeScript docs][], as they are very thorough,
easy to follow, and an all around great resource, but we wanted to go over a couple
of the ways we can work with Types in TypeScript to give you a good sense of
what the benefits of types are!

- need to re work this section
  - type asignments
  - custom types
  - error handling

## Conclusion

As you saw, TypeScript is a super helpful and powerful tool for us to write
clean and error-free code. TypeScript helps us catch errors at compile time,
makes refactoring much easier, and stops JavaScript type coercion in it's tracks!

## Resources

- [2021 State of JS][state-of-js]
- [Top Languages Over The Years][top-languages]
- [TypeScript docs](https://www.typescriptlang.org/docs/)

[state-of-js]: https://2021.stateofjs.com/en-US/other-tools
[top-languages]: https://octoverse.github.com/#top-languages-over-the-years
