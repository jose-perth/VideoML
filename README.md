# VideoML
Test on video classification models

## Test 1: determine presence of 1 of 2 characters
Use an already labeled video to determine time on screen of main characters.

- use cv2 to split video into 1 frame per second, saving the frame to output folder
- read frames into an np.array
- one hot encode categorical label
- resize all images to VGG16 requirements 224x224x3
- preprocess array
- split into training and validation sets
- process using VGG16 pretrained model
- reshape inputs

