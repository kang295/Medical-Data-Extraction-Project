# Medical Data Extraction Project

## Technical Architecture of the Project
1. pdf2image library to convert pdf document to a list of images
   (apply some image processing techniques)
2. OpenCV for basic image processing to make images clearer
   (making the pixel intensity uniform)
3. Pytesseract library to extract text from an image
   (Google's Tesseract engine to convert images into text)
4. Regular expression (a.k.a.regex) to extract useful information (or fields) from a text block
