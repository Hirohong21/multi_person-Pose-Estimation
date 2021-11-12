# multi_person-Pose-Estimation
# Models
## tensorflow
## Movenet.MultiPose
  A convolutional neural network model that runs on RGB images and predicts human joint locations of people in the image frame. The main differentiator between this MoveNet.MultiPose and its precedent, MoveNet.SinglePose model, is that this model is able to detect multiple people in the image frame at the same time while still achieving real-time speed. The model was designed to be run in the browser using TensorFlow.js or on devices using TensorFlow Lite, targeting movement/fitness activities. The released variant “Lightning” can run at >30FPS on most modern laptops and detects up to 6 people simultaneously while achieving good performance.
