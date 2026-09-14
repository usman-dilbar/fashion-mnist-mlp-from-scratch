# fashion-mnist-mlp-from-scratch

# Fashion MNIST Neural Network from Scratch

A neural network built on Fashion MNIST, starting with backprop written by hand
in plain numpy, then moving to a proper PyTorch model - testing different
activations, loss functions, optimizers, and regularization along the way.

Roll no: 23F-0576 Minahil Fatima, 23F-0618 Usman Dilbar.

## What's inside

- Part 1: a 2-layer MLP written with plain numpy, no autograd, checked against
  PyTorch to make sure the gradients actually match
- Part 2: comparing sigmoid, tanh, relu and leaky relu on the same network
- Part 3: cross-entropy vs MSE loss, plus a small regression task
- Part 4: comparing SGD, SGD+momentum, RMSProp and Adam
- Part 5: forcing the model to overfit on purpose (small dataset, big network)
- Part 6: trying to fix the overfitting - L2, L1, dropout, batchnorm, early
  stopping, data augmentation, more data
- Part 7: hyperparameter search with 5-fold cross validation, then final test
  set evaluation

## How to run it

1. Open the notebook on Kaggle
2. Add the Fashion MNIST dataset (search "Fashion MNIST", pick the one from
   zalando-research)
3. Turn on GPU under Settings > Accelerator (needs phone verification if you
   haven't done that already)
4. Run all cells top to bottom

Part 7 (the cross validation part) takes the longest to run, so don't panic if
it takes a few minutes.

## Notes

Random seed is fixed at 42 everywhere so results should be reproducible.
Dataset used: Fashion MNIST from Kaggle (zalando-research/fashionmnist).
