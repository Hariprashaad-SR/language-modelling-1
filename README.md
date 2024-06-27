# language-modelling-1
### (Linear model using pytorch)

Language modeling using PyTorch and a linear neural network involves predicting the probability of a sequence of words in a language. In this approach, words are first converted into vector representations (embeddings). These embeddings are then concatenated and passed through linear layers, which apply linear transformations to capture relationships between words. Optimization techniques like gradient descent are used to update the model's weights, and normalization techniques such as Batch Normalization can be applied to stabilize and accelerate training. The model's predictions are typically made using softmax to output probabilities for each word in the vocabulary, and cross-entropy loss is used to measure the performance of the model. This setup provides a simple yet effective framework for understanding and generating natural language text.

Here, 
- mlp
- optimise initialisation
- pytorch implementation
- backpropagation

Reference : [Andrej karpathy Github](https://github.com/karpathy)
