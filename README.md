# Face-Recognition
In this model, we leverage the power of both OpenCV and TensorFlow to construct a highly accurate face recognition system. OpenCV provides comprehensive tools for image processing, including face detection, alignment, and preprocessing, while TensorFlow serves as the backbone for training and deploying the Siamese neural network.

Once trained, the Siamese network can be deployed for face recognition tasks. Given a query image, OpenCV is used for face detection and alignment, followed by feeding the aligned face into the trained Siamese network. The network computes embeddings for both the query face and a database of known faces. TensorFlow's efficient computation allows for real-time comparison of embeddings, enabling rapid identification of the most similar face in the database.

This model provide 70% accuracy.
