## Readings: Data Modeling

## Name 3 advantages to Test Driven Development

1. **Better program design and higher code quality**
> When writing tests, programmers first have to define a goal they will achieve with the code piece. Developers estimate an experience it will give and the way it will match with other pieces of the entire code. A developer keeps in mind everything, from an interface to a work plan.

2. **Detailed project documentation**
> When writing tests for particular requirements, programmers immediately create a strict and detailed specification. It already includes all the likely users’ actions.

3. **TDD reduces the time required for project development**
> It’s widely known that both web and cross-platform apps like PWAs created with Test Driven Development take longer than ones created without TDD. Some sources mention the difference of about 30 percent.

![TDD](https://codica-images-production.s3.eu-central-1.amazonaws.com/2a39a5f3af33451593460e76bc648f1b.webp)

## In what case would you need to use beforeEach() or afterEach() in a test suite?

> **beforeEach()** is run before each test in a describe
> **afterEach()** is run after each test in a describe

## What is one downside of Test Driven Development

* **No silver bullet :**
> Tests help to seek out bugs, but they can not find bugs that you simply introduce within the test code and in implementation code. If you haven’t understood the matter you would like to unravel, writing tests most likely doesn’t help.

* **slow process :**
> If you begin TDD, you’ll get the sensation that you simply need an extended duration of your time for straightforward implementations. you would like to believe the interfaces, write the test code, and run the tests before you’ll finally start writing the code.

* **All the members of a team got to do it :**
> As TDD influences the planning of code, it’s recommended that either all the members of a team use TDD or nobody in the least. additionally, to the present, it’s sometimes difficult to justify TDD to the management because they often have the sensation that the implementation of latest features takes longer if developers write code that will not find themselves within the product half the time. It helps if the entire team agrees on the importance of unit tests.

* **Tests got to be maintained when requirements change :**
> Probably, the strongest argument against TDD is that the tests need to be maintained because the code has got to. Whenever requirements change, you would like to vary the code and tests. But you’re working with TDD. this suggests that you simply got to change the tests first then make the tests pass. So, actually, this disadvantage is that the same as before when writing code that apparently takes an extended time.y takes a long time.

## What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?
> **ES6 class :** This can be said to be a syntax base for constructor functions and instantiate objects using a new operator.
> **ES5 constructors :** This also uses a new operator for object creation but focuses on how the objects are being instantiated.

## Why REST?
> REST aims to make caching easier. Since the server is stateless and each request can be processed individually, GET requests should usually return the same response regardless of previous ones and the session. This makes the GET requests easily cacheable and browsers usually treat them as such.