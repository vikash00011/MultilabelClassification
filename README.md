# MultilabelClassification
In some cases you may want your classifier to output multiple classes for each instance. So this Hands on to cover this aspect.
For example,consider a face-recognition classifier: what should it do if it recognizes several people
on the same picture? Of course it should attach one tag per person it recognizes. Say the classifier has been trained to recognize
three faces, Vikash, Sachin, and Abhishek; then when it is shown a picture of Vikash and Abhishek, it should output 
[1, 0, 1] (meaning “Vikash yes, Sachin no, Abhishek yes”). Such a classification system that outputs multiplebinary tags is called a multilabel
classification system.

Pre-requesite: Please follow below seriarly

https://github.com/vikash00011/BinaryClassification

https://github.com/vikash00011/MulticlassClassification

