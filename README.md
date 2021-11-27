# Handwritten-Math-Symbols-82-Class-

Similar to a previous work of mine, in here I have decided to classify Handwritten Math Symbols on 82 classes. 
Details of the dataset used: 

Original source, that was parsed, extracted and modified is the CROHME dataset.
Visit CROHME at http://www.isical.ac.in/~crohme/index.html. 

The dataset can be found at: https://www.kaggle.com/xainano/handwrittenmathsymbols.

The model trained on the number of samples:
| Training | Validation  | Test  |
| ------------- | ------------- | ------------- |
| 300746| 56359 | 18869 |

All images were converted to 25x25 pixels. Due to the nature of the images this resolution was sufficient enough. Also the images were transformed into grayscale images as color didn't help in classification rather the model learned shapes to classify.

The final accuracy achieved without using augmentation was:

| Training | Validation  | Test  | F1-Score |
| ------------- | ------------- | ------------- | ------------- |
| 94.62%| 96.76 | 96.71 | 0.97 |

This is a working project. Using this in anywhere without the permission of the owner is extemely prohibited.
