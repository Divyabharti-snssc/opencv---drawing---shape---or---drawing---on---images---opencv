# ## Nalanda It Zone 
* ** Project report under Nalanda it Zone internship program.
  # Name : **Divya Bharti
  # Course : **BSC (5th Semester)
  # Session : **(2024-2028)
  # University Roll Number : **(24281200454)
  # University Registration Number : **(24120023228)
  # College Name : S.N. Sinha College
  
  # Institute Name : **Nalanda It Zone
  
  # Application ID : **(2PFWM0BB)
  
  # Project Topic : **OpenCV - drawing  - shape - or - drawing - on - images - OpenCV .

# ## Drawing shapes and Text on images in OpenCV.
* ** Topic:** Putting Text, Rectangles Circules On Images in OpenCV.

This project demonstrates how to use Opencv 's built-in drawing functions to overly shapes and costome text on an image or blank convas.

---

## Implementation Code('draw_shapes.py)

'''python
import cv2
import numpy as np

# 1. Create a black convas (500×500 pixels, 3 colour channels)
Canvas = np.Zeros(500, 500, 3), dtype = np.unit8

# 2. Draw  a Rectangle 
# Parameters: image, top-lift corner,  bottom-right corner, colour (BGR), thickness 
cv2.rectangle(canvas, (50, 50),(250×250), 3) # Green Rectangle 

# 3. Draw a Circle 
# Parameters: image, centre coordinates, radius, colours (BGR),  thickness(-1 fill the circle)
cv2.circle(canvas,(350, 150, 60, (0, 0, 255), -1) # Filled Red Circle 

# 4. Put Custom Text
  Parameters: image, test, starting co-ordinate, font, scale, color (BGR), thickness 
cv2.put Text(canvas, "OpenCV Drawing ",(50, 400), cv2.FONT-HERSHEY-SIMPLECX,1,(255, 255, 255),:

# 5. Display Theresult
cv2.imshow("Drawing Shapes & Text", Canvas)
cv2.waikey(0)
cv2.destroy AllWindows ()
'''

---

## Functions Explained
* **'cv2'.rectangle()'**: Used to highlight regions of interest (like drawing bounding boxes around faces).
* **'cv2'.Circle()'**: Useful for marking a specific keypoints or target centres on an image.
* **'cv2'.putText Essential for rendering()'**: Lables, predictions test, or confidence score dynamical.






