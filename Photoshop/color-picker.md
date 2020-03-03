# Photoshop - Color Picker Example

1. Open the file you're working with, in photoshop; in this example we will use a Photo by John Chris Cayetano from Unsplash: https://unsplash.com/photos/OH46N0QN7XA
2. Select the Eye Dropper Tool <img src="./images/eye-dropper-tool.jpg" alt="Select Eye Dropper Tool in toolbar" width="500" height="auto">
3. Select an area of your open image file, that you want to sample the color of <img src="./images/selecting-color.jpg" alt="Sample a new foreground color by clicking image" width="500" height="auto">
4. Double-Click the Foreground Color swatch <img src="./images/foreground-color-picker.jpg" alt="RGB and Hexidecimal values from sample click" width="500" height="auto">
5. Now you can use the RGB or Hex code (with `#` symbol) in your CSS 
``` CSS
/* Use RGB values for text color*/
.example-class {
    color: rgb(214, 64, 1);
}

/* If you want to use RGB but with an opacity/transparency value*/
.example-class {
    color: rgba(214, 64, 1, 0.6);
    /* The a stands for alpha channel. Accepted value is a decimal from 0 to 1. Where 0 is transparent and 1 is opaque*/
}

/* Use Hex code value for text color*/
.example-class {
    color: #d64001;
}
```