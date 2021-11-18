# Mathematical Analysis of the Substitution Code
What is the mathematical complexity to solve the code?
There are 26 factorial possible keys. That's 403,291,461,126,605,635,584,000,000 possible keys. 

This is because the first letter in the alphabet has 26 choices of letters that it could be switched with. Then the next letter has 25 because one of the letters was already used for the last letter. Then the next has 24, and the nest has 23 and so on. You then times all of those together because for each of the different possibilities for the first letter, there are 25 possibilities for the second letter. This goes all the way down to the last letter tha has 1 possibility. You can use factorial for this because factorial means the number times all of the numbers less than it until one.

![Image of an explination of factorial](https://cdn.inchcalculator.com/wp-content/uploads/2020/09/factorial-formula.png)

If you don't have the key, you have to brute force it with a computer by trying all of the possible solutions.
