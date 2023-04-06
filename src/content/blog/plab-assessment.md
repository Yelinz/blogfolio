---
title: "HSLU PLAB assessment brain dump"
description: "A non comprehensive mixed list of questions and answers from the PLAB assessment."
pubDate: "2022-09-16"
---

A non comprehensive mixed list of questions and answers from the PLAB assessment.
Some question might be missing because I forgot them.
May this help you, as the description provided for which topics are questioned isn't the clearest.

**Do not treat this as a complete and definitive list, topics and questions might and probably change everytime.**

## General programming
Write the 2 methods `divideBySeven` and `maxMinusMin`, they calculate from the given numbers list how many are dividable by seven and the difference between the largest and smallest number.
```java
public int divideBySeven(List numbers)
public int maxMinusMin(List numbers)
```
> Nothing difficult just some basic for each and if conditions. 
> `maxMinusMin` might also be solved using the `Math` library, but im unsure if that is graded worse or better.

## for, while, recursion
Countdown from 9 with the 3 different methods.
> Also not difficult if you have ever programmed.

## Java inheritance and typing

Person

Employee Student

Prof

###  Choice between Complie, Runtime or no Error
```java
Person p = new Student
----
Prof p = new Student
----
Person p = new Student
Employee e = (Employee) p
----
Employee e = new Prof
Person p = (Person) e
```
> Forgotten most of the questions, but something in that direction

### Questions about how inheritance works
If Prof is multiple inheritance
Subtype
If a Student object can be assigned into a Person variable.
> Forgotten most of the questions, but something in that direction

## Refactoring and UML Class Diagram
Given class `public class TemperatureDisplayAndCalculation`
Which principle a given class was violating
- SRP
- Hidding
- etc..

```java
public class Temperature {
	private int temp;
	private static final OFFSET

	public Temperature(int temp)
	public getCelcius()
	public getFahrenheit()
	public getKelvin
}
```

Fill in Class Diagram with missing methods and attributes

  > I didnt know how to represent `static` and `final`, maybe look that up. The above code is just my Interpretation, the class structure wasn't strictly defined and had to be interpreted form the pre-refactor code.

## JUnit
Write assert
Why many test with few asserts or few tests with many asserts
> No clue about junit so i forgot most questions, as I fluked this part

## Write a class
- class name Student
- private attributes `name` and `number`
- getters (without setter) for `name` and `number`
- `constructor` with parameter `name`
- `constructor` sets `number` and increase number everytime new Student is called

Follow up question:
How to create a Student object within the Student class with different constructors and not accessible/ callable outside of Student class.
Example:
`new Student("name", -1)`

> Generally not difficult, but with no java knowledge I don't know how to set `number` and increase it for every instance.

## General Java questions
> Hazy memory with this section, there were atleast 14 or so questions in total.
> But mostly just specific java knowledge.

what are and is the difference between checked and unchecked exceptions

how `try-catch-finally` works & what does finally "guarantee"

Java 8
Why were lambda and Stream API implemented

Class Hierarchy
> Maybe has something to do with https://staff.fnwi.uva.nl/a.j.p.heck/Courses/JAVAcourse/ch3/s1.html
> but I really don't know.

Overloaded function, why it doesnt work
```java
private void process(ArrayList<int> param)
private void process(ArrayList<String> param)
```
  
Overriden `Object.hashMap`
problematic with `hashSet`
