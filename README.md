# transfer-learning-with-different-datasets
(currently working)

Objective of this project is to analyze the performance of transfer learning on variety of datasets such as smaller/larger, similar/dissimilar to the original dataset, and figure out what changes can be made to our model to improve its performance.

Model used for Transfer Learning: ResNet50

As we know performance of transfer learning could depend on many factors, such as when:

   1. New dataset is small and similar to original dataset
   2. New dataset is large and similar to the original dataset
   3. New dataset is small but very different from the original dataset
   4. New dataset is large and very different from the original dataset
   
   Example of similar/dissimilar dataset:
   
   Since the ImageNet dataset used to train ResNet50 includes many dog pictures, our new dataset of dog breeds would be much more    similar to it than a dataset that contains many types of leaves.
   
Based on above scenarios, we could take different approach 
