# virtual-painting-using-openCV
Under this poject the user can draw on a virtual board using multiple colors of their choice. The project access the webcam and tracks the movement of the color objects using 
their HSV values. <br>
First select the colored marker or any object to draw of your choice.
To find the HSV values of the marker, run color_picker.ipynb. Using the trackbars determine HSV values of the marker.
Input those HSV values into the 'myColors' list, and the program will then be able to detect the object.
Associate apt color to be drawn with for the marker by inserting the desired BGR color in the 'myColorValues' list.
And you are then ready to draw virtually :) 
