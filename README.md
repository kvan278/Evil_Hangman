# Evil Hangman

Evil Hangman is a challenging version of the classic Hangman game where the computer strategically avoids revealing the secret word until absolutely necessary. Instead of selecting a word upfront, the program maintains a list of possible words based on user guesses, using data structures like sets, maps, and lists to facilitate this dynamic gameplay.



## Input Files

- **Dictionaries**:
  - `smallDictionary.txt` - A small dictionary for testing (9 words).
  - `dictionary.txt` - A larger dictionary containing thousands of words.

## Game Logic

- The computer maintains a list of potential words and does not reveal the chosen word until forced.
- Upon each guess, the program generates different "families" of words based on the revealed letters, choosing the family that maximizes the difficulty for the player.
- The game can operate under different difficulty levels (EASY, MEDIUM, HARD), affecting how the word families are chosen.

## User Interaction

- Allow players to make letter guesses
- Track and Display:
  - Remaining incorrect guesses
  - Letters already guessed
  - Current word pattern
  - Remianing words in play

## Difficulty Levels

1. **HARD**: Always picks the hardest family.
2. **MEDIUM**: Alternates between the hardest and second hardest families.
3. **EASY**: Details for this difficulty can be specified later.

## Author
- [Khanh Van](https://www.github.com/kvan278)
