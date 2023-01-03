# My first game implemented in JavaScript.

Snake_1.0
- created the logic of movement to the right, left, up, down
- created control from the PC keyboard
- created the logic of transitions at the borders of the fields
- created the logic of the random appearance of the target
- created target catching logic
- created end screen with score and new game button
- removed a bug when random squares appeared in the body of a snake
- fixed bugs of transitions at the field borders
- tail collision logic created

Snake_1.1
- added field dimension (3 versions)
- added start screen
- added the ability to select the size of the field
- added ability to select speed

Snake_1.2
- Added the ability to control from the touchscreen

Snake_1.3
- removed the bug "collision with the tail during a quick double change of direction"
- optimized code for field selection and speed, code compressed into 40 lines

Snake_1.4
- added neon glow
- brought the repeating code for coloring and blanking the color of the snake into a separate function forIAndESquares
- decided that choosing 2 conditions before the game is too boring and introduced a choice of Difficulty, which changes the field size and speed

Snake_1.5
- The speed of the snake is increased by 2% at all levels for each square eaten. This can be tracked in the console.
