---
layout: essay
type: essay
title: "Learning Javascript and Athletic Software Engineering"
# All dates must be YYYY-MM-DD format!
date: 2022-08-31
published: true
labels:
  - Javascript
  - Software Engineering
---

<!---<img width="200px" class="rounded float-start pe-4" src="../img/difficulty/degree_difficulty.jpg">--->


## Initial Impressions


Up to this point most of my experience in programming has been in Java and a little bit of Python and C++. As such, my frame of reference for learning Javascript has been mostly with respect to Java. What sticks out to me the most in the short time that I've been learning Javascript (about a week) is how "simple" it feels. I'm calling it "simple" because I don't know that have learned enough or have had enough experience with the language yet to be able to formulate a better word. This simplicity, as I have found so far, isn't necessarily a characteristic I have enjoyed about the language.

<img width="200px" src="../img/javascript.png">

For example, take a function definition. In Java, the type of each parameter that the function takes must be specified, as well as the type that is returned.

```java
// Java is statically-typed

boolean isOdd(int number) {
    if (number % 2 == 1) {
        return true;
    }
    return false;
}
```

However, since Javascript is not a statically typed language, the parameter types and return types are not specified.

```javascript
// Javascript is dynamically-typed

function isOdd(number) {
    if (number % 2 === 1) {
        return true;
    }
    return false;
}
```

The reason I say I haven't necessarily enjoyed this aspect of javascript is because it feels less precise than what I'm used to. It feels strange to initializing a variable say, and not state what it is.

```java

double pi = 3.14;
```

vs 

```javascript

let pi = 3.14;
```

From the little bit of time I've spent using javascript this is the most obvious difference I've had to get used to. I'm sure I will come across more as I use the language more.

## Software Engineering Perspective

Whether javascript is a good or bad language for software engineering is not really a question I feel I have enough experience to answer. I do know that Javascript is a very popular language and therefore it must be very useful for certain types of software engineering. I think it is important to note that, at least in my opinion, one should never isolate themselves to just one language and try to use that language for as many tasks as they can. I think it is valuable to generalize as much as possible in terms of programming concepts and sort of get down to the "first principles" to become a better programmer or software engineer. For this reason I think being able to use a variety of languages and choose the language that is best equipped to accomplish the task at hand is ideal. Or at the very least having experience with many languages so that you have a strong core understanding of programming principles and strategies.

## Athletic Software Engineering and WODs

I think the idea of athletic software engineering where you have to solve a programming problem in a relatively short amount of time in the form of a WOD (workout of the day) seems to be valuable tool in learning and reinforcing concepts. It is certainly stressful as being constrained to say 7-10 minutes is not something I am used to. Granted these problems are usually somewhat simple but the difficulty comes in the time limit. I've found that this constraint has required me to pretty much go with the first strategy for solving the problem that comes to mind as there is no time to sit and come up with a better one. This means that essentially you must have enough experience with solving similar types of problems that the first strategy you think of *is* the best strategy. 

As is mostly the case with programming, the enjoyment comes from succeeding and finding that you now know how to solved the puzzle, at which point you feel like you're a very good programmer. There is, however, always the next problem to humble you again.

