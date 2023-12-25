# Hang Man Game with python
This simple game is actually pretty complex. This hangman project combines lists, string manipulation, and slicing, along with other concepts.

 random.choice() picks a random item from a list. To select randomly from this list, we assign random.choice() to a variable.

 Once the word has been picked, the following things need to happen:

1. Prompt the user to type in a letter.
2. Check if the letter is in the word.
3. If it does, output the word with all blanks apart from the letter(s) they've already guessed.
4. Keep a running list of the letters they've used.
5. Count how many times they've picked a letter that isn't in the word - more than 6 and they lose.
6. Output a 'win' message if they reveal all the letters.


Example - 

🌟Hangman🌟

Choose a letter: i
Nope, not in there.
5 left.

Choose a letter: a
Correct!
__a__

Choose a letter: s
Correct!
s_a__

Choose a letter: u
Correct!
sua__

Repeat until.....
If user wins
You won with 5 lives left.

Loses
You lost!
