---
date: 2021-10-10
title: Book Insights | Refactoring - Improving the Design of Existing Code
tags: [books]
image: "/images/elegantpuzzle.jpg"

---

Refactoring makes code understandable and easy to extend. Refactoring makes it quicker to create complicated systems. You remove excess code so it is easier to understand & modify. By refactoring code you can better understand others code. You eliminate the having to remember what old code does. You can write code quicker

1. Duplicated code - Same code structure in more than one place.

2. Long Method - The longer a procedure is the more difficult is to understand.

3. Large Classes - When a class is trying to do too much, duplicated code cannot be far behind.

4. Long Parameter List- They are hard to understand, inconsistent and difficult to use.

5. Divergent Change - When one class is commonly changed in different ways for different reasons.

6. Shotgun Surgery - When every time you make a kind of change, you have to make a lot of little changes to a lot of different classes.

7. Feature Envy - A method that seems more interested in a class other than the one it actually is in.

8. Data Clumps - Bunches of data(fields, parameters...) that hang around together.

9. Primitive Obsession - Using primitives types instead of small objects.

10. Switch Statements - The same switch statement scattered about a program in different places. Use polymorphism.

11. Parallel Inheritance Hierarchies - Every time you make a subclass of one class, you also have to make a subclass of another.

12. Lazy Class - A class that isn't doing enough to pay for itself should be eliminated.

13. Speculative Generality - All sorts of hooks and special cases to handle things that aren't required.

14. Temporary Field - An instance variable that is set only in certain circumstances.

15. Message Chain - When a client asks one object for another object, which the client then asks for yet another object...

16. Middle Man - When an object delegates much of its functionality.

17. Inappropriate Intimacy - When classes access to much to another classes.

18. Alternative Classes with Different Interfaces - Classes with methods that look to similar.

19. Incomplete Library Class - When we need extra features in libraries.

20. Data Class - Don't allow manipulation in Data Classes. Use encapsulation and immutability.

21. Refused Bequest - Subclasses that don't make uses of parents methods.

22. Comments - Not all comments but the ones that are there because the code is bad.