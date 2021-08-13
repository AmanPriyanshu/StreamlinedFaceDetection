# StreamlinedFaceDetection
The project is meant to be used for simple streamlined implementations during competitions and hackathons. It is meant for Face Detection and will use the OpenCV-DNN framework which is one of the few fast, memory-efficient and easy to implement Face Detection models.

## Installation:

Terminal:

`git clone https://github.com/AmanPriyanshu/StreamlinedFaceDetection.git`

On Notebooks:

```py
!git clone https://github.com/AmanPriyanshu/StreamlinedFaceDetection.git
```

## Imports:

```py
from StreamlinedFaceDetection.detect import Detect
```

## Execution:

```py
d = Detect()

img = cv2.imread(path)
orig, img, boxes, confidences = d.detect_in_image(img)
```

## Display Images with Faces Bounded:

```py
import cv2

cv2.imshow(img)
```

On Google Colab:

```py
from google.colab.patches import cv2_imshow

cv2_imshow(img)
```
