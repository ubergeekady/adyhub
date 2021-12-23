---
date: 2021-09-15
title: Book Insights | Clean Code - A Handbook of Agile Software Craftsmanship
tags: [books]
image: "/images/clncod.jpg"

---
**Book** : [Clean Code: A Handbook of Agile Software Craftsmanship](https://www.amazon.in/Clean-Code-Robert-C-Martin/dp/8131773388#customerReviews)

**Author** : [Robert Martin](https://en.wikipedia.org/wiki/Robert_C._Martin)

![](/images/clncod.jpg)

### Introduction

- Book is about software engineering Craftsmanship == writing clean code
- Two aspects of Craftsmanship - knowledge and its application (work)
- Knowledge - principles, patterns, practices and heuristics
- Work - using the knowledge every day when reading lots of code, making mistakes, arguing over it, seeing the price you pay for wrong decisions
- 3 parts of the book - 
  - Part 1 - principles, patterns and best practices of writing good clean code
  - Part 2 - case studies and exercise to use knowledge gathered in part 1
  - Part 3 - summary list of heuristics to detect smelly (bad) code, learnt from part 2
- Insight - just knowing principles is not enough, you will have to use them daily, as an engineer you will have to write and review lots of code and get your code reviewed by senior people and learn from your mistakes.

### Chapter 1 - What is clean code? 

- There will be code - The only way to go fast is to keep your code clean

- Attitude - of that of professional (Pro), e.g. Doctor, patient - stop washing hands, Startup vs established company - attitude difference?

- Proxy of clean code - 

- - Maintainable/Testable - easy to change, has good tests, easy to validate new changes
  - Productivity of engineers - new feature development, developer happiness 
  - Readable - easy to read
  - Crips and clear - no surprises on what it does, does one thing very well.
  - Performant and scalable to many users

- Going fast - time pressure, tired of working, want to be done, big backlog

- Clean code - argument for cost effectiveness and professional survival

- Manager tip - 

- - Add more staff for tech debt - no!
  - Remember - Productivity vs time
  - What to do - Review code more to practice the craft! Managers and marketers need devs help to make correct promises and commitments - Stupid manager.
  - When should we clean - all the time! E.g. Broken window of a house.
  - Imagine a world where code always gets better with time :) One small action at a time! Boy Scout rule - *leave the campground cleaner than you found it.* 
     		***“Leave your code base cleaner than you found it”\***.

- Insights - going fast on the long term is possible with writing clean code all the time, practice the craft and learn from it and have the attitude of a PRO always for the work you do!

### Chapter 2 - Naming

- Name should tell the intent why it exists, what it does and how to use it E.g. good name would be **employeePyamentInfo** vs **ePay**
- Avoid confusing names -  I.e. using names that already imply something! E.g. naming something **unix**, **testList** (even if it not a list)... 
  Choose clear names - I.e. Say what you mean and mean what you say. E.g. **deleteItems** over **bustThemDown**, **kill** over **whack**
- Use good Distinctions  Avoid using number at end! Use distinctions that make sense and thus don't just use numbers
  E.g. **list1**, **list2**, instead - **productIds**, **productDetails** etc
  E.g. using **productInfo** and **productDetails** - means same and distinction is harder between these two variables.