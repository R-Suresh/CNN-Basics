# CNN Basics
1. CNN for CIFAR10 with and without [image data augmentation](https://github.com/R-Suresh/Neural_Network_Basics) is ```CIFAR10 CNN.ipynb```

1. Object Detection with above CIFAR10 model is in ```Car Object Detection.ipynb```<br>

| Input        | Output           | Filename  |
| ------------- |:-------------:| -----:|
|![](https://github.com/R-Suresh/CNN-Basics/blob/master/Input.jpg)| ![](https://github.com/R-Suresh/CNN-Basics/blob/master/output_new.jpg)| ```cropped.jpg``` |
|![](https://github.com/R-Suresh/CNN-Basics/blob/master/Input2.jpg)| ![](https://github.com/R-Suresh/CNN-Basics/blob/master/output2.jpg)| ```cropped2.jpg``` |

3. Basic image classifier using tensorflow. 
This current model is used to differentiate between 2 celebrities.

To run 
* Add files from [google drive](https://drive.google.com/file/d/1N0hOM0FD9hhB16kiZM4RNLLo--IVz2t9/view?usp=sharing)
* Unzip them and add them to the same directory as the rest of the content.
* Excecute ```python label_image.py <imagename.jpg>``` 

4. Keras Pretrained image classifier
Uses models pretrained on the image net task as is

To run
* Run the ```keras pretrained image classification.ipynb``` file

3. Keras Transfer learning
Use VGG model prerained on the imagenet task and transfer its learning to the task at hand<br>
Dataset can be found in ```images.rar```.<br>
Model trained for classifing human emotions into 6 basic categories is the [final_emotion_model.hdf5](https://drive.google.com/open?id=1UWnHx90XVJxx4xrxvrNILi6ZkEHn0e_M). Unzip the rar file and put in the directory.<br>
To run
* Run the ```Image Classification.ipynb``` file
* To run the classification model and deployment on a custom image use ```Image Classification and deployment.ipynb```
