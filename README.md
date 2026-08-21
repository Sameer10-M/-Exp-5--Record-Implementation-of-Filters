# Exp-5--Record-Implementation-of-Filters

# Image Smoothing and Sharpening Using OpenCV

## Name : Sameer shariff M
## Reg no : 212224220085

## Aim

To write a Python program using OpenCV to apply different smoothing filters (Averaging, Weighted Averaging, Gaussian, Median) and sharpening filters (Laplacian Kernel and Laplacian Operator) for image enhancement, and display each result separately along with the original image for comparison.

---

## The program performs the following operations:

- Read and display an input image  
- Apply Averaging filter  
- Apply Weighted Averaging filter  
- Apply Gaussian filter  
- Apply Median filter  
- Apply Laplacian sharpening using kernel  
- Apply Laplacian operator  
- Display all outputs for comparison  

---

##  Software Used

- Anaconda – Python 3.7  
- Jupyter Notebook / VS Code  
- OpenCV (cv2)  
- NumPy  
- Matplotlib  

---

##  Algorithm

### Step 1:
Import the required libraries: OpenCV, NumPy, and Matplotlib.

### Step 2:
Read the input image (e.g., `image.jpg`).

### Step 3:
Convert the image from BGR to RGB format for display.

### Step 4:
Apply Averaging Filter using `cv2.blur()`.

### Step 5:
Apply Weighted Averaging Filter using a custom kernel with `cv2.filter2D()`.

### Step 6:
Apply Gaussian Filter using `cv2.GaussianBlur()`.

### Step 7:
Apply Median Filter using `cv2.medianBlur()`.

### Step 8:
Apply Laplacian Sharpening using Kernel with `cv2.filter2D()`.

### Step 9:
Convert image to grayscale and apply Laplacian Operator using `cv2.Laplacian()`.

### Step 10:
Display all filtered images using a grid layout for comparison.

---

##  Developed By

- **Name: Vignesh S**   
- **Register No: 21222411061 ** 

---

##  Output

### Smoothing Filters

- Averaging filter produces blurred image  
- Weighted averaging provides smoother result with less distortion  
- Gaussian filter preserves edges better while reducing noise  
- Median filter removes salt-and-pepper noise effectively  

###  Sharpening Filters

- Laplacian kernel enhances edges and fine details  
- Laplacian operator detects edges clearly in grayscale

<img width="897" height="565" alt="Screenshot 2026-08-21 102201" src="https://github.com/user-attachments/assets/23b5da8f-d4ba-45c6-897f-149b892a0ee0" />

<img width="656" height="418" alt="Screenshot 2026-08-21 102206" src="https://github.com/user-attachments/assets/b669b983-d89b-4b20-a051-780c70d910f1" />

<img width="640" height="415" alt="Screenshot 2026-08-21 102211" src="https://github.com/user-attachments/assets/724245f6-2a8b-443d-94ff-c9f7845fd13a" />

<img width="892" height="559" alt="Screenshot 2026-08-21 102216" src="https://github.com/user-attachments/assets/60016f69-522a-4ab2-b961-5e69e810e0b4" />





---

##  Result

Thus, smoothing filters and sharpening filters are successfully implemented using OpenCV.
