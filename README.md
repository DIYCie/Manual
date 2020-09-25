# Manual

## Extra software info
In your app there are also two functions to handle button interaction: _onButtonPressed(button)_ and _onButtenReleased(button)_. These functions are called when a button is pressed or released, the _button_ variable holds the actual button that is pressed or released. The button can have of the following values:
-	Button.UP
-	Button.DOWN
-	Button.LEFT
-	Button.RIGHT
-	Button.A
-	Button.B

In the functions you can easily check if a specific button was pressed by using an if statement like this: _if (button === Button.UP)_.
