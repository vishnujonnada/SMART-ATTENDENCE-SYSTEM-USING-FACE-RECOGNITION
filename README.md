# SMART-ATTENDENCE-SYSTEM-USING-FACE-RECOGNITION
                        SMART ATTENDENCE SYSTEM USING FACE RECOGNITION
In this project, we utilized a combination of algorithms for face detection and recognition:

Face Detection: We used the HOG (Histogram of Oriented Gradients) algorithm combined with a Linear SVM (Support Vector Machine). HOG is effective for detecting the locations of faces in an image by capturing the edge directions and textures. This method is computationally efficient and works well in real-time applications.

Face Recognition: For recognizing faces, we used the face recognition library, which is based on a deep learning model. Specifically, it uses the ResNet (Residual Network) architecture implemented in the dlib library. The model generates 128-dimensional embeddings for each face, which are then compared using Euclidean distance to identify and recognize individuals.

These combined techniques allow for accurate and efficient real-time face detection and recognition
