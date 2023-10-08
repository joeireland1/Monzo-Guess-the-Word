# Monzo-Guess-the-Word

I have created and programmed this to provide the user with a game which is similar to hangman using Python 3. 

Firstly, I have created a list of Monzo lingo by using the lists data structure. 

The programme will select a word out of this list at random using the 'def' to define the choose_word function and then by using the return and choice function as well as the import random module.

I have then created another define function for play_game which tells the computer to use the above function to randomly select a word and output '_' for the length of the word using 'len'. 

I also have added a string to be printed to intorduce users to the game. 

I have used the join function to take the items in the iterable and join them into one string so that the customer is aware of how long the word is they are looking for. 

I have then used while, if and else statements to allow the programme to advise the user if the letter they have entered in the chosen random Monzo word or not. 

I have also used operators which allow the programme to distinguish if the letter inputted is in the random word. 

I have used len function and isalpha function to allow the user to know if they have inputted an invalid character - a string will be printed if so requesting the user to try again. 


# Monzo-Guess-the-Word QA analysis

I have reviewed the programme that I have created and whilst it works and functions as it should, there could be an improvement. 

If I were to create a version two of the game, I would ensure that when a numerical value is entered into the programme by the user, the output will specify that we can only use letters rather than "Invalid input. Please only enter one letter at a time."


