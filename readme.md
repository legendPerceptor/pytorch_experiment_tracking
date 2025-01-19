# PyTorch Experiment Tracking

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/legendPerceptor/pytorch_experiment_tracking/blob/main/experiment_tracking.ipynb)

The purpose of this repo is to provide a notebook that tracks the training process of different models to classify food images on the Food101 dataset. We use [EfficientNet series](https://pytorch.org/vision/main/models/efficientnet.html) as the backbone network. We change the classification layer to use transfer learning to fit the [Food101 dataset](https://pytorch.org/vision/main/generated/torchvision.datasets.Food101.html).

We will use Tensorboard to visualize the loss and accuracy curves. The notebook is designed to be run in VSCode locally.

The notebook serves as a reference for myself when encountering similar tasks in the future.
