
  
## Neuro - Face Mask Detector
<img src="https://i.ibb.co/hycmyB2/neuro.png" width="640" height="360">


Neuro is a face mask detector that utilizes a Deep Neural Network (Convolutional Neural Network / CNN) to differentiate between images of people with and without face masks. The CNN achieves an accuracy of **98%** on the training set and a **97%** accuracy on the test set. The stored weights of this CNN are then used to classify between *mask* or *no mask* in real time with OpenCV. The data used can be d

Main Functionalities:
* Multiple faces (with/without face masks) can be detected at the same time.
* No apparent lag time between wearing/removing masks and detection.


### Built With
* [Python](https://www.python.org/)
* [TensorFlow](https://www.tensorflow.org/)
* [OpenCV](https://opencv.org/)
* [DataFlair (Link to dataset used)](https://data-flair.training/blogs/download-face-mask-data/)



## Getting Started

To get a local copy up and running follow these simple example steps.

1. Clone the repo
   ```sh
   git clone https://github.com/mannan-arora/neuro.git
   ```
2. Install required libraries
   ```sh
   pip install -r requirements.txt
   ```
3. Execute the following command 
   ```sh
   python facemask.py
   ```
