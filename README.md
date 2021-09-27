# simple-object-tracker-by-color
__Simple red, green or blue object tracker__</br>
The user inputs the color __*(Red, Green, or Blue)*__ of the object that he wants to track, then the code changes the color from __*BGR*__ space to __*HSV*__ space</br>
### NOTE
We change from __*BGR*__ not __*RGB*__ because __*OpenCV*__ reads the image in BGR space
## What is HSV color space?
HSV __(Hue, Saturation and Value)__</br>
defines a type of color space. It is similar to the modern RGB and CMYK models. The HSV color space has three components: hue, saturation and value.</br>
### Hue
In HSV, hue represents color. In this model, hue is an angle from 0 degrees to 360 degrees.</br>
### Saturation
Saturation indicates the range of grey in the color space. It ranges from 0 to 100%. Sometimes the value is calculated from 0 to 1. When the value is ‘0,’ the color is grey and when the value is ‘1,’ the color is a primary color. A faded color is due to a lower saturation level, which means the color contains more grey.</br>
### Value
Value is the brightness of the color and varies with color saturation. It ranges from 0 to 100%. When the value is ‘0’ the color space will be totally black. With the increase in the value, the color space brightness up and shows various colors.</br></br>
![hsv](https://user-images.githubusercontent.com/74217535/134833221-4824440d-8f10-440b-8c79-b1b46cd63a0e.png)
</br>
## NOTE 
You can find a video of the run __*"object_color_detection .mp4"*__, and there is a __*"requirements.txt"*__ do not forget it and __*take into account when you opening the camera the lighting in the place*__ 
