---
date: 2021-10-10
title: Book Insights | Refactoring - Improving the Design of Existing Code - Code Smells
tags: [books]
image: "/images/refactoring.jpeg"

---
> "Whenever you read [Refactoring ], it’s time to read it again. And if you haven’t read it yet, please do before writing another line of code."
> –David Heinemeier Hansson, Creator of Ruby on Rails, Founder & CTO at Basecamp


> Fully Revised and Updated―Includes New Refactorings and Code Examples
> 
> “Any fool can write code that a computer can understand. Good programmers write code that humans can understand.”
> –M. Fowler (1999)

![](/images/refactoring.jpeg)

Refactoring makes code understandable and easy to extend. Refactoring makes it quicker to create complicated systems. You remove excess code so it is easier to understand & modify. By refactoring code you can better understand others code. You eliminate the having to remember what old code does. You can write code quicker

Code smells are key signs that refactoring is necessary. In theprocess of refactoring, we get rid of smells, enabling furtherdevelopment of the application with equal or greater speed. The lack of regular refactoring, can lead to a complete paralysisof a project over time, wasting a few years of developmentand requiring you to spend several more years to rewriteit from scratch.Therefore, it is necessary to get rid of code smells while they are still small.

### Long Method

A method contains too many lines of code. Generally, any method longer than ten lines should make you start asking questions. Like the Hotel California, something is always being added to a method but nothing is ever taken out. Since it’s easier to write code than to read it, this “smell” remains unnoticed until the method turns into an ugly, oversized beast. Mentally, it’s often harder to create a new method than to add to an existing one: “But it’s just two lines, there’s no use in creating a whole method just for that...” Which means that another line is added and then yet another, giving birth to a tangle of spaghetti code.

As a rule of thumb, if you feel the need to comment on something inside a method, you should take this code and put it in a new method. Even a single line can and should be split off into a separate method, if it requires explanations. And if the method has a descriptive name, nobody will need to look at the code to see what it does.

