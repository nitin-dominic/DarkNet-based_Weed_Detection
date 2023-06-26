# DarkNet-based_Weed_Detection

This repository consists of open-source DarkNet-based implementation of the paper published in the Journal of the ASABE. It consists of the configuration files and the dataset in YOLO (*.txt*) format for other researchers to develop and deploy Deep Learning-based weed detection approach. Please feel free to use the dataset but do remember to cite us in your work!

The configuration files (lightweight architecture) used in this research study needs to be merged with the original repository of [DarkNet YOLOv4](https://github.com/AlexeyAB/darknet). Once you have cloned the repository, you can bring in the dataset and start training the dataset with appropriate hyperparameter tunings/tweakings. We have also added a folder called Validation_metrics which displays all the screenshots of the metrics obtained after training on our dataset. Please refer to the original repository for more details.  

The dataset used in the paper can be found at Mendeley Data (open-source dataset repository). Please click on the link.

Sample of weed image dataset used in this ressearch study and published on Mendeley Data:

![Ragweed-1](https://raw.githubusercontent.com/nitin-dominic/DarkNet-based_Weed_Detection/main/ragweed1.png?token=GHSAT0AAAAAACC33YWNSKIB2ES77UCC7JMYZEY3A6Q)
![Ragweed-2](https://raw.githubusercontent.com/nitin-dominic/DarkNet-based_Weed_Detection/main/ragweed3.png?token=GHSAT0AAAAAACC33YWNIFDEERKGHQ4TK7IMZEY3B2A)
![Ragweed-3](https://raw.githubusercontent.com/nitin-dominic/DarkNet-based_Weed_Detection/main/ragweed4.png?token=GHSAT0AAAAAACC33YWMESE7HVXFYFEZWLGOZEY3CRQ)

Figure. Represents high-resolution aerial images used for annotation purpose, (a) yellow --- ragweed, (b) violet --- horseweed, and (c) pink --- kochia.

# !!! Please cite us if you plan to either merge this with your custom dataset or reproduce this study for your research work purpose !!!

### Data citation reference:
**Rai, N.,** Sun, X., Igathinathane, C., Howatt, K., Ostlie, M. (2023). SpotWeeds Annotated Dataset - Journal of the ASABE. Mendeley Data, V1, doi: 10.17632/m7g3yvzcs7.1.

### Paper citation reference:
**Rai, N.,** Sun, X., Igathinathane, C., Howatt, K., Ostlie, M. (2023). Aerial-based weed detection using low-cost and lightweight deep learning models on an edge platform. Journal of the ASABE. doi: xxx
