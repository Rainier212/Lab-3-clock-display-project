Project: clock-display
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class ClockDisplay. Then inspect this 
instance and leave the object inspector window open. With the inspector window open, 
call the object's methods, such as timeTick and setTime. Watch the 
"displayString" in the inspector.

The displayString field simulates the actual clock display device. Were this 
program running in a real clock, it would change the real, physical display 
hardware instead of this string. The timeTick method would be triggered once 
every minute by some timer hardware.

Everything else could be pretty much the same.


Note: This project does not implement adequate handling of errors.


ANSWERS TO QUESTIONS:

21- When I call its getTime method, the initial time the clock has been set too is "00:00". It starts at that particular time since a day starts at 00:00.

23- I will need to all the timeTick method 60 times for it to reach 01:00. I could also make it display that time by calling the setTime method. I would have to set the value of hour to 1 and the value of minute to 0.

24- (have to write down the definition of a variable of type NumberDisplay called digit.)
    NumberDisplay digit = new NumberDisplay(10);

25- Rectangle window = new Rectangle(int height, int width);

26- It creates a new clock set at the time specified by the parameters. So it'll set the time of a specific time that the person inputted.

27- They both have the same limits for hours (24 hours) and minutes (60 mins). However, the second constructor doesn't not have an updateDisplay method since it uses a setTime method.

28- The 2 possible methods are: print and getStatus

29- Squares (Window and Wall), Triangle (Roof) and Cirle (sun)

30- changeSize, moveHorizontal, moveVertical and makeVisible

31- Yes. draw, setColor and setBlackAndWhite are all its internal method calls.

32- 2 is the remainder of the expression (8 % 3)

33- It'll give me a negative remainder.

34- 0,1,2,3,4,5

35- 0 to m

37- I would say that the first possibilty is the easiest one to do since all we need to do is change numbers from an existing code. However the second one would be the better clock since it's a 24 hour clock, and displays if it's PM or AM.
