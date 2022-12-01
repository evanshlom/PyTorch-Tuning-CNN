# PyTorch-Tuning-CNN
Compared optimizers and learning rates of PyTorch CNN for image classification.

## Image Dataset
The Fashion-MNIST dataset contains 60,000 training images (and 10,000 test images) of fashion and clothing items, taken from 10 classes. Each image is a standardized 28x28 size in grayscale (784 total pixels).

## Virtual Environment Setup
To run the program, copy the virtual environment in this repository's yml file: using the Anaconda command line, enter the command below.  
```bash
conda env create --name torch_copy_env -f torch_env.yml
```

## Conclusion
After 30 epochs, the Adam optimizer with learning rate .001 gave the best results: 94% training accuracy and 90% validation accuracy, with 17% training loss and 31% validation loss.

After 30 epochs, the neural networks gave the following results:

  > With learning rate .1, SGD optimizer gave 86% training accuracy and 85% validation accuracy, with 39% training loss and 43% validation loss.

  > With learning rate .01, SGD optimizer gave 80% training accuracy and 79% validation accuracy, with 62% training loss and 63% validation loss.

  > With learning rate .001, SGD optimizer gave 66% training accuracy and 65% validation accuracy, with 142% training loss and 141% validation loss.

  > With learning rate .1, Adam optimizer gave 84% training accuracy and 82% validation accuracy, with 46% training loss and 56% validation loss.

  > With learning rate .01, Adam optimizer gave 93% training accuracy and 88% validation accuracy, with 18% training loss and 37% validation loss.

  > With learning rate .001, Adam optimizer gave 94% training accuracy and 90% validation accuracy, with 17% training loss and 31% validation loss.
