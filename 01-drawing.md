## 22/10/24 ~ ? - Drawing

### The Canvas

This is your canvas:
```js
function setup(){

}

function draw(){
  
}
```

The p5.js canvas is divided to 2 parts:

1. Anything in `setup()` **runs** only **once**, right when you open the canvas (or when you hit that "play" button on p5.js editor).
2. Meanwhile, everything in `draw()` is **repeated** every frame.

#### So, what do I do now?

1. Create a canvas in `setup()`:

   ```js
   function setup(){
     createCanvas(windowWidth, windowHeight)
   }
   ```
   
2. Then, add a background color in `draw()`:

   ```js
   function setup(){
     createCanvas(windowWidth, windowHeight)
   }

   function draw(){
     background(255)
   }
   ```
3. And we're done. We've created a white canvas for us to draw.


### Squares

### Circles

### Triangles
