# modularTurtleButtons
Having buttons with gturtle is no longer that difficult to make.

Prequisites to using:
- copied the buttons script near the main script
- imported the script into the main script
- have a turtle aleready made in your main script
- repeat the following inside your main script:
  "def onClick(x, y):
    Button.handle_click(x, y)"

After that just make a button like the following:
"easy_button = Button(-250, -200, 200, 100, "green", "Easy")
easy_button.make()"
