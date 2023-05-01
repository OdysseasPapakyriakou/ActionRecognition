# Action recognition in videos using a two-stream CNN
This project trains several CNN models for action recognition, culminating in a two-stream CNN where one stream comes from the optical flow of the videos, and the other stream comes from the middle frame.

### Model 1: Stanford40 image dataset
* Custom ResNet CNN

### Model 2: HMDB51 video dataset
* Finetuned based on model 1 using the middle frame of the videos

### Model 3: HMDB51 dataset
* Custom 3D ResNet CNN on optical flow from the videos

### Model 4: HMDB51 dataset
* Two-stream network, where one stream comes from model 1 and the other from model 2
* Several different types of fusion were tested: *average*, *concatenation*, *maximum*, *minimum*

The user is advised to read the report for a comprehensive description of the project.
