Week 6: Advanced Preprocessing & CNNs
Lab Overview
This project focuses on applying advanced image preprocessing techniques to improve OCR accuracy on real-world documents and building a Convolutional Neural Network (CNN) from scratch to recognize handwritten digits.
Part 1: Advanced PreprocessingIn this section
I implemented several algorithms to handle document quality issues like skew, noise, and perspective distortion:Perspective Correction: Created a four-point transform function to straighten documents photographed at various angles
Automatic Deskewing: Implemented an algorithm to detect the orientation of text and automatically rotate the document back to a horizontal plane.
Morphological Operations: Applied Erosion, Dilation, Opening, and Closing to remove "salt and pepper" noise and fill gaps in text characters.

Part 2: CNN from Scratch
I designed and trained a deep learning model using the MNIST dataset to understand how spatial features are extracted for digit recognition
Architecture:
Layer 1: 2D Convolution (32 filters) + ReLU Activation.
Layer 2: Max Pooling (2x2).
Layer 3: 2D Convolution (64 filters) + ReLU.
Layer 4: Max Pooling (2x2)
Dense Layers: Flatten followed by 128 units with Dropout (0.5) and a 10-unit Softmax output.
Results: The model achieved a final test accuracy of 99.10%, successfully exceeding the 98% target.


Key Achievements
Mastered advanced image preprocessing techniques to handle real-world document quality issues.
Built a custom CNN capable of high-accuracy character recognition.
Understood how deep learning architectures like convolutional and pooling layers power modern OCR systems.
