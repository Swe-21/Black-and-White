# Black-and-White
This is a simple multiplayer entertainment game done using Java - TCP Socket programming

RULES:

●The computer decides a 4 letter word. (Ex: P L A Y)

● The players must guess the word given by the computer.

● The players must guess the word by prompting different 4 letter words.
 (Ex: C R E W, A W A Y, T R A Y etc)
 
● If the word guessed by the guessers has the same letters as in the original word (P L A Y) but in different positions then it is a black letter.

● If the word guessed by the guessers has the same letters as in the original word (P L A Y) and in the same position then it is a white letter.

● Goal : the guessers must find the original word given by the computer.

● Guessers - The first person to guess the 4 letter word correctly is the winner.

● The amount of attempts taken to guess the word is displayed

EXAMPLE PLAY:

Word decided by computer : P L A Y

Guesser’s 1st guess : T A K E
Computer says: 1 black
(since ‘A’ exists but it is in the wrong place)

Guesser’s 2nd guess : T R A Y
Computer says: 2 whites
(since ‘A’ and ‘Y’ exists and it is in the right place)

Guesser’s 3rd guess : S P A T
Computer says: 1 white 1 black
(since ‘A’ is in right place and ‘P’ exists but it is in the wrong place)

Guesser’s 4th guess : P L A Y
Computer says: 4 whites - YOU FOUND IT!

No of guesses = 4
