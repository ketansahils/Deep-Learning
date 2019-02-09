* Data Source: http://vision.seas.harvard.edu/pubfig83/
* VGG-Model Pretrained model: https://keras.io/applications/#available-models
* VGG-Model Serialized model retrained for 83 Images: https://drive.google.com/open?id=1TLo6WRnV5Qtwe-k0ul48pLO-bm7-mB0D
* Infra: https://colab.research.google.com/

Here are a few images from the dataset. Each image is rescaled to 160x160.
![Results](https://github.com/ketansahils/Deep-Learning/blob/master/VGG16%20-%20Transfer%20Learning/data-snapshot.png)

Unlike most other existing face datasets, these images are taken in completely uncontrolled situations with non-cooperative subjects. Thus, there is large variation in pose, lighting, expression, scene, camera, imaging conditions and parameters, etc. 

<h2>We observe 71.3% accuracy for Top-1 predicted class and 90.1% for Top-5 predicted classes.</h2>

Here are a couple of misclassified examples:
![Results](https://github.com/ketansahils/Deep-Learning/blob/master/VGG16%20-%20Transfer%20Learning/Picture1.png)

**Next Steps:** Tuning the Hyperparameters, Model architecture and getting more training data to improve Top-1 accuracy.
