## Undo mistakes

Sometimes mistakes happen, so add a 'clear' button and an eraser button.

--- task ---
Add the 'X-block' sprite from the library's letters section. Colour the sprite's costume in red and make it a little smaller. This sprite is the 'clear' button.

[[[generic-scratch-sprite-from-library]]]

![screenshot](images/paint-x.png)
--- /task ---

--- task ---
Add code to the 'X-block' sprite to clear the Stage when the sprite clicked.

![cross](images/cross.png)
![blocks_1545215460_5247564](images/blocks_1545215460_5247564.png)
--- /task ---

You don't need to use a `broadcast`{:class="blockevents"} to clear the Stage, because the `clear`{:class="blockpen"} block does that job.

Do you see that the pencil sprite includes an eraser costume?

![screenshot](images/paint-eraser-costume.png)

Your project also includes a separate eraser sprite. 

--- task ---
Right-click on this eraser sprite and then click on **show**. Here is how your Stage should look now:

![screenshot](images/paint-eraser-stage.png)
--- /task ---

--- task ---
Add code to the eraser sprite to send an `'eraser' broadcast`{:class="blockevents"} when the eraser sprite is clicked.

![eraser](images/eraser.png)
![blocks_1545215461_6310802](images/blocks_1545215461_6310802.png)
--- /task ---

When the pencil sprite receives the 'eraser' message, it should switch its costume to the eraser and switch the pen colour to white, which is the same colour as the Stage!

--- task ---
Add some code to create the eraser.

--- hints ---
--- hint ---
Add some code to the pencil sprite:
`When I receive`{:class="blockevents"} the `eraser`{:class="blockevents"} message
`Switch to costume eraser`{:class="blocklooks"} 
`Set pen color`{:class="blockpen"} to white
--- /hint ---
--- hint ---
Here are all the blocks you need:
![blocks_1545215462_7428753](images/blocks_1545215462_7428753.png)
--- /hint ---
--- hint ---
Here is what the code should look like:
![blocks_1545215463_9098535](images/blocks_1545215463_9098535.png)
--- /hint ---
--- /hints ---
--- /task ---

--- task ---
Test your project to see if you can clear the Stage and erase pencil lines.

![screenshot](images/paint-erase-test.png)
--- /task ---

There's one more problem with the pencil: you can draw anywhere on the Stage, including near the 'clear' and eraser buttons!

![screenshot](images/paint-draw-problem.png)

--- task ---
To fix this, change the code so that the pen is only down if the mouse is clicked __and__ the `y` position of the mouse pointer is greater than `-120`:

![pencil](images/pencil.png)
![blocks_1545215465_0457473](images/blocks_1545215465_0457473.png)
--- /task ---

--- task ---
Test your project. You now should not be able to draw near the buttons.

![screenshot](images/paint-fixed.png)
--- /task ---
