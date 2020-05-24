# DRY Principle in Programming
1. Topic name and Presenter name. Greetings.
2. Okay, so let’s start with a short game. You’ll need to guess who said that.
“I choose a lazy person to do a hard job. Because a lazy person will find an easy way to do it.”
Giving a hint with the picture. Right! It’s Bill Gates. 
I’ve decided to start from this quote because for me the topic of my presentation is closely related to laziness and logic of course.
3. So, What is DRY? There’s a principle in programming called DRY. As you may notice, DRY is an acronym, which means Don’t Repeat Yourself.
The aim of this principle is pretty obvious from its name -  reduce repetition of code. Or avoid code duplication.
4. There's another concept that people have referred to as WET programming which stands for "Write Everything Twice."
Writing your code you should always ask yourself "Haven't I written this before?" If your answer is yes, it’s better to think about what can you do about it.
Basically, when you find yourself writing the same code over and over again, there may be a better way to do it. 
5. You can think of your code as clothes. Everyone knows that dry stuff is lighter and easier to maintain, manipulate, and store.
You wouldn’t want to keep wet clothes in your suitcase — it would create an unpleasant smell and increase the weight of your bag. 
When it comes to programming, DRY and WET practices can be taken the same way — you’d want to avoid the WET ones. 
Let’s look at the examples.
6. We have a very simple example. Just to get an understanding. We have fruits array, which elements we need to print via the console. 
We could just use Console.Log for that. Let’s do some copy and paste. But imagine that you have 100 elements. 
Doing the same doesn’t seem very correct from a technical point of view. It is full of duplications everywhere.
This code could be improved. 
7. We can use a loop to execute repeated code. Looks better, right? 
8. Let’s look at another example. Now we have 3 arrays and the same task.
9. We could use console.log again. But we already know that using loops is faster. But is it code DRY enough? 
We can see that use the same loop 3 times. How can we avoid that? 
9. Well, we can wrap loop into a function like that. All we have to do now is just call this function for each array.
Drying Up your code usually means refactoring code by taking something done several times and turning it into a loop or a function.
DRY code is easy to change, because you only have to make change in one place.
It is quite obvious, which one of the two should all developers be aiming for. 
10. **Advantages of DRY**
	* *Readability* — Usually You can follow the DRY codes easily
	* *Reusability* — You won't need to define stuff more than once instead you will reuse the already written logic that performs the same operations
	* *Cost* — DRY coding approach saves you time and space
	* *Testing* — Unit testing is easier with DRY code. The more paths and functions you have to cover using the tests, the more code you have to write. If code is not repeated, you just have to test one main path. So if you have a WET code, you will perform more unit tests
11. With all the advantages of using DRY, there are some pitfalls. You need to be aware of them.
	* Not all code needs to be merged into one piece. Some times 2 pieces of code can look similar but with little differences. When to merge these prices of code into one and when to leave them separated needs to be thought over carefully.
	* Over-dried code may not be easier to read because you will have many logical callings to follow. You should be careful about naming your variable or functions, if you can’t figure out what a variable is for or what a function does based on its name, then it’s harder to change it later. You need to think a lot when you’re implementing DRY code.
12. How to decide when you need to dry up your code? You can use Rule of Three. What is that rule about?
To repeat twice the same code may be ok. But the third time we build the same code, it’s time to refactor and fix the duplication.
In conclusion I would like to say: Whenever you finish writing some code, you should always look back to see if there is any way you can DRY it up.
13. Thank you very much for listening!


