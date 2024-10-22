## 10/22/24, Drawing

### The canvas

In p5.js, the canvas is your drawing area, where all your shapes and designs will come to life. Here’s the basic structure of a p5.js sketch:

```js
function setup(){
  // This runs once, at the start
}

function draw(){
  // This runs in a loop, over and over again
}
```

The p5.js canvas is divided into two parts:

1. `setup()`: This function runs only once when the program starts. It’s where to put anything that only needs to happen once, like creating your canvas.

2. `draw()`: This function runs continuously, refreshing the screen at around 60 frames per second by default. Anything you put in `draw()` will be repeated every frame, so it can be used for animation and dynamic changes.

#### So, what do I do now?
Let’s start by creating a small canvas and adding a background color. We’ll start with a 400x400 pixel canvas.

1. Create a canvas inside `setup()`:
    ```js
    function setup(){
      createCanvas(400, 400);
    }
    ```
This line creates a canvas that’s 400 pixels wide and 400 pixels tall, just the right size for making bite-sized art.

2. Add a background color inside `draw()`:
    ```js
    function setup(){
      createCanvas(400, 400);
    }

    function draw(){
      background(255); // 255 is white
    }
    ```
    The `background(255)` line fills the entire canvas with white every frame. The number `255` represents the maximum brightness in grayscale, so it gives you a solid white background. You can replace `255` with other values (0 is black, and any number between 0 and 255 gives you shades of gray).

With these two steps, you now have a blank canvas ready to be filled with shapes, colors, and designs.

#### What's next?

Now that we have a blank canvas, let's draw some shapes and begin exploring the basic building blocks of visual design in p5.js.

### Line

### Square

### Circle

### Triangle

### Quadrilaterals
