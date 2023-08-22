# Indian-Flag-Using-Python-Turtle
Introduction:
In this project, we will show how to use Turtle graphics using Python to make our Indian flag. Turtle is a pre-installed library in Python used to design a virtual canvas. In simple language, it’s a tool that helps you to draw on a board in your program with the help of a few commands. These commands are basically related to directions or the start and stop of drawing. So gear up with your IDE and try this out!

Explanation:
As turtle is a library in Python, we will first start by importing it into our program using the import keyword. Next, we import * from the turtle, this means that all the functions defined in the turtle library will be imported and are free to use in this code.

The second step is to create a screen or your drawing board for the graphics. This can be done by using a turtle.Screen(). This assigns a screen to the variable screen. Now to draw, you will need a medium. On paper, it’s your pencil, and with the virtual board or screen it’s the turtle. Hence, we assign turtle to the variable t using turtle.Turtle() and set its speed to 0. Speed settings can be set between 1 (slowest) to 10 (fastest). At speed 0, all animations are stopped and the turtle can go as fast as possible.

Now, the only thing left to do is to draw.

Start by lifting the pen up which means that it won’t draw whatever direction it goes. Now set the location of the pen(turtle) to the coordinates (-400,250) using method goto(). The coordinates may differ from person to person. Now, initially, the screen is white, so you won’t need to create the white rectangle for the flag but green and orange and also the Ashoka Chakra.

Firstly, we set the color to orange and next use begin_fill() so that it fills the shape with orange color as the border is created. Next, we set the directions for the turtle to move using methods like right(), left(), and forward(). The trick we used here is after we created the orange rectangle, we extended the vertical left line to reach the co-ordinated where the green rectangle begins. The same steps are to be followed for the green rectangle.

Remember to penup() as we move to the center of the white rectangle for the Ashoka Chakra.

The logic here is to make a big circle with the color navy blue. Then draw another circle concentric to this circle with a smaller radius. Concentric circles are circles with the same center with different radii. This will give a circular border effect. Similarly, we draw a small navy blue circle over the white circle in the center. Repeat the steps! =>

t.penup() => t.goto() => t.pendown() => t.color() => t.begin_fill() => t.circle() => t.end_fill()

Following the above step next we draw 24 circles on the border and connect to the center by drawing spokes and this is done by using the for loop. And bravo! You have learned to use a turtle and make your flag in it.

