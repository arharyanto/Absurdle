# Absurdle
Wordle is a word game where the player attempts to guess a 5-letter English word. Each incorrect guess receives feedback in the form of colored tiles indicating how closely the letter matches the target word. This image shows a game with 4 guesses (arise, route, rules, rebus) for the target word, rebus. Guessed letters that exactly match the target word are marked green while letters that are in the target word (but not in the right position) are marked yellow. Letters that aren't in the target word are marked gray.

Absurdle is a variant of Wordle developed by qntm:

Wordle picks a single secret word at the beginning of the game, and then you have to guess it. Absurdle gives the impression of picking a single secret word, but instead what it actually does is consider the entire list of all possible secret words which conform to your guesses so far. Each time you guess, Absurdle prunes its internal list as little as possible, attempting to intentionally prolong the game as much as possible.
