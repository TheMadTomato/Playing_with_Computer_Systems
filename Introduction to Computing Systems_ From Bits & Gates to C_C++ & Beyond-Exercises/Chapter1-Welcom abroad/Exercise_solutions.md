# Chapter 1: Welcome Abroad

1. Explain the first of the two important ideas stated in Section 1.5.

    The Two important notions are the notion of abstraction and the notion of hardware vs. software

    The notion of abstraction is the ideology that whilst working on something we should not be so taken away by the details so that it hinders our actual progress, neither should we be in a state where we can't go back to check and understand details. To achieve anything in life, we go through steps. Of course each step is made from multiple smaller steps. The idea of abstraction is that while in a single step we know for sure how each of the smaller steps work and they are set and unlikely to change, we don't have to waste time and energy to check and go into each smaller step we can immediately finish the step as it is and move on to the next one. On the other hand, it is important that we know what are the smaller steps and how they work, not having the need to go through them does not mean we should not know what they are. For it happens sometime we need to attentively deconstruct a step into as many steps as needed so we can meet the wanted result. And to do that we should have the appropriate knowledge to know how to properly use each step to meet the wanted results. Abstraction and Deconstruction  is a notion that cover all the aspect of life not only computers.

    The notion of hardware versus software is one that preaches to treat hardware and software as one rather than treating each as if it is its own special domain. This notion is pretty clear. To achieve higher levels of intellect we should treat our learning of these to concepts as essential to one another. It is self explanatory kinda if one knows how computer resources work, one will ofc be able to write much better programs.

2. Can a higher-level programming language instruct a computer to compute more than a lower-level programming language?

    Code written with a high level programming language is always converted by the computer to low-level programming language so no they both are able to instruct the computer the same way. low-level languages just give you more clarity as a user as to how it talking with computer resources.

3. What difficulty with analog computers encourages computer designers to use digital designs?
    
    digital designs dominate over analog designs when it comes to precision, effectiveness, and efficiency. In analog designs one will need a particular tool for each process, one wil lose time, and one's rate of inaccurate results increases. digitals systems offer tremendous capabilities, for in one system one can have multiple tools that compute and solve most problems faster and more accurate than the average human being. analog designs require some level of expertise to be used correctly while on a digital computer even a cat can operate the same operations. accuracy  is more achievable in a digital design thus computer designers use digital designs.

4. Name one characteristic of natural languages that prevents them from being used as programming languages.

    Computer needs a set of clear instruction that it would execute. In natural language that we use in our day to day lives, almost every spoken word can have multiple meanings depending on the context, the tone, and other variables that a computer cannot possible comprehend. When we order a computer to do something it needs to know exactly what is the tasked so it can precisely execute it. Hence we created programming languages, set of instructions, that we can use to efficiently communicate with the computer.

5. Say we had a “black box,” which takes two numbers as input and outputs their sum. See Figure 1.10a. Say we had another box capable of multiplying two numbers together. See Figure 1.10b. We can connect these boxes together to calculate p × (m + n). See Figure 1.10c. Assume we have an unlimited number of these boxes. Show how to connect them together to calculate:
a. ax + b
b. The average of the four input numbers w, x, y, and z
c. a2 + 2ab + b2 (Can you do it with one add box and one multiply box?)

    a. (a,x)-->[a * x]-->ax; (ax,b)-->[ax + b]-->ax+b
    b. (w,x,y,z)-->[w + x + y + z]-->sum; (sum, 4)-->[sum/4]-->average
    c. (a, ab, b)-->[a + ab + b]-->a+ab+b; (a+ab+b, 2)-->[2 * (a + ab +b)]--> a2+2ab+b2

6. Write a statement in a natural language, and offer two different interpretations of that statement.

    "Dad went out to get milk"--> dad needs milk so he went buy some
                              --> dad is running away and never coming back. good luck lil    timmy

7. The discussion of abstraction in Section 1.3.1 noted that one does not need to understand the makeup of the components as long as “everything about the detail is just fine.” The case was made that when everything is not fine, one must be able to deconstruct the components, or be at the mercy of the abstractions. In the taxi example, suppose you did not understand the component, that is, you had no clue how to get to the airport. Using the notion of abstraction, you simply tell the driver, “Take me to the airport.” Explain when this is a productivity enhancer, and when it could result in very negative consequences.

    It is a productivity enhancer when i do not have to slow myself down while working on a project. but negative consequence may happen if is did not give enough attention to some details of the base of the project
