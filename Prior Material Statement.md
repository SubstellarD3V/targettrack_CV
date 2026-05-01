# targettrack_CV
Foundational files for enabling coherent target tracking of a tennis ball using a Pi 5 w/ Camera 3, AI HAT+  

'As per BEng Project Guidelines, the following external material was used as foundations for this project:

Computer Vision Model: The baseline object detection model was the open-source YOLOv26n model provided by Ultralytics. It was pre-trained on the COCO (Common Objects in Context) dataset. It was then fine-tuned on a custom dataset generated for this project
Model Compilation Software: The Hailo Dataflow Compiler was used to perform post-training quantisation (PTQ) and convert the YOLOv26n model into a Hailo Executable File (.hef) compatible with the AI HAT+ NPU (Neural Processing Unit).
Dataset Annotation Tools: The third-party platform Roboflow was used to create the bounding-box annotations of the custom tennis ball dataset.
Mechanical Hardware: A premade PETG plastic mini-pan-tilt kit was purchased and physically modified (cutting of the provided SG90 servo horns) to fit the system requirements.
Software Libraries: Open-source Python libraries, including those necessary for interfacing with the PCA9685 Servo Driver HAT, the Pi Camera 3, and standard computer vision frameworks (such as OpenCV, as researched in initial project scoping), were used to bridge the hardware and software pipelines.

All other elements, including the custom Convolutional Neural Network (CNN) architecture built for fault classification, the closed-loop PID control logic, and the specific dataset generation, represent original work conducted for this project.'
