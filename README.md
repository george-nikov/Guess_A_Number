# The "Guess - A - Number" Game
A console-based JavaScript implementation of the "Guess - A - Number" game. 

![image](https://user-images.githubusercontent.com/109210142/214312082-d81b1c9c-4521-418b-aa9f-6b792b449552.png)

**"Guess A Number"** is a game in which your opponent, "the computer" chooses a random number between "1 and 100" and your task is to **guess** this number. After each number you enter, the computer will give you a hint of whether the number is **greater or less than the number** you selected until you **guess the correct number.**

You **win** the game when your number matches your **computer** number. 

## Input and Output

Choose a number between **1** and **100**, then press **Enter.**
The computer selects a **random number**, then returns information whether the **number is less than, greater than or equal to the selected number.**

## Solution

Firstly, we create an interface where we can enter the number without stopping the program then we create a method "random" which helps the computer choose a random number. We also create a function that stores the question about the number using "readline.question". Then we check if the input data is valid using if-else statement and check if the number entered by the player matches the computer's number. Finally we print the output. 

** Source Code**: [Source Code](Guess_A_Number.js)

## Screenshots

![1212](https://user-images.githubusercontent.com/109210142/214315712-12a536d0-97bb-4bb0-89cb-763fcda8fd41.PNG)
![1213](https://user-images.githubusercontent.com/109210142/214315725-00f6a7f0-0298-4452-8ec2-5d76a10bc047.PNG)
