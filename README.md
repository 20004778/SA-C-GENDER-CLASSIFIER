# SA-C-GENDER-CLASSIFIER
# Algorithm
1. To classify the gender of a person use the DeepFace library.
2. DeepFace library is developed based on deep learning algorithms.
3. Import the deepface class from DeepFace library, cv2 class from openCv2 library and Matplot library according to the requirements.
4. Load and display the imported image.
5. Pass the image to DeepFace library and analyze the image to predict gender of a person.
6. This prediction is stored in result variable.
7. Finally print the prediction using this algorithm.

## Program:
```
/*
Program to implement 
Developed by   : SURYA R
RegisterNumber :  212220230052
*/
```

1. CODE :
```python
!pip install deepface
from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt
img1=cv2.imread('6.jpg')
plt.imshow(img1[:,:,::-1])
plt.show()
result=DeepFace.analyze(img1,actions=['gender'])
print("Gender : ",result['gender'])
img2=cv2.imread('i.jpg')
plt.imshow(img1[:,:,::-1])
plt.show()
result=DeepFace.analyze(img2,actions=['gender'])
print("Gender : ",result['gender'])
```

## OUTPUT:

![image](https://user-images.githubusercontent.com/75236145/173177059-760936a5-cce2-49a7-a4ff-cd31628d248a.png)
![image](https://user-images.githubusercontent.com/75236145/173177035-d592f6ee-a680-4117-8be7-89f4aa8fcfbc.png)

2. DEMO VIDEO YOUTUBE LINK:



