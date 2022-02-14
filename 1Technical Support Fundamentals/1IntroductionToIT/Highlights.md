# WEEK 1 NOTES

<br>

## History of Computing

* **Computer**: A device that stores and processes data by performing calculations.
* **Algorithm**: A series of steps that solve specific problems.
* **Cryptography**: study of secure communications techniques that allow only the sender and intended recipient of a message to view its contents.
* **Open source**: Anyone can modify and use it.

<br>

## Digital Logic

* **Binary system**: The communication that a computer uses, also known as a base-2 numeral system.
* We group binary into 8 number or **bits**. Technically, a **bit** is a binary digit.
* A group of 8 bits is referred to as a **byte**.
* Each byten can store one character, and we can have 256 possible values thanks to the base-2 system (2<sup>8</sup>).
* **Character encoding**: Assigns our binary values to characters, so that we as humans can read them.
* The first character in the ASCII to binary table -- a lowercase 'a' -- maps to 01100001 in binary.
* **Logic gates**: Allow our transistors to do more complex tasks, like decide where to send electrical signals depending on logical conditions.

<br>

## Computer Architecture Layer

* **Abstraction**: To take a relatively complex system and simplify it for our use.
* **Hardware layer**: Made up of the physical components of a computer.
* **Operating system**: Allows hardware to communicate with the system.
* **Software layer**: How we as humans interact with our computer.
* **User**: Interacts with the computer.

<br>

## Procedure for converting a decimal number to binary.

<ol>
<li>Take decimal number as dividend.</li>

<li>Divide this number by 2 (2 is base of binary so divisor here).</li>

<li>Store the remainder in an array (it will be either 0 or 1 because of divisor 2).</li>

<li>Repeat the above two steps until the number is greater than zero.</li>

<li>Print the array in reverse order (which will be equivalent binary number of given decimal number).</li>
</ol>