# RockPS

The Odin Project
A program that allows the user to play Rock Paper Scissors in the command console. The user will play against the computer, and it will be best of three.

Does the program have an interface: No, it will be used the the console.

What input will the program have. Will the input data be from the user or somewhere else: The users choice between rock, paper or scissors through a function call. The data will be from the user.

What is the desired output: Rather the user won or lost the round of Rock Paper Scissors. If three rounds have passed, rather the user won or lost the game.

Given your inputs, what are the steps to return the desired output:

- User starts the match with either rock, paper or scissors by entering choice into prompt
- Initialize computerChoice variable and randomly choose rock, paper or scissors
- Rock beats scissors, scissors beat paper, paper beats rock. Depending on the computerChoice and users input, increment either user or computers win.
- Print number of wins, and previous winner
- Check how many wins user and computer have. If neither have three wins, prompt user to enter choice again. If one have three wins, end game and declare winner through print.
