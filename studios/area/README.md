---
title: 'Studio: Area of a Circle'
currentMenu: studios
---

Get cosy with C# syntax by revisiting one of our early Python programs. We'll create a console program that calculates the area of a circle based on input from the user.

Write a program/class `Area` that prompts the user for a number, and then calculate the area of a circle with that radius and print the result.

> *NOTE:* Recall that the area of a circle is `A = pi * r * r` where `pi` is 3.14 and `r` is the radius.

Here's an example of how your program should work:

```nohighlight
Enter a radius: 2.5
The radius of a circle of radius 2.5 is: 19.625
```

Some questions to ask yourself:
- What data type should the radius be?
- What is the best way to get user input into a variable `radius` of that type?

Create your program/class in the `csharp-exercises` project by right-clicking on the top-level solution within the *Team Explorer* and selecting *Add > New Project*.

## Bonus Missions

1. Add validation to your program. If the user enters a negative number, print an error message and quit. You'll need to peek ahead to learn about [conditional syntax in C#](../../csharp4python/control-flow/#conditionals).
2. Extend your program further by using a [while](https://msdn.microsoft.com/en-us/library/2aeyhxcd.aspx) or [do-while](https://msdn.microsoft.com/en-us/library/370s1zax.aspx) loop, so that when the user enters a negative number they are re-prompted.
