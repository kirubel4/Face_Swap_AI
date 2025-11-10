# Face_Swap_AI


This project demonstrates how to extract and swap human faces between two images using **OpenCV**, **Dlib**, and **PIL (Pillow)**.  
By leveraging **facial landmark detection** and **Delaunay triangulation**, we can seamlessly reconstruct and blend one face onto another, achieving realistic face replacement effects.

---

## 🔍 Overview

Face swapping is a multi-step image processing pipeline that involves:

1. Detecting facial landmarks on both source and target images.  
2. Triangulating facial regions using **Delaunay triangulation**.  
3. Warping corresponding triangles from the source face to match the destination face geometry.  
4. Seamlessly blending the swapped face onto the target image using **Poisson seamless cloning** provided by OpenCV.

This technique can be used for:
- Augmented reality filters  
- Face morphing and reconstruction  
- Entertainment and visual effects  
- Computer vision research and experimentation

---

## 🧠 Key Technologies

- **Python 3**
- **OpenCV** — for image processing and affine transformations  
- **Dlib** — for landmark detection via pretrained models  
- **NumPy** — for numerical operations  
- **PIL (Pillow)** — for image loading and conversions  
- **Requests** — for downloading remote images  

---

