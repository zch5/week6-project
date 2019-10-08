# Week 6 Project - Argument Bot 3000

## Collaborators:

* Zachary Heistand
* Tyler Glass
* Marshall Lentz

## Getting started

Welcome to the Argument Bot 3000! This program contains a number of functions for maximizing your argumentative prowess on the Internet.

### Installation and Usage

To use this program, simply clone the database on your local computer using the command:

`git clone https://github.com/zch5/week6-project.git`

Then, run the program using a Python IDE or the command line.

### Functions

1. clap(argument)
  * Inserts a clapping emoji between each word in a string for added effect.
  * Example:
    * Input: `clap("Pineapple does not belong on pizza!")`
    * Output: Pineapple :clap: does :clap: not :clap: belong :clap: on :clap: pizza!
2. mic_drop(argument) 
  * Inserts a mic drop at the end of a string. 'Nuff said.
  * Example:
    * Input: `mic_drop("Pineapple does not belong on pizza!")`
    * Output: `Pineapple does not belong on pizza! *mic drop*`
3. mock(argument)
  * Randomly makes characters in the string uppercase and lowercase to mock your opponent and make him cry.
  * Example: 
    * Input: `mock("Pineapple does not belong on pizza!")`
    * Output: `PiNeaPpLE DoEs nOt bElOng oN pIzZa!`
4. repeat(argument, int)
  * Repeats your argument *int* number of times to make it more true each time.
  * Example:
    * Input: `repeat("Pineapple does not belong on pizza!", 3)`
    * Output:
    ```
    Pineapple does not belong on pizza!
    Pineapple does not belong on pizza!
    Pineapple does not belong on pizza!
    ```
5. spellcheck(argument)
  * Corrects your opponent's misspelled words to really zing 'em.
  * Example:
    * Input: `spellcheck("Pineapple does not belnog on pizza!")`
    * Output: `Pineapple does not *belong on pizza!`
6. thank_u_next(argument)
  * Inserts "thank u next" at the end of a really compelling argument.
  * Example:
    * Input: `thank_u_next()`
    * Output: `Pineapple does not belong on pizza! thank u, next`

*The creators of the Argument Bot 3000 are in no way responsible for damages incurred by the use of this code in online arguments, personal or otherwise.*
