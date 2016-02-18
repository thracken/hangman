# hangman
A text-only hangman game that pulls a random word from an external "dictionary" file.

This has one issue - if you guess a non alphanumeric character, the game accepts it as a guess, and (of course), it counts against you.
As the point of this exercise was to get the file interactions working, I'm not going to take the time to create a regex for every possible special character.
