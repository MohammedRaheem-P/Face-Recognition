# Face-Recognition
using pretrained inception model - Transfer Learning

Tasks:
Face Verification
Face Recognition

inputs : pretrained inception model
process > adding top layers over pretrained inception model. 
training > using triplet loss function

model gives 128 embedded vector.
based on the distance...predicting similarities

FaceNet is trained by triplet loss function
observation/eg form of (A,P,N) where A-Anchor image, P-Positive (similar)image, N-Negative(different)image

Reference : FaceNet -A Unified Embedding for Face Recognition and Clustering
