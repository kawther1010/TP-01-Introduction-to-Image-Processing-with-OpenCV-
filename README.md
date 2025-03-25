# 📷 TP 01: Introduction to Image Processing with OpenCV  

## 🎯 Objective  
Understand how to read, display, and save images using OpenCV.  

## 📝 Exercises  

### 🔹 Exercise 01: Reading, Displaying, and Saving an Image  
1. Read the image from the file **`rose 1024.tif`** and display its size.  
2. Display the image and retrieve the pixel values at positions **(0,0)**, **(10,10)**, and **(15,30)**.  
3. Save this image in a different format (e.g., **PNG**).  

### 🔹 Exercise 02: Basic Image Processing Operations  
Using the grayscale image **`rose 1024.tif`** with a size of **1024 × 1024**, implement the following operations:  
1. Read the image **f**.  
2. Flip the image **f** vertically.  
3. Crop the region of the image **f** defined by the rectangle `[257:768, 257:768]`.  
4. Resample the image **f** by reducing its size by half.  
5. Extract and display the intensity profile of the middle horizontal line (**512th row**).  

## 🔧 Useful Functions  
### 📌 `cv2.flip(image, flipCode)`  
- **`image`** : The input image.  
- **`flipCode`** : Defines the type of flip:  
  - `0` : Vertical flip.  
  - `>0` : Horizontal flip.  
  - `<0` : Both horizontal and vertical flip.  

## 🚀 Installation & Execution  
1. Install dependencies:  
   ```bash
   pip install opencv-python numpy matplotlib
