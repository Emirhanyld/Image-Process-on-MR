# PatientDataExtractor

This project focuses on extracting patient names from medical images using **OCR (Optical Character Recognition)** and organizing the output data automatically.  
After recognizing the patient name, the script crops a specific region of the image and saves it into a folder named after the detected patient.

## Features
- Extracts **patient name** from images using Tesseract OCR
- Preprocesses images with OpenCV for better OCR accuracy
- Crops a specific region of interest (ROI) from the image
- Creates a new folder for each patient based on their name
- Saves the cropped image into the corresponding folder automatically

## Technologies Used
- Python
- OpenCV
- PyTesseract
- NumPy
- Pillow (PIL)
- Google Colab (for development)

## Project Workflow
1. Load input medical image.  
2. Apply preprocessing (grayscale, blur, thresholding, morphology).  
3. Extract patient name using OCR.  
4. Define region of interest (ROI) and crop the image.  
5. Create a folder named after the patient.  
6. Save the cropped image into the folder.  
