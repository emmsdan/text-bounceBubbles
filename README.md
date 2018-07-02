# text-bounceBubbles

 Bounce bubbles when mouse interact with Text

## HOW TO USE
  
### Changing Color

#### // Color variables:
#### `red` = [0, 100, 63];
#### `orange` = [40, 100, 60];
#### `green` = [75, 100, 40];
#### `blue` = [196, 77, 55];
#### `purple` = [280, 50, 60];

### multiple colors
// Letters in the message will cycle through these colors:
letterColors = [red, green, orange, blue, purple];

### print message
message = 'Multiple colors!';

// Define color variables:
red = [0, 100, 63];
orange = [40, 100, 60];
green = [75, 100, 40];
blue = [196, 77, 55];
purple = [280, 50, 60];
letterColors = [red, orange, green, blue, purple];

### smallest distance at which a mouse will 
mouseResponseThreshold = 10;

### how strongly the dots will try to return to their starting position
friction = 0.8;

### how dots will rotate when interacting
rotationForce = 50.0;

### draw message
drawName(message, letterColors);
bounceBubbles();

