# National ID Card Recognition

---

## Overview

The National ID Card Recognition project aims to develop a system for extracting and structuring information from national ID card images using Optical Character Recognition (OCR) and image processing techniques. By leveraging Tesseract OCR for text recognition and OpenCV for image preprocessing, this project provides an efficient way to digitize and organize ID card data.

## Purpose

This recognition system helps:

- **Automated Data Entry:** Simplify and accelerate the process of entering ID card information into databases or systems.
- **Data Organization:** Extract structured data from ID cards, including personal details and document numbers.
- **Accuracy Improvement:** Enhance the accuracy of data extraction with advanced image preprocessing techniques.

## Usage

1. **Set Up:** Install the required libraries using:
   ```bash
   pip install pytesseract opencv-python pandas
   ```
   Ensure Tesseract OCR is installed on your system. Refer to the [Tesseract installation guide](https://github.com/tesseract-ocr/tesseract) for instructions.

2. **Image Preprocessing:** 
   - Load ID card images using OpenCV.
   - Apply preprocessing techniques such as grayscale conversion, noise reduction, and edge detection to improve text recognition accuracy.
   - Use methods like contour detection and perspective transformation to isolate and enhance the ID card region.

3. **Text Recognition:**
   - Use Tesseract OCR to extract text from preprocessed images.
   - Fine-tune OCR parameters to match the specific layout and text style of national ID cards.

4. **Data Extraction and Structuring:**
   - Extract relevant information such as Full Name, Date of Birth, Place of Birth, Number, and Issued On from the recognized text.
   - Combine extracted fields into a structured format and store them in a pandas DataFrame for further processing or database entry.

5. **Testing and Validation:**
   - Test the system with various national ID card images to ensure robustness and accuracy.
   - Validate the extracted data against known information to assess performance.

## Contributors
**This project was made by**

[Omar (Ven)](https://github.com/VenStudio)

*This project was made for a course from [ElectoPI](https://alcamp.electropi.ai/)*

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
