## Coloured pencils

Now you're going to add different coloured pencils to your project and allow the user to choose between them.

--- task ---
Click on the pencil sprite, click on **Costumes**, and duplicate the 'pencil-blue' costume.

![screenshot](images/paint-blue-duplicate.png)
--- /task ---

--- task ---
Name the new costume 'pencil-green', and colour the pencil green.

![screenshot](images/paint-pencil-green.png)

--- /task ---

--- task ---
Draw two new sprites: one blue square and one green square. These are for choosing between the blue and green pencil.

![screenshot](images/paint-selectors.png)
--- /task ---

--- task ---
Rename the new sprites so that they are called 'blue' and 'green'

[[[generic-scratch-rename-sprite]]]

--- /task ---

--- task ---
Add some code to the 'green' sprite so that when this sprite is clicked, it `broadcasts`{:class="blockevents"} the message "green".

![green square](images/green_square.png)
![blocks_1545215454_9892426](images/blocks_1545215454_9892426.png)

[[[generic-scratch-broadcast-message]]]
--- /task ---

The pencil sprite should listen for the "green" message and change its costume and pencil colour in response.

--- task ---
Switch to your pencil sprite. Add some code so that when this sprite receives the `green`{:class="blockevents"} broadcast, it switchs to the green pencil costume and changes the pen colour to green.

![pencil](images/pencil.png)

![blocks_1545215456_0834806](images/blocks_1545215456_0834806.png)

To set the pencil to colour to green, click the coloured square in the `set pen color`{:class="blockpen"} block, and then click on the green square sprite.
--- /task ---

Then to a similar thing so that you can switch the pencil colour to blue.

--- task ---
Click on the blue square sprite and add this code:

![blue_square](images/blue_square.png)
![blocks_1545215457_1853302](images/blocks_1545215457_1853302.png)

Then click on the pencil sprite and add this code:
![pencil](images/pencil.png)
![blocks_1545215458_3099954](images/blocks_1545215458_3099954.png)
--- /task --- 

--- task ---
Finally, add this code to tell the pencil sprite which colour to start with, and to make sure that the screen is clear when your prom starts.

![pencil](images/pencil.png)
![blocks_1545215459_4364326](images/blocks_1545215459_4364326.png)
--- /task ---

If you prefer, you can start with a different colour pencil.

--- task ---
Test your code. Can you switch between the blue and green pencil colours by clicking on the blue or green square sprites?

![screenshot](images/paint-pens-test.png)
--- /task ---

