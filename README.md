#  Face Sunglass Filter using OpenCV

This project applies a virtual sunglasses filter on a face image using OpenCV.  

---

##  Features
- Detects and selects eye region manually
- Resizes sunglasses to fit face proportion
- Uses masking for realistic overlay
- Blends sunglasses with the original image smoothly

---

##  Technologies Used
- Python
- OpenCV
- NumPy
- Matplotlib

---

##  Demo

### Input Image
<img width="674" height="446" alt="image" src="https://github.com/user-attachments/assets/af131a95-4ec9-47d8-aaa4-ff23bb75a96a" />


### Output Image
<img width="675" height="436" alt="image" src="https://github.com/user-attachments/assets/8deb1ab5-ce68-4b25-9eae-a288bc676488" />

---

## ⚙️ How It Works

1. Load the face image and sunglasses image  
2. Resize sunglasses according to face dimensions  
3. Create a mask for blending  
4. Extract eye region (ROI)  
5. Apply:
   - Mask on face
   - Mask on sunglasses  
6. Combine both using image arithmetic  
7. Place final output back on the face  

---
## Conclusion
Implemented a sunglasses overlay system using OpenCV by applying image resizing, masking, and ROI-based blending, demonstrating practical skills in computer vision and image processing.
