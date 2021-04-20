# Face_recogintion_using_inception_model
This model is built to recognize or verify human faces. Many of the ideas presented here are from FaceNet. 
Face recognition problems commonly fall into two categories:
   * Face Verification - "is this the claimed person?
   * Face Recognition - "who is this person?"
FaceNet learns a neural network that encodes a face image into a vector of 128 numbers. By comparing two such vectors, you can then determine if two pictures are of the same person. We will be using a pre-trained model which represents ConvNet activations using a "channels first" convention
