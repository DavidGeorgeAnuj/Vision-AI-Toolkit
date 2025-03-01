**AI-Powered Object Detection, Face Matching, and Text Recognition**
====================================================================

**Description**
---------------

This project integrates multiple components, including:

*   **Object Detection** using the YOLOv8 model in real-time through a webcam or video file.
    
*   **Face Matching** between two images using OpenCV and a face embedding model.
    
*   **Text Recognition** from images using EasyOCR.
    

The project is implemented with a **Graphical User Interface (GUI)** using **CustomTkinter**, allowing users to select video files or use their webcam for object detection. Additionally, users can perform face matching and text extraction from images.

**Requirements**
----------------

To run this application, ensure you have the following dependencies installed:

### Python Dependencies:

Install the required packages using pip:

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   bashCopypip install opencv-python numpy torch easyocr customtkinter ultralytics   `

These dependencies include:

*   **opencv-python**: For image and video processing (including face matching and object detection).
    
*   **numpy**: For numerical operations in image processing.
    
*   **torch**: PyTorch framework to run the YOLOv8 model.
    
*   **easyocr**: Optical character recognition library for text extraction.
    
*   **customtkinter**: A modernized version of Tkinter to create the GUI.
    
*   **ultralytics**: Contains the YOLOv8 model for object detection.
    

**How to Use**
--------------

### **Object Detection**:

*   Launch the application and either select a video file or use your webcam for real-time object detection using YOLOv8.
    

### **Face Matching**:

*   Upload two images, and the app will compare the faces to check for matches, utilizing face embeddings.
    

### **Text Recognition**:

*   Upload an image, and EasyOCR will extract and display any text present in the image.
    

### **GUI Operations**:

The user-friendly GUI allows you to:

*   Choose a video file or activate the webcam for object detection.
    
*   Upload images for face matching and text recognition.
    
*   View the results in real time on the interface.
    

**Future Work / Enhancements**
------------------------------

*   **Advanced Object Detection**: Support more object categories or train YOLOv8 on custom datasets.
    
*   **Real-Time Face Matching**: Implement face matching with a live webcam feed.
    
*   **Multi-Language OCR**: Extend text recognition to support more languages with EasyOCR's multilingual capabilities.