# Advanced Machine Learning

### GTSRB Traffic Sign Image Multi-class Classification Part III
### Final Report Part III coming soon
using Python

by Sean Sungil Kim

This project is a follow-up of the GTSRB Traffic Sign Recognition Project Part I and II. The objective of this project is the same as that of Part I. In this project, the main focus was on exploring different architectures of the ConvNets (small, medium, medium-large). Due to the small original size of the GTSRB images, limited time and limited computing power, extremely big CNN architectures were not explored. The fully connected layers (or the actual classifier layers) had the same architecture (Dense-Dropout-Dense) and parameters for all models in this project. Although the medium-large architectures (Conv-Pool-Conv-Pool-Conv-Pool-Dropout) took longer to train because of the depth of the ConvNet, the performance was lower than the medium architectures. The best CNN architecture for the GTSRB dataset was in fact medium (Conv-Conv-Pool-Dropout). The validation precision, recall, and f-score were 0.982360, 0.981919 and 0.981933 respectively. These performance scores were better than those of all models analyzed in Part I and II. The total runtime of the final CNN model was significantly faster than some of the boosting algorithms explored in Part I, despite the best performance scores. The importance and power of deep learning algorithms for image recognition problems were proven in this project.

The GTSRB dataset can be downloaded here: http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset
