# SA-C-GENDER-CLASSIFIER
# Algorithm
1.Install deepface

2.Import necessary packages

3.Read the image

4.Analyze the gender using deepface

## Program:
```python
"""
Program to implement Gender Classification
Developed by   : P S CHETAN
RegisterNumber :  212220230033
"""
from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt

img=cv2.imread('chetan.jpeg')
plt.imshow(img[:,:,::-1])
plt.show()

result=DeepFace.analyze(img2,actions=['gender'])
print("Gender : ",result['gender'])

```

## OUTPUT:

1. CODE :

![image](https://user-images.githubusercontent.com/75260837/172696636-a13ccb3f-0db3-483f-a3ae-f213ab5f705a.png)


2. DEMO VIDEO YOUTUBE LINK:
https://youtu.be/JRg7gW8PsPY
