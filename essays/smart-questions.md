---
layout: essay
type: essay
title: "How to Ask Smart Questions"
# All dates must be YYYY-MM-DD format!
date: 2022-09-08
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

Asking questions can be very important when learning something new. Just asking questions without much thought, however, is usually not the best way to improve your understanding of the problem. It's important to know how to formulate your question so as to get the best possible answer that will not only help you solve your current problem, but hopefully give you the knowledge to deepen your understanding of the material as a whole. In programming, what I have found is that when I'm stuck on a problem or if my code isn't working, knowing exactly what I'm trying to do and recognizing what my program is currently doing is very important when trying to resolve problems. To ask an effective question, you have to try to understand exactly what is going wrong in your programming or your thinking, so that you or the person answering the question can isolate the gap in your knowledge.

## Example of a Smart Question

#### *"How to print in C"*

This question was asked on [StackOverflow](https://stackoverflow.com/questions/2162758/how-to-print-in-c) and the person who asked this question also provided the context that they are a beginner to C and also stated how they would have done it in Java. They provided their own code that they have been working on.

```C
#include <stdio.h>

int addNumbers(int a, int b)
{
    int sum = a + b;
    return sum;
}

int main(void)
{
    int a = 4;
    int b = 7;

    printf(addNumbers(a,b));
    return 0;
}
```

This is a smart question because it is explicit and precise. Since they have provided their attempt, anyone who goes to answer their question knows exactly what the question asker is trying to do. One of the answers to this question provided a very good summary of the printf() function in C and how to use it, providing examples of each conversion specifier. A snippet of their response was:

---
*"For signed decimal integer output, use either the "%d" or "%i" conversion specifiers, such as"*

```C
printf("%d\n", addNumber(a,b));
```
*"You can mix regular text with conversion specifiers, like so:"*
```C
printf("The result of addNumber(%d, %d) is %d\n", a, b, addNumber(a,b));
```
---

Another answer also provided documentation for the printf() function. These are useful answers because not only have they answered the original question, they have also helped the question asker alleviate potential problems down the road.

## Example of a Not Smart Question

#### *"i tried adding a figure to my empty array using push"*

The first think to note about this post from [StackOverflow](https://stackoverflow.com/questions/73651500/i-tried-adding-a-figure-to-my-empty-array-using-push) is that it ins't even a question but rather a plainly stated attempt of something that they tried to do. Because of this, it isn't really clear what the question asker is trying to do. They did provide a code snippet of what they did, 

```javascript
var giv = []
    var mes = (2, 3);
    function outPut () {
    output.push(2,3); 
        
    }
    alert(output);
```

but from the code it is clear that the title of the post is somewhat misleading because they said figure when they meant variable. It is important to be precise and use correct terminology when asking a question. We can also see from the code that there are a lot of syntax errors in the code, making it pretty unclear as to what exactly they want to push and to where. This means the question asker has a lot misunderstandings that need to be resolved first before asking this question. Knowing what you don't know is important because it means you can seek help on precisely the things that you need help with.

Because of the ambiguity in the question, one of the answers had to guess at what the asker was trying to do, while another answer simply stated other errors in the code and how to fix them:

---
*"I think your code is all messed up in terms of variables and function, here is what I think you're trying to achieve. Is that correct?"*

```javascript
var giv = [];

function output (input) {
    giv.push(input);
}

var mes = 2;
output(mes);

mes = 3;
output(mes);

alert(giv);
```
---
*"You have to push to the correct variable name. Either rename giv to output, or use giv.push() instead. And fix the rest of the syntax errors."*

---

Because of this unclear and badly framed question, the answers are ambiguous and unclear. This shows the importance of being explicit in your question and precise and informative about your problem.

## Conclusion

One thing to keep in mind when asking questions is to imagine that you are trying to answer it. If you were seeing the question through fresh eyes and no other context, think about how you would pose it. Make sure the title is clear and is relevant to the problem. Provide as much context as possible in the question (like your attempted code) so that it is clear exactly what you are trying to do, and provides a way to reproduce the problem. Describing any research you have done to try and understand the problem before asking it is also very helpful to let others know what level of understanding you are currently at. A well-thought out question will significantly increase your chances of getting you the nice, well-thought out answer you were looking for.  
