# Rock-Paper-Scissors
This is a **Java program for a simple text-based "Stone, Paper, Scissor" (Rock, Paper, Scissors) game**.

The program simulates the classic game where a user plays against the computer. The user chooses one of "stone," "paper," or "scissor," and the computer randomly makes its choice. The program then determines the winner based on the game's rules and displays the result. After each round, the user is given the option to play again or exit.

Here's a breakdown of the Java programming topics used in this code:

* **Object-Oriented Programming (OOP) Concepts:**
    * **Classes and Objects:** The code defines two classes: `stonePaperScissorGame` and `stonePaperScissor`. An object `player` of `stonePaperScissorGame` is created in the `main` method.
    * **Encapsulation:** Instance variables (like `userChoice`, `computerChoice`, `userWon`, etc.) are declared as `private`, and access to them is controlled through public methods (getters and setters), although not all variables have explicit getters/setters (e.g., `userWon` is set internally).
    * **Methods:** Various methods are defined to encapsulate specific functionalities of the game (e.g., `setUserChoice`, `setComputerChoice`, `checkkResult`, `displayResult`, `startGame`, `playAgain`, `welcomeAndRules`, `resetGame`).
    * **Constructors:** Although not explicitly defined, the default constructor is used for `stonePaperScissorGame`.

* **Basic Java Syntax and Control Flow:**
    * **`import` statements:** To bring in necessary classes (`java.util.Random` for random number generation and `java.util.Scanner` for user input).
    * **Variables and Data Types:** `int` for choices, `boolean` for win/draw states, `String` for display messages and menu input.
    * **`private` and `public` access modifiers:** To control visibility of members.
    * **`if-else if-else` statements:** Used in `checkkResult` and `displayResult` for conditional logic.
    * **`switch` statements:** Used in `whatHappend` and `playAgain` for multiple choice handling.
    * **`return` statement:** In getter methods and boolean condition methods.
    * **Method Calls:** Calling methods of the same class or other objects.

* **Input/Output (I/O):**
    * **`Scanner` class:** To read user input from the console (`System.in`).
    * **`System.out.print()` and `System.out.println()`:** To display output to the console.

* **Random Number Generation:**
    * **`Random` class:** To generate the computer's random choice (`rand.nextInt(3)`).

* **String Manipulation (basic):**
    * Assigning string literals to variables.
