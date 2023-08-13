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

8. John said, “I saw the man in the park with a telescope.” What did he mean? How many reasonable interpretations can you provide for this statement? List them. What property does this sentence demonstrate that makes it unacceptable as a statement in a program?   

	Some of the interprettions that comes to my mind is that (1) He saw a guy with a telescope in the park. (2) in the park he saw a man in the park but do not know his intentions nor who he is or why does he have a telescope. and the unclarity and uncertatinty that this phrase hold is what make it unacceptable to be a statment in a program. statment in a program sould be clear to the point that answer the 5W essentially. we can't have any level of obscuroty in a program statement at all.

9. Are natural languages capable of expressing algorithms?

	Ye for algorithms are nothing but the sequence of idea that will be later converted to code in a certain programming language.

10. Name three characteristics of algorithms. Briefly explain each of these three characteristics.

	**Definiteness**: Meaning that in an algorithm, every step should be precisely stated.
	**Effective Computability**: Meanong that in an algortihm, each step should can be carried out by the computer-Realistic for the computer standards.
	**Finiteness**: Meaning that in an algorithm, we should declare how each process terminates.

11. For each characteristic of an algorithm, give an example of a procedure that does not have the characteristic and is therefore not an algorithm.

	*Definiteness*: Execute until user is satisfied. (how is the usr satisfied, when will he be?)
	*Effective Computability*: Execute until the greatest odd number. (There is no greatest odd number)
	*Finiteness*: enter name. ( the correct way is to say: enter name then terminate)

12. Are items a through e in the following list algorithms? If not, what qualities required of algorithms do they lack?
	a. Add the first row of the following matrix to another row whose first column contains a non-zero entry. (Reminder: Columns run vertically; rows run horizontally.)
		 | 1 2  0  4|
		 | 0 3  2  4|
		 | 2 3 10 22|
		 |12 4  3  4|

	- It does not qualifies for an algorithm for it lack the third charachteristc, finiteness

	b. In order to show that there are as many prime numbers as there are natural numbers, match each prime number with a natural number in the following manner. Create pairs of prime and natural numbers by matching the first prime number with 1 (which is the first natural number) and the second prime number with 2, the third with 3, and so forth. If, in the end, it turns out that each prime number can be paired with each natural number, then it is shown that there are as many prime numbers as natural numbers.

	- This algorithm does not meet the *Effective Computability* criterion. it is not somthing realistic as numbers have no limit therefore there is the possibility for endless amount of pairs.

	c. Suppose you’re given two vectors each with 20 elements and asked to perform the following operation: Take the first element of the first vector and multiply it by the first element of the second vector. Do the same to the second elements, and so forth. Add all the individual products together to derive the dot product.

	- this algorithm is true. the steps are clear, computer-achievable, and terminate by adding all indiviual products to derive the dot - final - product.

	d. Lynne and Calvin are trying to decide who will take the dog for a walk. Lynne suggests that they flip a coin and pulls a quarter out of her pocket. Calvin does not trust Lynne and suspects that the quarter may be weighted (meaning that it might favor a particular outcome when tossed) and suggests the following procedure to fairly determine who will walk the dog.
		1. Flip the quarter twice.
		2. If the outcome is heads on the first flip and tails on the second, then I will walk the dog.
		3. If the outcome is tails on the first flip and heads on the second, then you will walk the dog.
		4. If both outcomes are tails or both outcomes are heads, then we flip twice again.
	   
	   Is Calvin’s technique an algorithm?

	   Yes and i will make it into a program using C++ because it seems fun and i hadn't used C++ in a while check it here: 
	   > https://github.com/TheMadTomato/Playing_With_C-Cpp/tree/NoobLevelCodes/CoinFlip

	e. Given a number, perform the following steps in order:
		1. Multiply it by 4
		2. Add 4
		3. Divide by 2
		4. Subtract 2
		5. Divide by 2
		6. Subtract 1
		7. At this point, add 1 to a counter to keep track of the fact that you performed steps 1 through 6. Then test the result you got when you subtracted 1. If 0, write down the number of times you performed steps 1 through 6 and stop. If not 0, starting with the result of subtracting one, perform the seven steps again.
		
		- it is a legit algorithm

13. Two computers, A and B, are identical except for the fact that A has a subtract instruction and B does not. Both have add instructions. Both have instructions that can take a value and produce the negative of that value. Which computer is able to solve more problems, A or B? Prove your result.

	both will be able to output the same amount of problem since both are capabale of producing negative value.

*the rest of the questions i answered oraly for i lost a lot of time while setting my new laptop and wanted to move to a new chapter*
