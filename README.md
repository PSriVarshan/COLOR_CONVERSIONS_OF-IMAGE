# COLOR_CONVERSIONS_OF-IMAGE

## AIM

#### To write a python program using OpenCV to do the following image manipulations.

i) Read, display, and write an image.

ii) Access the rows and columns in an image.

iii) Cut and paste a small portion of the image.

iv) To perform the color conversion between RGB, BGR, HSV, and YCbCr color models.


## Software Required:

### Anaconda - Python 3.7

## Algorithm:

### Step 1
Choose an image and save it as a filename.jpg ,
### Step 2
Use imread(filename, flags) to read the file.
### Step 3
Use imshow(window_name, image) to display the image.
### Step 4
Use imwrite(filename, image) to write the image.
### Step 5
End the program and close the output image windows.
### Step 6
Convert BGR and RGB to HSV and GRAY
### Step 7
Convert HSV to RGB and BGR
### Step 8
Convert RGB and BGR to YCrCb
### Step 9
Split and Merge RGB Image
### Step 10
Split and merge HSV Image


``` python
Developed By: Sri Varshan P
Register Number: 212222240104
```

#### IMAGE 

![WhatsApp Image 2024-02-12 at 22 45 58_61274ce4](https://github.com/swedha333/COLOR_CONVERSIONS_OF-IMAGE/assets/114944059/584633de-5b50-4455-9ed1-871d2fdcbbd8)


## Program:


### i) Read and display the image
``` py
#Read and display the image
import cv2
image=cv2.imread('city.jpg',1)
image=cv2.resize(image,(200,325))
cv2.imshow('Psv',image)
cv2.waitKey(0)
cv2.destroyAllWindows()
```


### Output:

![image](https://github.com/swedha333/COLOR_CONVERSIONS_OF-IMAGE/assets/114944059/40578dba-1b99-4636-aa00-79893b54490d)

## Program:


### ii)Write the image

```py
#Write the image
import cv2
image=cv2.imread('city.jpg',0)
cv2.imwrite('demos.jpg',image)
```

### 

### iii)Shape of the Image

<br>
<br>

### iv)Access rows and columns
<br>
<br>

### v)Cut and paste portion of image
<br>
<br>

### vi) BGR and RGB to HSV and GRAY
<br>
<br>

### vii) HSV to RGB and BGR
<br>
<br>

### viii) RGB and BGR to YCrCb
<br>
<br>

### ix) Split and merge RGB Image
<br>
<br>

### x) Split and merge HSV Image
<br>
<br>




## Result:
Thus the images are read, displayed, and written ,and color conversion was performed between RGB, HSV and YCbCr color models successfully using the python program.







