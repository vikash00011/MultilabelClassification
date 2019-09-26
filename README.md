# MultilabelClassification
In some cases you may want your classifier to output multiple classes for each instance. So this Hands on to cover this aspect.
For example,consider a face-recognition classifier: what should it do if it recognizes several people
on the same picture? Of course it should attach one tag per person it recognizes. Say the classifier has been trained to recognize
three faces, Alice, Bob, and Charlie; then when it is shown a picture of Alice and Charlie, it should output 
[1, 0, 1] (meaning “Alice yes, Bob no, Charlie yes”). Such a classification system that outputs multiplebinary tags is called a multilabel
classification system.

Pre-requesite: Please follow below seriarly

https://github.com/vikash00011/BinaryClassification

https://github.com/vikash00011/MulticlassClassification

