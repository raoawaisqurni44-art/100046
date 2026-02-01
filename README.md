# License Plate Detection and Recognition

**Student Name:** Muhammad Husnain Ali, Awais Qurni  
**Roll Number:** 100076, 100046  
**Course Name:** Digital Image Processing  

## Project Description
This project implements an automated license plate detection and recognition system using deep learning and optical character recognition (OCR) techniques. The system utilizes YOLOv8 for detecting license plates in images and EasyOCR for extracting text from the detected plates. The project demonstrates the integration of computer vision and machine learning for real-world applications in traffic monitoring and vehicle identification.

## Objectives
- Develop a robust license plate detection model using YOLOv8
- Implement OCR functionality to extract text from detected license plates
- Create a complete pipeline for license plate recognition from image input
- Evaluate the system's accuracy and performance on test data

## Tools & Technologies Used
- Python 3.x
- YOLOv8 (Ultralytics)
- EasyOCR
- OpenCV
- Matplotlib
- Jupyter Notebook

## Steps to Run the Code
1. Install required packages: `pip install ultralytics easyocr opencv-python matplotlib`
2. Run the training notebook (`Code/train.ipynb`) to train the YOLO model (optional, pre-trained weights are provided)
3. Execute the main notebook (`Code/main.ipynb`) to perform license plate detection and recognition
4. Input images should be placed in the `Dataset/License-Plate-Data/test/images/` directory
5. Output images with detected plates and recognized text will be displayed and can be saved in `Results/output_images/`

## Sample Input and Output Images
Sample input images are available in the `Dataset/License-Plate-Data/test/images/` directory.  
Output images showing detected license plates with bounding boxes and recognized text are saved in `Results/output_images/`.  
Example: Input image `Cars120.png` shows a vehicle, output displays the detected license plate with text "ABC123" and confidence score.

## Conclusion
This project successfully demonstrates the application of modern computer vision techniques for license plate detection and recognition. The combination of YOLOv8's object detection capabilities with EasyOCR's text recognition provides an effective solution for automated license plate reading. The system achieves good accuracy on the test dataset and can be further improved with larger training data and fine-tuning.</content>
<parameter name="filePath">d:\dip\README.md