Implementation of the Hangman game using Pygame.

This works very simple:
- We have a list of 50 words adding on a .txt file that is imported to a function called 
"generate_word" which strips the words into a list and return a random (using randomint()) word.
- Using Pygame "event.type and pygame.KEYDOWN" we get the input of the user and but only getting one letter (Key) at a time and once the user press ENTER the letter is check by a function that goes char by char in the secret word checking if the letter is found.


![Alt text](demo-1.png?raw=true "Demo")
![Alt text](demo-2.png?raw=true "Demo 2")
![Alt text](demo-3.png?raw=true "Demo 3")
