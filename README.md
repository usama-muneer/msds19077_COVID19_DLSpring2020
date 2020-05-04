# msds19077_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.

# PART 1: Dataset
Dataset used for this assignment can be found using link blow: 

https://drive.google.com/file/d/1-HQQciKYfwAO3oH7ci6zhg45DduvkpnK/view?usp=sharing

# Task 1: Load pretrained CNN model and fine-tune FC Layers
Our task is to fine-tune Fully Connected layers of ResNet-18 and VGG-16 pretrained models by adding two custom layes and freezed other layer then train model on given dataset. And the results are given blow:
</br></br>
```ResNet-18 Results after find-tune FC Layers:```
</br></br>
![](Results/resnet18_FC_Control_curves.png)
![](Results/resnet18_FC_Control_results.png)

</br></br>
```VGG-16 Results after find-tune Classifier:```
</br></br>
![](Results/vgg16_FC_Only_curves.png)
![](Results/vgg16_FC_Only_results.png)

# Task 2: Fine-tune the CNN and FC layers of the network
Our task is to fine-tune Fully Connected and classifier layers of ResNet-18 and VGG-16 pretrained models by unfreezing different layes then train model on given dataset. And the results are given blow:

</br></br>
```ResNet-18 Results after unfreezing all layers:```
</br></br>
![](Results/resnet18_entire_curves.png)
![](Results/resnet18_entire_results.png)

</br></br>
```VGG-16 Results after unfreezing all layers:```
</br></br>
![](Results/vgg16_entire_curves.png)
![](Results/vgg16_entire_results.png)

# Trained Models:
<p>Trained weights for this dataset can be found using this link:</p><a href="https://drive.google.com/open?id=1evAZB1c9GfsWA-uiVcbebyGkt-2oFxBa">Link</a>


<hr>

# PART 2: Dataset
<p>Dataset used for this assignment can be found using this link:</p>  <a href="https://github.com/HadiaIrshad/MSDS19016_COVID19_DLSpring2020/blob/master/README.md">Link </a>
#Task:
<p>In this task we are performing multi-class, multi-label classification by implementing focal loss for detecting infections such as COVID-19 among X-Ray images.</p>

# Experiment 1:
</br>
```ResNet-18 with Binary Cross Entropy loss with logistics:```

![](Results/resnet18-bce.png)
</br></br>
```Confusion Matrix for validation data```
</br>
![](Results/resnet18-bce-CM-valid.png)

</br>
# Experiment 2:
</br>
```VGG-16 with Binary Cross Entropy loss with logistics:```

![](Results/vgg16-bce.png)
</br>
```Confusion Matrix for validation data```
</br>
![](Results/vgg16-bce-CM-valid.png)

</br>
# Experiment 3:
</br>
```ResNet-18 with Focal Loss:```

![](Results/resnet18-fl.png)
</br>
```Confusion Matrix for validation data```
</br>
![](Results/resnet18-fl-CM-valid.png)

</br>
# Experiment 4:
</br>
```VGG-16 with Focal Loss:```

![](Results/vgg16-fl.png)
</br>
```Confusion Matrix for validation data```
</br>
![](Results/vgg16-fl-CM-valid.png)

<br>
# Trained Model:
Trained weights for this dataset can be found using this link:<a href="https://drive.google.com/open?id=1aTiVv7fDUqtbkrqM2e-LfjaTWkyfPu8d">Link</a>
