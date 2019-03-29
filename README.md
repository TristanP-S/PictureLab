# PictureLab
PictureLab Project For APCSA done with Connor Powell
## Questions
### Activity 1
1. How many bits does it take to represent the values from 0 to 255?
- 8
2. How many bytes does it take to represent a color in the RBG color model?
- It takes three bytes to represent a color on the RBG model.
3. How many pixels are in a picture that is 640 pixels wide and 480 pixels high?
- There are 307200 pixels in a 640 x 480 pixel picture.
### Activity 2
1. How can you make pink?
- java.awt.Color[255,0,255]
2. How can you make yellow?
- java.awt.Color[255,255,0]
3. How can you make purple?
- java.awt.Color[150,0,150]
4. How can you make white?
- java.awt.Color[255,255,255]
5. How can you make dark gray?
- java.awt.Color[75,75,75]
### Activity 3
1. What is the row index for the top left corner of the picture?
- 0
2. What is the column index for the top left corner of the picture?
- 0
3. The width of this picture is 640. What is the right most column index?
- 639
4. The height of this picture is 480. What is the bottom most row index?
- 479
5. Does the row index increase from left to right or top to bottom?
- Top to bottom
6. Does the column index increase from left to right or top to bottom?
- Left to right
7. Set the zoom to 500%. Can you see squares of color? This is called pixelation. Pixelation means
displaying a picture so magnified that the individual pixels look like small squares.
- Yes
### Activity 5
1. Open Picture.java and look for the method getPixels2D. Is it there?
- No, just several lines calling for it
2. Open SimplePicture.java and look for the method getPixels2D. Is it there?
- Yes
3. Does the following code compile?
- **DigitalPicture p = new DigitalPicture();**
- No, DigitalPicture is an interface, so it can't be an object
4. Assuming that a no-argument constructor exists for SimplePicture, would the following
code compile?
- **DigitalPicture p = new SimplePicture();**
- Yes
5. Assuming that a no-argument constructor exists for Picture, would the following
compile?
- **DigitalPicture p = new Picture();**
- Yes
6. Assuming that a no-argument constructor exists for Picture, would the following
compile?
- **SimplePicture p = new Picture();**
- Yes
7. Assuming that a no-argument constructor exists for SimplePicture, does the following
code compile?
- **Picture p = new SimplePicture();**
- No
### Activity 7
1. How many times would the body of this nested for loop execute?
- **for (int row = 7; row < 17; row++)**
- **for (int col = 6; col < 15; col++)**
- This loop will execute 90 times
2. How many times would the body of this nested for loop execute?
- **for (int row = 5; row <= 11; row++)**
- **for (int col = 3; col <= 18; col++)**
- This loop will execute 117 times.
## Exercises
### Acitivty 3
- 1: Complete (removed after completion)
- 2: Complete (using mairo.png)
### Activity 4
- 1: Complete
- 2: Complete
- 3: Complete
### Activity 5
- 1: Complete
- 2: Complete
- 3: Complete
- 4: Complete
- 5: Complete
- 6: Complete
### Activity 6
- 1: Complete
- 2: Complete
- 3: Complete
- 4: Complete
### Activity 7
- 1: Complete
- 2: Complete
- 3: Complete
### Activity 8
- 1: Incomplete
- 2: Incomplete
### Activity 9
- 1: Incomplete
- 2: Incomplete
