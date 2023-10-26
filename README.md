# Number Guessing Game

This is a simple Number Guessing Game implemented in Java. The game generates a random number between 1 and 100, and your goal is to guess that number within the fewest attempts. This project is an excellent way to practice your Java programming skills and logic.

## How to Play

1. The program will generate a random number between 1 and 100.
2. You will be prompted to guess the number.
3. Enter your guess using the keyboard.
4. The program will give you feedback, telling you if your guess is too high or too low.
5. Keep guessing until you correctly guess the number.
6. Once you guess the correct number, the program will display the number you guessed and the number of attempts it took.

## Prerequisites

Before you can run this game, you need to have Java installed on your system. If you don't have Java installed, you can download it from [Java's official website](https://www.oracle.com/java/technologies/javase-downloads.html).

## How to Run

To run the Number Guessing Game, follow these steps:

1. Download the Java source code provided in the `Number_Guessing_Game.java` file.

2. Open your terminal or command prompt and navigate to the directory where you saved the file.

3. Compile the Java code using the following command:

   ```bash
   javac Number_Guessing_Game.java
   ```

4. Run the compiled code with this command:

   ```bash
   java Number_Guessing_Game
   ```

5. The game will start, and you can begin guessing the random number.

## Game Logic

- The game generates a random number between 1 and 100.
- You input your guess through the console.
- The program provides feedback, such as "Too low" or "Too high," based on your guess.
- It keeps track of the number of attempts it takes for you to guess the correct number.
- Once you guess the correct number, the program displays the number you guessed and the number of attempts.

## Sample Output

Here's an example of what you might see when playing the game:

```
Guess the number
50
Too low...
Guess the number
75
Too high...
Guess the number
63
Too high...
Guess the number
56
Too low...
Guess the number
59
Too low...
Guess the number
60
Yes, you guessed it right! It was 60.
You guessed it in 6 attempts.
```

Have fun playing the Number Guessing Game and improving your Java skills!
