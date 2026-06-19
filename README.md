# AI-Powered-Human-Body-Shape-Classification-System
Developed an advanced computer vision system designed to analyze and classify human body shapes (e.g., Inverted Triangle, Rectangle, Apple) for both men and women. Built using the YOLOv5 architecture and PyTorch. Integrated OpenCV for dynamic image rendering and bounding box visualization to deliver precise physical trait analysis.
<img width="1280" height="752" alt="image" src="https://github.com/user-attachments/assets/a2adab94-4b75-4a49-bfd5-124fab4adde4" />
<img width="1280" height="872" alt="image" src="https://github.com/user-attachments/assets/6459c28a-7af6-47f6-a507-b63492a6f11b" />
<img width="1280" height="701" alt="image" src="https://github.com/user-attachments/assets/4be5889f-4dfb-4d16-ad6b-6846cebea97e" />


https://github.com/user-attachments/assets/cb30f04e-0ba9-4b92-9805-1aaca33ee7f1




### Key Contributions:
* Trained and deployed a custom model (`best.pt`) tailored to recognize complex human body structures and categorize them into specific geometrical shapes.
* Engineered the pipeline to simultaneously detect gender and body type variations, ensuring robust multi-class classification.
* Utilized OpenCV for reliable image preprocessing and automated scaling, facilitating clean visual output with labeled body feature boxes.
* Resolved OS-specific path issues using `pathlib` to guarantee seamless cross-platform deployment.

### Technologies & Tools:
* **Programming Language:** Python
* **Frameworks & Libraries:** PyTorch, YOLOv5, OpenCV, NumPy
