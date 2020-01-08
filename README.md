# Local-Decision
Overview of session plan for the class on attribution methods for single examples.

## Outline
From the first class, the students will have trained an MNIST classifier,
and looked at per-example gradients to 'solve' the Decoy MNSIT task.
We'll have a total of 90 mins.

### Introduction (10-15 mins)
Introduce attribution methods and set up the lab.

### Computer Vision
1. Experiment 1 (20 mins):
   - Train and/or load a pre-trained model on MNIST/Fashion MNIST.
   - Implement Gradient, SmoothGrad, & Integrated Gradients.
   - Look at SmoothGrad & Integrated Gradients maps for different examples.

2. Experiment 2 (10 mins):
   - Load a pre-trained CNN on ImageNet (VGG/Inceptionv3/Resnet-50).
   - Look at Gradient, SmoothGrad, & Integrated Gradients maps for a few examples.

2. Experiment 3 (?):
   - Implement some other methods?
   - Look at a different model?

### NLP
1. Experiment 1 (20 mins):
   - Train and/or load a pre-trained model on toy task (?).
   - Implement Gradient, SmoothGrad, & Integrated Gradients.
   - Look at Gradient, SmoothGrad, & Integrated Gradients maps for different examples.

2. Experiment 2 (10 mins):
   - Load a pre-trained model on SST (?).
   - Look at Gradient, SmoothGrad, & Integrated Gradients maps for a few
   examples.

2. Experiment 3 (?):
   - Implement some other methods?
   - Look at a different model?

### Conclusion (10-15 mins)
We will discuss the state of affairs as well currently stand.

1. Assessment. Given the wealth of methods in this category, how do you choose?

2. Perspective from NLP and challenges that occur in discrete domain.