# anpr
Global ANPR, the ANPR code has been optimized to recognize universal plate. This was originally an assignment task given by APU university.

## Task
Given a set of 12 photos of cars plate with a different angle and from various countries.
create an automatic plate number recognition to automatically extract the plate from the photo.

## Code
The technique was simplified into 4 main things: 
*The rest is just processing the image*
1. It was done by morphing into arbitrary shape which have rectangular ratio usually ranged from 1 - 5.
2. Doing shape recognition and take 5 clostest shape from rectangle.
3. Crop the coordination from the clostest shape and order it from the best candidate ( the higher ratio the better ) and the shape recognized as rectangle.
4. Do the OCR.

