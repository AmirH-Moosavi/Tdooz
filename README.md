# Tdooz
Tdooz is an advanced version of the tic tac toe game. This game is played in an 8 x 8 matrix. First, the starting color of the game is determined randomly, and the person who has the same colored piece starts the game and chooses a desired number between 1 and 8. After choosing this number, the corresponding bead will be placed in the lowest empty house of that column. Five different modes of scoring are vertical mode, horizontal mode, diagonal to the left, diagonal to the right and the last mode, the corners of a 4 x 4 square. It should be noted that the number of doses for beads in a row and in one direction will be calculated only once, and it is considered a new dose if a row or a column or a diameter is completely filled. The player who achieves the most doses at the end of the game wins.

### Ways for getting score
<img width="277" alt="image" src="https://github.com/mohamadkhalaj/Tdooz/assets/62938359/6ac4f735-660d-4195-b319-9bdf2dfa7400">
<img width="267" alt="image" src="https://github.com/mohamadkhalaj/Tdooz/assets/62938359/1eab1f5e-b1ff-40d4-92cc-67a82484808d">
<img width="253" alt="image" src="https://github.com/mohamadkhalaj/Tdooz/assets/62938359/4cb37d58-fc17-46ca-8624-394a6c5a26b3">

## Marked beads
So far, the rules mentioned were for normal beads, but the story is a little different for marked beads. By using marked pieces and by establishing the following conditions, you can make the opposite piece the same color as yourself:
- If the bead on the left side of the bead with the percentage mark (%) has the opposite color of the bead, it can make that bead the same color as itself.
- If the bead on the bottom right of the bead marked with a star (*) is a bead of the opposite color, it can make that bead the same color as itself.
- If the bottom bead of the dollar sign ($) is the opposite color, it can make that bead the same color. 

### Usage of the marked beads
<img width="273" alt="image" src="https://github.com/mohamadkhalaj/Tdooz/assets/62938359/e0ebfcfa-7ccf-4dca-bd99-6301f10dee61">
<img width="266" alt="image" src="https://github.com/mohamadkhalaj/Tdooz/assets/62938359/722f28bc-ad02-424e-b32b-c94d55ccc32e">
<img width="262" alt="image" src="https://github.com/mohamadkhalaj/Tdooz/assets/62938359/d877d52f-9eed-42f0-b28f-8a88d40242bb">

This adds an extra layer of strategy to the game, as players must carefully consider which marked pieces to use and how to use them effectively.
Also, the game will continue until the entire game board is filled with pieces of both colors in order of turn. Note that each color has only three marked pieces and in the end, the winning color is the one that has made more doses on the game board. This means that players must not only focus on making doses but also on preventing their opponent from making doses. Strategic play and careful planning are key to winning in this exciting game.

# How to compile
This project is an OOP(Object Oriented Programming) made with Java programming language. This project has a graphical interface that is made with Jframe. The UML diagram of the classes is located in to the root directory of this repository `TDoozUML.png`.

For compiling this project you should compile this file: `src/Game/Run.java`.


# Team members
- [Amir Hossein Moosavi](https://github.com/AmirH-Moosavi)
- [Mohammadmahdi Khalaj](https://github.com/mohamadkhalaj)
- [Ali Hassanzadeh](https://github.com/AliHasanzadeh80)
