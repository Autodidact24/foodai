[//]: # (Image References)


# Food-101

## Introduction

In this project, we are designing an algorithm that can visually differentiate between different types of food.

The dataset contains images of food, organized by type of food. It was used in the Paper "Food-101 – Mining Discriminative Components with Random Forests" by Lukas Bossard, Matthieu Guillaumin and Luc Van Gool. It's a good (large dataset) for testing computer vision techniques.

## Getting Started

1. Clone the [repository](https://github.com/Autodidact24/foodai) and create a `data/` folder to hold the Food 101 dataset
```text
git clone https://github.com/Autodidact24/foodai
mkdir data; cd data
```

2. Create folders to hold the training, validation, and the test images.
```text
mkdir train; mkdir valid; mkdir test
```

## Create a Model
Use the training and validation data to train a model that can distinguish between the pictures of 101 types of food.

## Evaluation

### >85% accuracy for the top-1 for the test set

