# AI-Powered-Human-Body-Shape-Classification-System
Developed an advanced computer vision system designed to analyze and classify human body shapes (e.g., Inverted Triangle, Rectangle, Apple) for both men and women. Built using the YOLOv5 architecture and PyTorch. Integrated OpenCV for dynamic image rendering and bounding box visualization to deliver precise physical trait analysis.
### Key Contributions:
* Trained and deployed a custom model (`best.pt`) tailored to recognize complex human body structures and categorize them into specific geometrical shapes.
* Engineered the pipeline to simultaneously detect gender and body type variations, ensuring robust multi-class classification.
* Utilized OpenCV for reliable image preprocessing and automated scaling, facilitating clean visual output with labeled body feature boxes.
* Resolved OS-specific path issues using `pathlib` to guarantee seamless cross-platform deployment.

### Technologies & Tools:
* **Programming Language:** Python
* **Frameworks & Libraries:** PyTorch, YOLOv5, OpenCV, NumPy
